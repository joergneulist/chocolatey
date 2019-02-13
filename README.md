# Chocolatey Setup

* Run the following in an admin powershell to install **chocolatey**:

`Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))`

* Then, to install the base setup:

`choco install -y base.config`
