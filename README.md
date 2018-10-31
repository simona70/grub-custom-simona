# grub-custom-simona
Fork of grub to detect revision's kernel
Must be loaded into /etc/grub.d
And have execute +x flag in file system

It read kernel version in "file kernel" attribute instead of search it in name file (arch linux has not version in name file (for security I suppose?)

grub-custom is for /etc/default while 11_linux_simona is for /etc(grub.d
