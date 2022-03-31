# Windows-Choco-Install
PowerShell script to automate chocolatey install and update process of software.

Tested on Windows 10 Pro and Home

1. Update "apps.txt" with desired software packages to be installed.
2. Run the update script in Admin mode.
3. Be sure to set ExecutionPolicy to allow scripts to run on your system.
4. If Chocolatey is not installed, it will download and install this first.
5. Any software package listed in "apps.txt" will now be installed/updated if necessary.
6. Chocolatey Logs can be used to troubleshoot if needed.

Find packages and more information on Chocolatey here:
https://community.chocolatey.org/packages
https://docs.chocolatey.org/en-us/
