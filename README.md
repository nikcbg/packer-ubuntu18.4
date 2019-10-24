# packer-ubuntu18.4

A packer project that creates ubuntu18.4 Vagrant base box for VirtualBox provider.

## Prerequisites

* Install [packer](https://www.packer.io/downloads.html).
* Install [vagrant](https://www.vagrantup.com/downloads.html).

## Building the box with Packer

The packer template is in `template.json`. In the `variables` section you can set parameters to customize the build. Help on setting, overriding variables in `packer` can be found [here](https://www.packer.io/docs/templates/user-variables.html#setting-variables).

- Run `packer validate template.json` - to make basic template validation.

- Run `packer build template.json` - to build the Vagrant box with packer.


## Uploading to Vagrant cloud

- Fllow [this](https://www.vagrantup.com/docs/vagrant-cloud/boxes/create.html) on how to upload your newly created box to Vagrant Cloud 
