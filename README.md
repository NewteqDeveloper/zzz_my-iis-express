# my-iis-express
This contains the IIS express settings used for my work laptop

# Where is everything located?

These settings must go in the Documents folder of the user under IIS Express (e.g. `C:\Users\user.name\Documents\IIS Express`)

The following three environment variables are set by iisexpress.exe during the process startup:
  - `%IIS_BIN%` - refers to IIS Express installation folder `(%PROGRAMFILES%\IIS Express)`
  - `%IIS_USER_HOME%` - `%USERPROFILE%\Documents\IISExpress`
  - `%IIS_SITES_HOME%` - `%USERPROFILE%\Documents\My Web Sites`
  - `%SYSTEMDRIVE%` - is a standard windows system environment variable

# What is this for?

This is just for reference purposes and to allow me to see a history of changes so that I can make things easier in the future without having to install full IIS.

This is to help give a basic template of what is required to set up a IIS Express site, because it's all XML based, and poitns to a directory.
