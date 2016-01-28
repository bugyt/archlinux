# ArchLinux 2016.01.01 [Box Version 1.0.1]
## Clean and minimal Arch Linux x86_64 base box with libvirt or virtualbox provider


#### Github repository for bug reports or  feature requests
[https://github.com/bugyt/archlinux/](https://github.com/bugyt/archlinux/)

#### Release Info
* Current ArchLinux Release: 2016.01.01
* Included Kernel: 4.3.3
* Details
  * Virtual Hard Disk Capacity 20GB, Dynamically allocated
  * Base package
  * Base devel package
  * Grub
  * Pacman package manager
  * OpenSSH
  * Users and passwords
     * root / vagrant
     * vagrant / vagrant (Public Key authentication with [Insecure Keypair](https://github.com/mitchellh/vagrant/tree/master/keys), password-less sudo)
  * VirtualBox Guest Additions (for Virtualbox version)
  * __Network File System (NFS)__
  * __rsync__
  * __bash-completion__
  * __bash customizations__

#### Virtualbox 
##### Requirements
* [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
* [Vagrant](https://www.vagrantup.com/downloads.html)


##### Getting started

Install and connect to the box :

      $ mkdir archbox
      $ cd archbox
      $ vagrant init bugyt/archlinux
      $ vagrant up --provider virtualbox
      $ vagrant ssh
<br />

#### libvirt (QEMU-KVM)
##### Requirements
* [QEMU-KVM](https://en.wikibooks.org/wiki/QEMU/Installing_QEMU)
* [Vagrant](https://www.vagrantup.com/downloads.html)
* [Vagrant Libvirt Plugin](https://github.com/pradels/vagrant-libvirt#installation)

##### Getting started

Install and connect to the box :

      $ mkdir archbox
      $ cd archbox
      $ vagrant init bugyt/archlinux
      $ vagrant up --provider libvirt
      $ vagrant ssh
<br />
