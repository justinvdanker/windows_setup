# windows_setup
Installation scripts required to setup my Windows environment from scratch.

Step one is to run the `setup.ps1` file in order to install Chocolatey.
To do this please make sure to run the script in an elevated Powershell prompt.
If you run into the issue that the script is not allowed to run because of a restriction on the Execution Policy please run the following command:
`Set-ExecutionPolicy Unrestricted`

After installing Chocolatey you can install all disred programs by simply running:
`choco install .\packages.config` (in an elevated Powershell prompt)
