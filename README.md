# vagrant-debian-box
provides a basic debian jessie base box for vagrant

## Requirements

 * Oracle VM VirtualBox
 * Vagrant
 * mkisofs
 * 7zip

## Usage

Just call 

	./build.sh 

to build a debian vagrant base box and type

	vagrant box add "debian-jessie" debian-jessie-64.box

to add it as a vagrant box with name debian-jessie.


### Notes

This script is based on Dotzero's [repo](https://github.com/dotzero/vagrant-debian-wheezy-64) with some tweaks.
