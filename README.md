# grub-custom-simona

Compile an alternative list of the usable kernels of the grub boot menu indicating the kernel relase, obtained from the output of the 'file' command, instead of the file name.

Put grub-custom into /etc/default and 11_linux_simona into /etc/grub.d with +x execute flag.

Aur Pkg grub-hook (https://aur.archlinux.org/packages/grub-hook/) can be conveniently used together with my package in order to be sure that at the end of every kernel update the grub start list will also be updated.
