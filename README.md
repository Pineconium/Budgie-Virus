# The *Budgie* Virus
A little WIN3.1 virus I made with VBScript.

The Budgie Virus is meant for Windows 16-bit operating systems (pre-9x)

It currently only works in Windows 3.1, the only version I tested.


## Stuff you need.
--Before running--
1. Both the `BUDGIE.EXE` and `VBRUN100.DLL` files on your computer.
2. Any software capable of making floppy disk image (.IMG) files (like `cat` for example)

--For VMs--
1. A virtual machine running Windows 3.1 (or similar 16bit versions) -- *VirtualBox is used on this tutorial but other VMs should work*
2. That is it.

--For real hardware (DON'T RECOMMEND!)--
1. A computer or laptop running Windows 3.1 (or similar 16bit versions) -- *This will be the victim*
2. A blank floppy disk (with at least 1MB of free space)
3. A .img burning software (such as RawWrite)
4. A Floppy disk writer/reader on both computers (if you don't have one on your main computer, you can just buy a USB one)

## Payload (SPOILERS!)
Budgie.exe is a basic VBS-based virus made with the Virtual Basic app on Windows 3.1. It basically gets rid of everything in the `C:\WINDOWS\` directory (excluding the \system\ folder)
