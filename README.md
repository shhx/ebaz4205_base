
Useful commands:

- petalinux-config --silentconfig : Configure the project without opening the GUI, you can modify the configuration by editing the project-spec/configs/config file.
- petalinux-config -c kernel : Configure the kernel.
- petalinux-build : Build the project.
- petalinux-package --boot --fsbl --fpga --u-boot : Package the project into BOOT.BIN and image.ub.
