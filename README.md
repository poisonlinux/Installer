# Installer
Custom Installer Slackware
Located at usr/lib/setup/

Archived present in: isolinux/initrd.gz
For open initrd.gz use:
```
mkdir INITRD && cd INITRD && xz -dc <../initrd.img | cpio --quiet -i --make-directories
```
