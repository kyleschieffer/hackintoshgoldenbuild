# Hackintosh Golden Build</b>
<h3>EFI and Config Files for Perfectly Configured Multi-Boot Hackintosh on Z490 Motherboard

<h4>This repository contains configuration files and tools to build a perfect Hackintosh with the following hardware:<br>


<h4>Hardware
<h6>Asus ROG-Strix Z490-E Gaming Motherboard<br>
Intel Core i7 10700K CPU<br>
Radeon RX 5700XT Graphics<br>
Broadcom BCM4360 wireless card<br>
Atheros 8111 Dual-Port Gigabit LAN card<br>
Focusrite Scarlett 6i6 Sound Interface<br>
ASmedia PCIe x1 to SATA expansion card<br> 

<h5>Storage

<h6>Samsung 970 EVO NVMe - 500 GB<br>
&nbsp;    macOS Big Sur<br>
WD Black NVMe - 500 GB<br>
&nbsp;    Windows 10<br>
Crucial MX300 SSD - 525 GB<br>
&nbsp;    Arch Linux<br>
Samsung T7 USB SSD - 500 GB<br>
&nbsp;    Working Projects<br>
Samsung 860 EVO SSD - 1 TB<br>
&nbsp;    Libraries<br>
Samsung 860 EVO SSD - 1 TB<br>
&nbsp;    Libraries 2<br>
Crucial MX500 SSD - 1 TB<br>
&nbsp;    Virtualization Station<br>
Seagate Barracuda HDD - 4 TB<br>
&nbsp;    Time Machine<br>
WD 80EDAZ HDD - 8 TB<br>
&nbsp;    Jazzy Repository<br>
   
<h6>The second NVMe slot (my Windows Boot Drive) shares a bus with SATA ports 5 and 6, so in order to prevent throttling my high speed drive, my two lower-speed HDDs are connected to a discreet SATA expansion card.  With this configuration, Compatibility Support Module (CSM) must be enabled in order for Time Machine to appear as a boot option, however I would recommend activating it selectively on the rare occasions when that is necessary, as it otherwise results in longer boot times.<br>

<h4>What works:
  
<h3> EVERYTHING!

<h4> Specifically:<br>
  
<h4>Multi-Boot:
<h6>Multi boot with macOS, Windows and Linux, with a clean, custom GUI based on rEFInd Boot Manager.<br>
Stable boot priority<br>
Custom bootloader GUI<br>
Time zone issues between OSes fixed<br>
Bluetooth sharing between OSes fixed<br>
  
<h4>macOS:
<h6>The Integrated Intel 2.5G Ethernet works!<br>
Time Machine works!<br>
Facetime and Messages work!<br>
AirDrop works!<br>
Multi-monitor, including a fifth DisplayLink USB display, works!<br>
Virtualization works!<br>
USB ports are mapped, but the kext must be patched with your own system-id to work.<br>

<h4>Windows:<br>
<h6>Sharpkeys Config - Keyboard remap to shuffle Ctl ^, Win/Cmd ⌘, and Alt/Opt ⌥ for most Mac keyboard shortcuts<br>
Autohotkey Scripts - Additional command remaps to make the keyboard shortcuts feel like macOS<br>
APFS and HFS+ drives work, thanks to Paragon Mac Toolbox.  It's commercial software, but no alternative comes close.

<h4>Linux:<br>
<h6>sudo rm -rf /*

<h4>Things I would still like to implement:<br>
<h6>Windows 10 - Autohotkey Keyboard Remap Script doesn't work when active window has administrator privileges.<br>
Linux - APFS support, Displaylink monitor support
