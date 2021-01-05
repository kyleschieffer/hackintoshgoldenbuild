# hackintoshgoldenbuild
EFI and Config Files for Perfectly Configured Hackintosh on Z490 Motherboard

This repository contains configuration files and tools to build a perfect Hackintosh with the following hardware:

Asus ROG-Strix Z490 Gaming-E Motherboard<br>
Intel Core i7 10700K CPU
 Stably overclocked at 5.1 GHz
Radeon RX 5700XT Graphics
Broadcom 20702 wireless card
Atheros 8111 Dual-Port Gigabit LAN card

Focusrite Scarlett 6i6 Sound Interface

Storage

NVMe
  Samsung 970 EVO NVMe Boot Drive
    macOS Big Sur - 500 GB
  WD Black NVMe
    Windows 10 - 500 GB

SATA
  Samsung 860 EVO SSD
    Libraries - 1 TB
  Samsung 860 EVO SSD
    Libraries 2 - 1 TB
  1 Crucial MX500 SSD
    Virtualization Station - 1 TB
  1 Crucial MX300 SSD
    Ubuntu - 525 GB

USB 3.2
  Samsung T7 USB SSD
    Working Projects - 500 GB

PCIe Sata Port Adapter
  Seagate Barracuda HDD 
    Time Machine - 4 TB
  WD 80EDAZ HDD
    Jazzy Repository - 8 TB
    
The second NVMe slot (my Windows Boot Drive) shares a bus with SATA ports 5 and 6, so in order to prevent throttling my high speed drive,
my two lower-speed HDDs are connected to a discreet SATA expansion card.  In order to boot from Time Machine, Compatibility Support Module (CSM)
must be enabled.

The Integrated Intel 2.5G Ethernet works!
Time Machine works!
Facetime and Messages work!
AirDrop works!
Multi-monitor, including with a DisplayLink USB display, works!
Virtualization works!

Multi boot with Windows and Linux, with a clean, custom GUI based on rEFInd Boot Manager.
Stable boot priority
Time zone issues between OSes, fixed
Bluetooth sharing between OSes, fixed
USB ports are mapped, but the kext must be patched with your own system-id to work.

Windows:
Sharpkeys Config - Keyboard remap to shuffle Ctl ^, Win/Cmd ⌘, and Alt/Opt ⌥ for most Mac keyboard shortcuts
Autohotkey Scripts - Additional command remaps to make the keyboard shortcuts feel like macOS

Linux:
Displaylink Driver

Things to improve:
EDID discrepancies with DisplayLink monitor when changing OSes.
Autohotkey Keyboard Remap Script don't work when active windows has administrator privileges.
My consumerism wants a Big Navi.  Config will update when my physical rig reflects this.
