# geoserver windows installer compiler

This is a PowerShell implementation of the script described here: 
https://docs.geoserver.org/latest/en/developer/win-installer.html

The script clones the Geoserver repo, downloads NSIS and the required plugin, unzips, copies the required files from the git repository and compiles the installer.
