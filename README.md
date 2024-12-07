# KDE-Wallpapers Archive
An archive of old kde wallpapers
Currently includes ikde4 kdeartwork-wallpapers
## Install
cp subfolders to /usr/share/wallpapers for systemwide installation
cp subfolders to ~/.local/share/wallpapers for user-only installation

or use
### CMake

	mkdir build
	cd build
	cmake ../ -DCMAKE_INSTALL_PREFIX=/usr
	
	sudo make install


### Packages

I provide packages for opensuse tumbleweed and archlinux

#### Opensuse Tumbleweed
- Add the repo with

        sudo zypper ar https://download.opensuse.org/repositories/home:/MartinF99/openSUSE_Tumbleweed/ martinf99_home

- install the package 

    sudo zypper in plasma-classic-wallpapers

#### Archlinux

    plasma-classic-wallpapers is available via the aur
