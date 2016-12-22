# EFIReboot
A simple tool that allows to reboot directly to a specified (U)EFI boot entry (for example, a GNU/Linux distro)

![screen](https://github.com/pellettiero/EFIReboot/raw/master/screen.png)

__Double-click__ on any (U)EFI entry to **Reboot** into it.  
Right-click on any entry to **Reboot** into it, mark it as **BootNext** (boot into it on next boot), or **create a shortcut**.  
A shortcut can be created **with** or **without** a reboot confirmation (ask before rebooting, aka _quiet_ mode).  

You can also create a shortcut manually or script it by calling the application with the following arguments, where _ID_ is a valid ID from the entry table:  
`EFIReboot.exe ID [quiet]`
## Download
You can download it [here](https://github.com/pellettiero/EFIReboot/releases/latest).  
**.NET Framework 4.5** or later is required to run this app.
