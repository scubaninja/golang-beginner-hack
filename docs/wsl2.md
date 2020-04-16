# Windows Subsystem for Linux 2.0

Golang's heritage is on Linux, therefore some choose to develop on Linux too.
The best way of doing this on a Windows PC is to install Windows Subsystem for Linux.
WSL v2 is much improved iver the initial version and will be formally released with the 2004 release of Windows 10.
However, you can install it now if you are a Windows Insider - the slow ring is fine for this.

## WSL2 Install

WSL2 can be installed if you are running Windows 10 build 18917 or higher (run ```winver``` to find out).

```pwsh
Enable-WindowsOptionalFeature -Online -FeatureName "HypervisorPlatform","Microsoft-Windows-Subsystem-Linux","VirtualMachinePlatform","Containers-DisposableClientVM"
```

You may need to restart your computer.

## WSL Set Default Version

```plain
wsl.exe --set-default-version 2
```
## Install Ubuntu from the Microsoft Store

Search for Ubuntu and install
