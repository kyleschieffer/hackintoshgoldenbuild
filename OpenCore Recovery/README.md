# Bootloader Recovery</b>
<h4>Easily boot right back into your system when you lose boot priority.

<h5>If you reset your NVRAM or sometimes with OS updates, the system is unable to find OpenCore and boot into it, and I'd have to navigate to the Bootstrap.efi file from a UEFI shell and manually reactivate it.  This bootloader automatically boots into a shell and the startup script launches directly back into OpenCore, which will save its boot entry automatically from there.

<h6>Add this to the EFI partition of any other drive.  (Internal if you can!)  Any time you get locked out of your OpenCore build and your UEFI Bios does

<h5>The script references the filesystem where OpenCore lives on my system, but it will be necessary to adjust the filesystem in the startup.nsh file to reflect the local machine. I already recognized in the root directory's readme file that I'm a lazy hack.
