---
description: System requirements and 3 simple steps to successfully install the platform
---

# Installation

* [**System Requirements**](installation.md#pc-requirements)****
* ****[**Installation Steps**](installation.md#installation-steps)****
* ****[**Uninstallation**](installation.md#uninstall)****

Once you downloaded VT-Terminal application from VT-Terminal official website — you are ready to start an installation process. From this point we must clarify the main differences between VT-Terminal "installation process" and default Windows® install process, that most users are accustomed to.

{% embed url="https://youtu.be/155Ha6Rku0E" %}

{% hint style="success" %}
VT-Terminal does not copy its files to the system folders (AppData or Program Files) of the OS, nor does write changes to the system registry
{% endhint %}

What does it mean? The program doesn't violate the integrity of the OS, and in case of removal, it will not leave any prints of its presence on your computer. VT-Terminal’s "installer" literally extracts files to the user-specified folder.

This approach allows you to store (and launch) the VT-Terminal on removable drive for use on any other computer as the portable application. It can be convenient when you need to move VT-Terminal with all of its settings to another PC; just copy VT-Terminal folder and paste where you need.

### PC requirements

{% hint style="info" %}
* Windows 10
* [.NET Framework v.4.8](https://dotnet.microsoft.com/download/dotnet-framework/thank-you/net48-web-installer)
* Available disk space — 1 GB (depends on the volume of loaded history)
* **The hardware requirements for VT-Terminal depends upon what you are doing with it.** Most desktop systems can run VT-Terminal without any difficulty. 
* The following hardware specifications, are very much recommended for a fast system: 16 GB RAM, minimum of 4 core CPU, and a SSD (solid-state drive).
{% endhint %}

{% hint style="warning" %}
**Microsoft has officially stopped supporting Windows 8 and Windows 7**. Therefore, the platform may not start or may work incorrectly. [More information on supported versions, please check on official Microsoft website.](https://support.microsoft.com/en-us/help/13853/windows-lifecycle-fact-sheet)\
\
We recommend using Windows 10.
{% endhint %}

### Installation steps

![VT-Terminal installer screen](../.gitbook/assets/extract-files-quantower.png)

1. [**Download the app installer**](https://updates.quantower.com/Quantower/x64/latest/VT-Terminal.exe) and launch the _**VT-Terminal.exe**_ file
2. Select the folder to extract application files
3. Once an extraction process being finished the platform will start automatically with **Binance connection** in Info Mode and with the default workspace

{% hint style="warning" %}
Please note, that you may need to allow an in-going and outgoing connection for _**Starter.exe**_ file (the main executable of VT-Terminal terminal) in your Firewall settings
{% endhint %}

![](../.gitbook/assets/default-workspace.png)

### Uninstall

If you need to uninstall the application, just _**delete the folder with all application files**_. You may also keep your personal settings (connection information & workspaces) by copying the Settings folder (can be found right in VT-Terminal folder) before application delete. These Settings folder can be pasted to any other VT-Terminal folder later.

You may also refer to [**Backup & Restore manager**](backup-and-restore-manager.md) to backup your settings in one file and restore them later.
