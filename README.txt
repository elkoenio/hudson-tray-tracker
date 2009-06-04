-- How to release

  - Update the AssemblyInfo.cs file (HudsonTrayTracker\Properties\AssemblyInfo.cs) with the new version number.
  - Commit the AssemblyInfo.cs file
  - Let Hudson build the installer
  - Get the installer from http://hudson.idm.fr/job/Hudson%20Tray%20Tracker/ws/trunk/scripts/installer/HudsonTrayTrackerInstaller.exe
  - Rename the installer with the appropriate version number (for instance HudsonTrayTrackerInstaller_v0.9.1.exe)
  - Upload the installer on the Google Code project page
  - Update the version.properties file (scripts\version.properties) with the new version number and the URL of the newly uploaded installer
  - Commit the version.properties file