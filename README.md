# The *Budgie* Virus
A little WIN3.1 virus I made with VBScript.

The Budgie Virus is meant for Windows 16-bit operating systems (ore-9x)

It only works in Windows 3.1 as that's the only WIN version I tested.


## Stuff you need.
-- For Windows 3.1 --
1. Make use you have the "VBRUN100.dll" file with the OS. (DLL NOT INCLUDED!)
--For VMs--
1. A virtual machine running Windows 3.1 (or similar 16bit versions) -- *VirtualBox is recommended*
2. The Budgie.img file is installed.

--For real hardware (DON'T RECOMMEND!)--
1. A computer or laptop running Windows 3.1 (or similar 16bit versions) -- *This will be the victim*
2. A blank floppy disk (with 1MB of free space)
3. A .img burning software (such as RawWrite)
4. USB Floppy disk writer/reader

## Payload (SPOILERS!)
Budgie.exe is a basic VBS-based virus made with the Virtual Basic app on Windows 3.1. It basically gets rid of everything in the `C:\WINDOWS\` directory (excluding the \system\ folder)
