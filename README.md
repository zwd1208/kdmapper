https://www.unknowncheats.me/forum/anti-cheat-bypass/320049-kdmapper-manual-map-driver-using-vulnerable-driver-intel.html

So, this driver (iqvw64e.sys) comes as part of Intel LAN drivers and it allows to copy, read and write user/kernel memory, map physical memory and perform virtual to physical address translation.
For code execution: I used a method described here (Executing shellcode)

Your driver must be compiled with /GS- option, and have custom driver entry point defined. (Basically the same kind of driver that you would use with drvmap or any other driver manual mapper)
