---
title: Windows Setup
permalink: /tools/
---

## Windows Settings

### **Windows[_](/assets/win.zip)Defender**

Exclude Folder `C:\Windows\AutoKMS\`

### **Privacy Settings**

Disable unwanted features

### **Remove One Drive**

`gpedit.msc`

*Local Computer Policy > Computer Configuration > Administrative Templates > Windows Components > OneDrive*

Set Prevent the usage of OneDrive for file storage [**ENABLED**]
Set Prevent the usage of OneDrive for file storage for Windows 8.1 [**ENABLED**]

`taskkill /f /im OneDrive.exe`

`%SystemRoot%\SysWOW64\OneDriveSetup.exe /uninstall`

`rd "%UserProfile%\OneDrive" /Q /S`

`rd "%LocalAppData%\Microsoft\OneDrive" /Q /S`

`rd "%ProgramData%\Microsoft OneDrive" /Q /S`

`rd "C:\OneDriveTemp" /Q /S`

`REG Delete "HKEY_CLASSES_ROOT\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}" /f`

`REG Delete "HKEY_CLASSES_ROOT\Wow6432Node\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}" /f`

### Trim SSD

`fsutil behavior set DisableDeleteNotify 0`

### Indexing Options

`control.exe srchadmin.dll`

*Modify > Remove > Users*

### **Power Options**

`control powercfg.cpl`

- High performance [**Active**]
- Hard disk [**Turn off after: 0**]

### Windows Updates

`ms-settings:windowsupdate`

### Mouse Settings

`main.cpl`

*Pointer Options > Uncheck: Enhance Pointer Precision*



## Applications

### Windows Setup

- [10se1ucgo](https://github.com/10se1ucgo/DisableWinTracking/releases/latest)
- [Disassembler0](https://github.com/Disassembler0/Win10-Initial-Setup-Script/releases)

### Drivers

- [RX480](https://www.amd.com/en/support/graphics/radeon-400-series/radeon-rx-400-series/radeon-rx-480)

### Software

- [Ninite](https://ninite.com/7zip-audacity-chrome-discord-everything-handbrake-klitecodecs-qbittorrent-revo-sharex-skype-spotify-steam-zoom/)

- [Space Sniffer](http://www.uderzo.it/main_products/space_sniffer/download.html)
- [Wizmouse](https://antibody-software.com/web/software/software/wizmouse-makes-your-mouse-wheel-work-on-the-window-under-the-mouse/)

- [Adobe Acrobat Reader](https://get.adobe.com/reader/)

- [Adobe Photoshop](https://prodesigntools.com/adobe-cc-2018-direct-download-links.html)

- [Aseprite](https://dacap.itch.io/aseprite)

- [Git](https://git-scm.com/download/win)

- [GitKraken](https://www.gitkraken.com/download/windows64)

- [JetBrains Rider](https://www.jetbrains.com/rider/download/#section=windows)

- [Microsoft Visual C++](https://www.techpowerup.com/download/visual-c-redistributable-runtime-package-all-in-one/)

- [RescueTime](https://www.rescuetime.com/download_windows)

- [ScreenToGIF](https://www.screentogif.com/downloads)

- [Sublime Text](https://www.sublimetext.com/3)

- [Typora](https://typora.io/#windows)

- [Unity Hub](https://public-cdn.cloud.unity3d.com/hub/prod/UnityHubSetup.exe)

### Extensions

- [AMTEmu](https://www.zippyshare.com/plank28/bihtn6ew/dir.html)

- [LastPass](https://chrome.google.com/webstore/detail/lastpass-free-password-ma/hdokiejnpimakedhajhdlcegeplioahd)

- [HTTPS Everywhere](https://chrome.google.com/webstore/detail/https-everywhere/gcbommkclmclpchllfjekcdonpmejbdp?hl=en)

- [uBlock Origin](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm?hl=en)