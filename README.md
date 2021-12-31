# plymouth-theme-mashup-tech
a simple animated theme for plymouth bootsplash


## sample:


https://user-images.githubusercontent.com/54219098/147488391-9e165e95-c90a-4f40-9b58-1a5f291bed57.mp4


## installation

### Fedora

1. clone the repository to your local machine
2. Place the "mashup-tech" folder in /usr/share/plymouth/themes
3. run `plymouth-set-default-theme mashup-tech -R` The "-R" parameter regenerates the initrd image.
4. reboot and watch the magic happen

### Ubuntu

1. clone the repository to your local machine
2. Place the "mashup-tech" fol`der in /usr/share/plymouth/themes
3. Set it as default theme via `sudo update-alternatives --install /usr/share/plymouth/themes/default.plymouth default.plymouth /usr/share/plymouth/themes/mashup-tech/mashup-tech.plymouth 100`
4. Run `sudo update-alternatives --config default.plymouth` and select the theme
5. Run `sudo update-initramfs -u` to regenerate initramfs
6. reboot and watch the magic happen

#### Credits 

The images for the encryption password input field come from the hot-dog theme. Capslock image is a modified version from [spinner](https://github.com/freedesktop/plymouth/blob/master/themes/spinner/capslock.png)

The main logo as well as the animations are made by myself from a few free-to-use vector graphics. 
