# Provisioning EXSi

Project with examples on how to provision vms with vagrant to a EXSi hypervisor.

## Prerequisites

1. Vagrant 2.2.6
2. Vagrant plugins:
   2.1. vagrant-vmware-esxi
   2.2. vagrant-winrm-syncedfolders
   2.3. vagrant-reload
3. OVF 4.2.0

## Installation

1. Vagrant

   ```bash
   curl -O https://releases.hashicorp.com/vagrant/2.2.6/vagrant_2.2.6_x86_64.deb
   sudo apt install ./vagrant_2.2.6_x86_64.deb
   vagrant --version
   ```

2. Vagrant plugins

   ```bash
   vagrant plugin install vagrant-vmware-esxi
   vagrant plugin install vagrant-winrm-syncedfolders
   vagrant plugin install vagrant-reload
   ```

3. OVF
   Download product from [link](https://my.vmware.com/group/vmware/details?downloadGroup=OVFTOOL420&productId=614)

   ```bash
   sh VMware-ovftool-4.2.0-5965791-lin.x86_64.bundle
   ```

## Usage

Most of the configuration options is detailed in the Vagrantfile.

For any doubts regarding configuration go to exsi plugin wiki [here](https://github.com/josenk/vagrant-vmware-esxi/wiki).
