# OS

Kernel project using Rust following the tutorial by Philipp Oppermann, can be found in the following [link](https://os.phil-opp.com/multiboot-kernel/)

Downloaded
binutils-2.31.90.tar.xz

* `sudo mv ~/Downloads/binutils-2.31.90.tar.xz /usr/local/build-binutils`
* `sudo tar -vxf /usr/local/build-binutils/binutils-2.31.90.tar.xz`

After running the configuring found in his tutorial in the following page [link] I was able to access it at the following:
~/opt/cross/x86_64-elf/bin/ , I refer to this directly to not get messed up with the one that comes with Mac

Installing grub was a bit more tricky but the following worked for me
Cloned repo git clone git clone git://git.savannah.gnu.org/grub.git  
Installed the following tools

* `brew install autoconf automake libtool`
* `brew install gcc`
* `brew install nasm`

If you run into gettext problems
* ` brew install gettext`
* `brew link --force gettext`

I also installed the following brew install autoconf-archive
* `brew install pkg-config`


After having all the above I went into the cloned repo grub folder and was able to follow the steps in the following page without any issues. [Link.](https://wiki.osdev.org/GRUB_2#Installing_GRUB_2_on_OS_X)
