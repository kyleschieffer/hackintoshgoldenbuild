# Bootloader Recovery</b>
<h4>Easily boot right back into your system when you lose boot priority.

<h6>If you reset your NVRAM or sometimes with OS updates, the system is unable to find OpenCore and boot into it, and then you have to navigate to the Bootstrap.efi file from a UEFI shell and manually reactivate it (and before I knew how to do this, I was literally resetting the CMOS by physically removing the battery to recover my boot options!)  This bootloader automatically launches a shell with a startup script aimed directly back into OpenCore, which will automatically reset to boot automatically from there.<br>

<h6>Add this to the EFI partition of any other drive.  Make a recovery stick, or internal is a great idea if you have an extra blank EFI partition.  I have never accidentally found internal drives in the laundry!  Any time you get locked out of your OpenCore build and your UEFI Bios doesn't see OpenCore, boot onto that drive.<br>

<h6>The script is hacky and manually references the filesystem where the OpenCore EFI partition lives on my personal system, so it will be necessary to adjust the filesystem in the startup.nsh file to reflect the local machine.  It's not terribly elegant, but much better than having to dismantle the machine, replace the CMOS battery and start from scratch when your boot entries disappear.
