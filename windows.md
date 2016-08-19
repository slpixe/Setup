# Notes for installing/setting up windows for my use

## Installations
1. Google Chrome - [Download](https://www.google.com/chrome/browser/desktop/index.html)
2. Git - [Download](https://git-scm.com/download/win)
3. Nodejs - [Download](https://nodejs.org/en/download/)
4. 7Zip - [Download](http://www.7-zip.org/download.html)
5. SourceTree [Download](https://www.sourcetreeapp.com/download/)
6. VLC [Download](https://www.videolan.org/vlc/download-windows.en_GB.html)
7. PhpStorm - [Download](https://www.jetbrains.com/phpstorm/download/#section=windows-version)
8. Docker - [Download](https://download.docker.com/win/stable/InstallDocker.msi)
9. CCleaner - [Download](https://www.piriform.com/ccleaner/download/standard)
10. HeidiSQL - [Download](http://www.heidisql.com/download.php)

## Windows Features
1. Hyper-V (if docker, otherwise install VirtualBox & Vagrant)
2. Bash for Windows (Windows settings -> Update & Security -> For Developers -> Developer Mode)

## Alternatively use Chocolatey

1. Open Powershell with Admin permissions
2. Allow Powershell to run scripts `Set-ExecutionPolicy RemoteSigned`
3. Download & Install Chocolatey - `iwr https://chocolatey.org/install.ps1 -UseBasicParsing | iex`
  1. Chrome `choco install googlechrome`
  2. 7Zip `choco install 7zip.install`
  3. NodeJs `choco install nodejs.install`
  4. Nodepad++ `choco install notepadplusplus.install`
  5. Git `choco install git.install`
  6. CClearner `choco install ccleaner`
  7. VLC `choco install vlc`
  8. Atom `choco install atom`
  9. Putty `choco install putty`
  10. VirtualBox `choco install virtualbox`
  11. Paint.net `choco install paint.net`
  12. SourceTree `choco install sourcetree`
  13. Vagrant `choco install vagrant`
  14. KeePass `choco install keepass.install`
