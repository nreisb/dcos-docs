---
post_title: Install DC/OS using Terraform
nav_title: Terraform
menu_order: 60
---

One way to install DC/OS is to automate the [Advanced Installer](/docs/1.10/installing/advanced-installer/) with [Terraform](https://www.terraform.io/).

Here are a few Terraform projects to get you started:


| Environment | Node Type | Project | Support Level | Docs |
|--------------------|--------------|-------------------|---------|---------------|
| AWS/Azure | Virtual | [bernadinm/terraform-dcos](https://github.com/bernadinm/terraform-dcos) | Community | N/A |
| AWS | Virtual | [zutherb/terraform-dcos](https://github.com/zutherb/terraform-dcos) | Community | N/A |
| AWS | Virtual | [dcos-up](https://github.com/kensuio/dcos-up) | Community | N/A |
| DigitalOcean | Virtual | [digitalocean-dcos-terraform](https://github.com/jmarhee/digitalocean-dcos-terraform) | Community | [docs](/docs/1.10/installing/terraform/digitalocean/) |
| Packet | Physical | [packet-terraform](https://github.com/dcos/packet-terraform) | Community | [docs](/docs/1.10/installing/terraform/packet/) |


## Further reading

Looking to install into other environments? Checkout the [full list of install methods](/docs/1.10/installing/).