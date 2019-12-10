## Module Bastion Host
### Usage
The usage of the module could be like this in your own main.tf file:
```
module "bastion-host" {
  source = ""

  project_id    = "<PROJECT ID>"
  instance_name = "<INSTANCE NAME>"
  zone          = "<ZONE>"
  subnetwork    = "<SUBNETWORK>"

}
```
