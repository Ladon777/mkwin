mkwin
=====

mkwin is a shell script to create a Windows installation USB from ISO. It support EFI and MBR boot for Windows 7 and up.


Requirements
============

* ms-sys
* grub
* dosfstools
* ntfs3g
* dialog (optional; required if not specifying device on command line)
* sane environment (util-linux, coreutils, etc.)


Usage
=====

Run the mkwin script in your shell:

    $ sudo ./mkwin.sh <ISO file> [USB device] [NTFS label]

If device is omitted, you will be prompted to select from available removable devices.