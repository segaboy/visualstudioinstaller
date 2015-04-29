# visualstudioinstaller
A simple installer for Microsoft's Visual Studio Code

Microsoft recently released the Visual Studio Code application into the wild for Mac, Windows, and Linux.  This software comes as a ZIP archive from Microsoft with no installer.  This application should work in any distribution and does the following:

Downloads the ZIP archive from Microsoft. https://code.visualstudio.com/
Extracts the contents of the archive to /opt/ (after successfully downloading to temp.
Downloads a .desktop file from The Powerbase and copy the icon from the archive to /usr/share/icons.

That's pretty much it. Takes a couple of seconds to install.
