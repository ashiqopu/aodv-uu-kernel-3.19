# Download

source: https://kernel.ubuntu.com/~kernel-ppa/mainline/v3.19.8-ckt23/

linux-headers-3.19.8-031908ckt23_3.19.8-031908ckt23.201607121433_all.deb
linux-headers-3.19.8-031908ckt23-generic_3.19.8-031908ckt23.201607121433_amd64.deb
linux-image-3.19.8-031908ckt23-generic_3.19.8-031908ckt23.201607121433_amd64.deb

	>> sudo apt-get install module-init-tools

# Install

	>> sudo dpkg -i *.deb

# Load

- reboot and press shift key  to load grub
- choose advanced options for ubuntu
- select generic kernel 3.19

# Install old GCC (4.8) and symlink
	>> sudo apt install gcc-4.8 g++-4.8

	>> sudo ln -s /usr/bin/gcc-4.8 /usr/bin/gcc
	>> sudo ln -s /usr/bin/g++-4.8 /usr/bin/g++
