This folder is one of the kernel image installation folders. Each installed
kernel image shall have a folder with a name of the format:
	zambesii<bits>-<version>-<custom-name>/

Inside of this folder, the kernel image, memorydisk and symbol map shall be
found, with the names:
	zambesii.zxe (image).
	zambesii.__ksm (kernel symbol map file).
	zambesii.memdisk (kernel memorydisk).

Furthermore, the kernel headers, which are used for the purpose of installing
new distributaries shall be found here, in a folder called "headers", and an
accompanying folder shall be found here, with the name "distributaries", which
shall hold all installed distributaries, /already linked/ against the kernel
symbol map.

