# Bootloader Recovery</b>
<h4>Easily boot right back into your system when you lose boot priority.

<h6>If you reset your NVRAM or sometimes with OS updates, the system is unable to find OpenCore and boot into it, and then have to navigate to the Bootstrap.efi file from a UEFI shell and manually reactivate it.  This bootloader automatically boots into a shell and the startup script launches directly back into OpenCore, which will save its boot entry automatically from there.<br>

<h6>Add this to the EFI partition of any other drive.  (Internal is a great idea if you have an extra blank EFI partition.  I have never accidentally found internal drives in the laundry.)  Any time you get locked out of your OpenCore build and your UEFI Bios doesn't see OpenCore, boot onto that drive.<br>

The script references the filesystem where OpenCore lives on my system, but it will be necessary to adjust the filesystem in the startup.nsh file to reflect the local machine. I already recognized in the root directory's readme file that I'm a lazy hack.
