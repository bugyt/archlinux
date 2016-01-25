# ArchLinux 2016.01.01
## Clean and minimal Arch Linux x86_64 base box with libvirt provider

### Requirements
<br />
* [QEMU-KVM](https://en.wikibooks.org/wiki/QEMU/Installing_QEMU)
* [Vagrant](https://www.vagrantup.com/downloads.html)
* [Vagrant Libvirt Plugin](https://github.com/pradels/vagrant-libvirt#installation)
<br />

### Installation
<br />

    vagrant init bugyt/archlinux
    vagrant up --provider libvirt
<br />

### Version 1.0.0
<br />
* Pacman package manager
* OpenSSH
* vagrant user with [Insecure Keypair](https://github.com/mitchellh/vagrant/tree/master/keys)
* Password-less Sudo
<br />

### Issues and feature requests
<br />
Use this github repository for bug reports or  feature requests :
[https://github.com/bugyt/archlinux](https://github.com/bugyt/archlinux)
<br />
