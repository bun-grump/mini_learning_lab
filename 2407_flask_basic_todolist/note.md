# need to uncomment the create_all() when running the first time to create a database.

# create requirements.txt

pip freeze > requirements.txt

# create runtime.txt to specify python version

python-3.12.2

# create Procfile

web: gunicorn app:app

# create .gitignore

# to deploy on heroku, first login using cli

heroku login

# initialize git repo

git init

git add .
git commit -m "upload"

git remote -v
git push heroku master
