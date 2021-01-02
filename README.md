# mitbos

A simple operating system project to learn how an operating system implemented from scratch.


* To generate boot sector use nasm assambler
```
nasm boot_sect.asm -f bin -o boot_sect.bin
```

* To run qemu emulator with generated boot sector
```
qemu-system-x86_64 -drive file=boot_sect.bin,format=raw
```
