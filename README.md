# terr_everything
IAC networking via Terraform

Project goal: 
Support [Proxmox](https://registry.terraform.io/providers/Telmate/proxmox/latest/docs), [vSphere](https://registry.terraform.io/providers/hashicorp/vsphere/latest/docs), and [VirtualBox](https://registry.terraform.io/providers/terra-farm/virtualbox/latest/docs)

Used in combination with https://github.com/rylagek/pack_everything, users should be able to simply create virtual networks in their desired provider using [Packer](https://www.packer.io/) for machine creation and [Terraform](https://www.terraform.io/) for Networking
