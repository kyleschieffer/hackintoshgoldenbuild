# hackintoshgoldenbuild
EFI and Config Files for Perfectly Configured Hackintosh on Z490 Motherboard

This repository contains configuration files and tools to build a perfect Hackintosh with the following hardware:

Asus ROG-Strix Z490 Gaming-E Motherboard<br>
Intel Core i7 10700K CPU
 Stably overclocked at 5.1 GHz<br>
Radeon RX 5700XT Graphics<br>
Broadcom 20702 wireless card<br>
Atheros 8111 Dual-Port Gigabit LAN card<br>
Focusrite Scarlett 6i6 Sound Interface<br>

Storage

NVMe<br>
  Samsung 970 EVO NVMe Boot Drive<br>
    macOS Big Sur - 500 GB<br>
  WD Black NVMe<br>
    Windows 10 - 500 GB<br>

SATA<br>
  Samsung 860 EVO SSD<br>
    Libraries - 1 TB<br>
  Samsung 860 EVO SSD<br>
    Libraries 2 - 1 TB<br>
  1 Crucial MX500 SSD<br>
    Virtualization Station - 1 TB<br>
  1 Crucial MX300 SSD<br>
    Ubuntu - 525 GB<br>

USB 3.2<br>
  Samsung T7 USB SSD<br>
    Working Projects - 500 GB<br>

PCIe Sata Port Adapter<br>
  Seagate Barracuda HDD <br>
    Time Machine - 4 TB<br>
  WD 80EDAZ HDD<br>
    Jazzy Repository - 8 TB<br>
    
The second NVMe slot (my Windows Boot Drive) shares a bus with SATA ports 5 and 6, so in order to prevent throttling my high speed drive, my two lower-speed HDDs are connected to a discreet SATA expansion card.  In order to boot from Time Machine, Compatibility Support Module (CSM) must be enabled.<br>

The Integrated Intel 2.5G Ethernet works!<br>
Time Machine works!<br>
Facetime and Messages work!<br>
AirDrop works!<br>
Multi-monitor, including with a DisplayLink USB display, works!<br>
Virtualization works!<br>

Multi boot with Windows and Linux, with a clean, custom GUI based on rEFInd Boot Manager.<br>
Stable boot priority<br>
Time zone issues between OSes, fixed<br>
Bluetooth sharing between OSes, fixed<br>
USB ports are mapped, but the kext must be patched with your own system-id to work.<br>

Windows:<br>
Sharpkeys Config - Keyboard remap to shuffle Ctl ^, Win/Cmd ⌘, and Alt/Opt ⌥ for most Mac keyboard shortcuts<br>
Autohotkey Scripts - Additional command remaps to make the keyboard shortcuts feel like macOS<br>

Linux:<br>
Displaylink Driver<br>

Things to improve:<br>
EDID discrepancies with DisplayLink monitor when changing OSes.<br>
Autohotkey Keyboard Remap Script don't work when active windows has administrator privileges.<br>
My consumerism wants a Big Navi.  Config will update when my physical rig reflects this.<br>
