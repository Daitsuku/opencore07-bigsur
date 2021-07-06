# opencore0.7-bigsur
OpenCore Folder For Dell Haswell Laptop

*What's folder doesn't include*
  - *SSDT-PLUG* (do one for yourself via SSDTTime) 
  - *SMBIOS* (Use MacBookAir6,2 . generate one for yourself)
  - DSDT

**__Don't forget to do snapshot after you put SSDT-PLUG into your EFI__**

__What's should you know?__
  - This folder is for laptop using RTL8100/8111
  - This folder is for laptop useing Intel wifi that's compatible with AirportItlwm
    - *see compatible listing : https://openintelwireless.github.io/itlwm/Compat.html*
  - This folder using SSDT-SHUTDOWN FIX (guide by dortania here : https://dortania.github.io/OpenCore-Post-Install/usb/misc/shutdown.html)
    - if you wish for dsdt shutdown patch fix, please remove "FixShutdown-USB-SSDT" and "_PST to ZPST" as well.

  - # __i'm not responsible for brick or else that would happened to your laptop, use my EFI at your own risk.__
