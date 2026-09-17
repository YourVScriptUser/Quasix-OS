# Quasix
OS Source for the VSK-32 in x32 Assembly

To compile, navigate to the VSK-32 root folder

Run this command, and fill in the paths.

```
py vsk32env.py WriteVMDisk
py Assembler/image.py [path-to-QUASIX] -o [path-to-vmdisk]
py ssfs.py ls "C:/python/VSK-32/Storage/Disk/vmdisk.img"
```

vmdisk is located inside `/VSK-32/Storage/Disk/vmdisk.img`

And then run the emulator >>> `py Emulator.py`
