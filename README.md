### Hello!
### Welcome to README.md and LINKS Project Repository.
### Current Version of Links - GNU (Busybox) / LINKS 0.1
### Beta test is started on 6 January 2026.

### INSTRUCTIONS FOR COMPILING A LINKS 0.1:
### 1. Make Sure, you having installed packets: libisofs, libburn, readline, acl, zlib, and libisoburn
### 2. Find a "Base" folder and enter on it.
### 3. Run a ISO compiling process, with command bellow:

xorriso -as mkisofs -o links_linux-0.1.iso \
   -b isolinux/isolinux.bin -c isolinux/boot.cat \
   -no-emul-boot -boot-load-size 4 -boot-info-table \
   ./iso_root

### 4. Find a LINKS Linux ISO file. If you dont find it, make sure you installed all packets upper this text and thy again.
### 5. Enjoy The LINKS!

### Please, subscribe to our Telegram Channel: @xmecorp
### if you have questions about LINKS Project and another questions, tell it to us: @xmeco
### Copyright Xtreme MicroElectronics Corporation (XMECO). Links Project. All Rights Reserved.
