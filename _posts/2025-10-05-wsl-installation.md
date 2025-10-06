---
layout: default
title : "Windows Subsystem for Linux"
tags : linux
---
# Install WSL manually

Download **wsl.2.6.1.0.x64 1.msi**, install it and run as administrator : 
```powershell
Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux -NoRestart 
Enable-WindowsOptionalFeature -Online -FeatureName VirtualMachinePlatform -NoRestart
```

Download Ubuntu release : https://releases.ubuntu.com/24.04.3/ubuntu-24.04.3-wsl-amd64.wsl

Install it in a personal (user) folder

```
wsl --import Ubuntu <InstallFolder> <WSLFile.wsl>
```

In order to start a root shell just type
```
wsl
```

You can now install the needed packages for your activities, create a user ...
```bash
apt update
apt install comparepdf
apt install xmlstarlet
groupadd sylvain
useradd -s /bin/bash -m -c "sylvain" -g sylvain sylvain
```

* Windows's file are accessible from Linux in the /mnt/c folder
* Linux files are accessible from Windows using the \\\\wsl$ folder

