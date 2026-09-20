# Quasix
OS Source for the VSK-32 in x32 Assembly

To compile, navigate to the VSK-32 root folder
Rename `fiex` to `.fiex` and move it to `\Quasix\com`. It wont compile without this file.

Run this command, and fill in the paths.

```
py vsk32env.py WriteVMDisk
py Assembler/image.py [path-to-QUASIX] -o [path-to-vmdisk]
```

vmdisk is located inside `/VSK-32/Storage/Disk/vmdisk.img`

And then run the emulator >>> `py Emulator.py`
