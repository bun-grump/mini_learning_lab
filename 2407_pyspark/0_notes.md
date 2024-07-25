# to set up sparks correctly on windows

1. download JDK, make sure the version supports sparks (maybe only up to 17)
2. download Apache sparks
3. download python (maybe only up to 3.11.8)
4. download hadoop winutils and hadoop.dll (the right version)
5. setup the environment variable correctly to point to the correct files/folders
6. python environment variables needs to be explicitly pulled every time the program is run
7. if path cannot be configured correctly in the system, can use the .exe file location
8. After putting hadoop.dll and winutils in hadoop/bin folder and adding the folder of hadoop to PATH, also need to put hadoop.dll into the C:\Windows\System32 folder
