# hackintoshgoldenbuild
<h2>EFI and Config Files for Perfectly Configured Multi-Boot Hackintosh on Z490 Motherboard

<h3>This repository contains configuration files and tools to build a perfect Hackintosh with the following hardware:<br>

<h4>Asus ROG-Strix Z490 Gaming-E Motherboard<br>
Intel Core i7 10700K CPU
<h5> Stably overclocked at 5.1 GHz<br>
<h4>Radeon RX 5700XT Graphics<br>
Broadcom 20702 wireless card<br>
Atheros 8111 Dual-Port Gigabit LAN card<br>
Focusrite Scarlett 6i6 Sound Interface<br>

<h2>Storage

<h3>NVMe<br>
<h4>  Samsung 970 EVO NVMe Boot Drive<br>
<h5>    macOS Big Sur - 500 GB<br>
<h4>  WD Black NVMe<br>
<h5>    Windows 10 - 500 GB<br>

<h3>SATA<br>
<h4>  Samsung 860 EVO SSD<br>
<h5>    Libraries - 1 TB<br>
<h4>  Samsung 860 EVO SSD<br>
<h5>    Libraries 2 - 1 TB<br>
<h4>  Crucial MX500 SSD<br>
<h5>    Virtualization Station - 1 TB<br>
<h4>  Crucial MX300 SSD<br>
<h5>    Ubuntu - 525 GB<br>

<h3>USB 3.2<br>
<h4>  Samsung T7 USB SSD<br>
<h5>    Working Projects - 500 GB<br>

<h3>PCIe Sata Port Adapter<br>
<h4>  Seagate Barracuda HDD <br>
<h5>    Time Machine - 4 TB<br>
<h4>  WD 80EDAZ HDD<br>
<h5>    Jazzy Repository - 8 TB<br>
    
The second NVMe slot (my Windows Boot Drive) shares a bus with SATA ports 5 and 6, so in order to prevent throttling my high speed drive, my two lower-speed HDDs are connected to a discreet SATA expansion card.  In order to boot from Time Machine, Compatibility Support Module (CSM) must be enabled.<br>

<h2>Features:
<h3>Multi boot with Windows and Linux, with a clean, custom GUI based on rEFInd Boot Manager.<br>

<h3>macOS
<h4>The Integrated Intel 2.5G Ethernet works!<br>
Time Machine works!<br>
Facetime and Messages work!<br>
AirDrop works!<br>
Multi-monitor, including with a DisplayLink USB display, works!<br>
Virtualization works!<br>
USB ports are mapped, but the kext must be patched with your own system-id to work.<br>

<h3>Windows:<br>
<h4>Sharpkeys Config - Keyboard remap to shuffle Ctl ^, Win/Cmd ⌘, and Alt/Opt ⌥ for most Mac keyboard shortcuts<br>
Autohotkey Scripts - Additional command remaps to make the keyboard shortcuts feel like macOS<br>

<h3>Linux:<br>
<h4>Displaylink Driver<br>

<h3>Multi-Boot Issues:
<h4>Stable boot priority<br>
Time zone issues between OSes, fixed<br>
Bluetooth sharing between OSes, fixed<br>

<h3>Things to improve:<br>
<h4>EDID discrepancies with DisplayLink monitor when changing OSes.<br>
Windows 10 - Autohotkey Keyboard Remap Script doesn't work when active window has administrator privileges.<br>
