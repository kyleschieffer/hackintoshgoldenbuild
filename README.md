# hackintoshgoldenbuild</b>
<h2>EFI and Config Files for Perfectly Configured Multi-Boot Hackintosh on Z490 Motherboard

<h3>This repository contains configuration files and tools to build a perfect Hackintosh with the following hardware:<br>

<h5>Asus ROG-Strix Z490 Gaming-E Motherboard<br>
Intel Core i7 10700K CPU<br>
<h6> Stably overclocked at 5.1 GHz<br>
<h5>Radeon RX 5700XT Graphics<br>
Broadcom 20702 wireless card<br>
Atheros 8111 Dual-Port Gigabit LAN card<br>
Focusrite Scarlett 6i6 Sound Interface<br>

<h4>Storage

<h5>NVMe<br>
<h6>  Samsung 970 EVO NVMe Boot Drive<br>
    macOS Big Sur - 500 GB<br>
  WD Black NVMe<br>
    Windows 10 - 500 GB<br>

<h5>SATA<br>
<h6>  Samsung 860 EVO SSD<br>
    Libraries - 1 TB<br>
  Samsung 860 EVO SSD<br>
    Libraries 2 - 1 TB<br>
  Crucial MX500 SSD<br>
    Virtualization Station - 1 TB<br>
  Crucial MX300 SSD<br>
    Ubuntu - 525 GB<br>

<h5>USB 3.2<br>
<h6>  Samsung T7 USB SSD<br>
    Working Projects - 500 GB<br>

<h5>PCIe Sata Port Adapter<br>
<h6>  Seagate Barracuda HDD <br>
    Time Machine - 4 TB<br>
  WD 80EDAZ HDD<br>
    Jazzy Repository - 8 TB<br>
   
<h5>The second NVMe slot (my Windows Boot Drive) shares a bus with SATA ports 5 and 6, so in order to prevent throttling my high speed drive, my two lower-speed HDDs are connected to a discreet SATA expansion card.  In order to boot from Time Machine, Compatibility Support Module (CSM) must be enabled.<br>

<h4>Features:
<h5>Multi boot with Windows and Linux, with a clean, custom GUI based on rEFInd Boot Manager.<br>

<h4>macOS
<h5>The Integrated Intel 2.5G Ethernet works!<br>
Time Machine works!<br>
Facetime and Messages work!<br>
AirDrop works!<br>
Multi-monitor, including with a DisplayLink USB display, works!<br>
Virtualization works!<br>
USB ports are mapped, but the kext must be patched with your own system-id to work.<br>

<h4>Windows:<br>
<h5>Sharpkeys Config - Keyboard remap to shuffle Ctl ^, Win/Cmd ⌘, and Alt/Opt ⌥ for most Mac keyboard shortcuts<br>
Autohotkey Scripts - Additional command remaps to make the keyboard shortcuts feel like macOS<br>

<h4>Linux:<br>
<h5>Displaylink Driver<br>

<h4>Multi-Boot Issues:
<h5>Stable boot priority<br>
Time zone issues between OSes, fixed<br>
Bluetooth sharing between OSes, fixed<br>

<h4>Things to improve:<br>
<h5>EDID discrepancies with DisplayLink monitor when changing OSes.<br>
Windows 10 - Autohotkey Keyboard Remap Script doesn't work when active window has administrator privileges.<br>
