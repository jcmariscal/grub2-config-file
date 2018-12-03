# grub2-config-file

My grub2 custom config file for ISO booting.

## Configuration

- Move ISO files to /boot/bootiso directory
- Modify `/etc/grub.d/40_custom` as sudo and run 

```shell 
update-grub
```

- Boot into a live-cd medium. 

Currently supported:
- Kali linux
