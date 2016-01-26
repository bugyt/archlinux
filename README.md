# ArchLinux 2016.01.01
## Clean and minimal Arch Linux x86_64 base box with libvirt provider

#### Release Info
* Version 1.0.0
* Current ArchLinux Release: 2016.01.01
* Included Kernel: 4.3.3
* Box Size: 667 MB
* Details
  * Base package
  * Base devel package
  * Grub
  * Pacman package manager
  * OpenSSH
  * vagrant user with [Insecure Keypair](https://github.com/mitchellh/vagrant/tree/master/keys)
  * Password-less Sudo

#### Requirements
* [QEMU-KVM](https://en.wikibooks.org/wiki/QEMU/Installing_QEMU)
* [Vagrant](https://www.vagrantup.com/downloads.html)
* [Vagrant Libvirt Plugin](https://github.com/pradels/vagrant-libvirt#installation)

#### Installation
    vagrant init bugyt/archlinux
    vagrant up --provider libvirt
<br />

#### Issues and feature requests
Use this github repository for bug reports or  feature requests :
[https://github.com/bugyt/archlinux/issues](https://github.com/bugyt/archlinux/issues)
