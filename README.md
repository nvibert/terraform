Nico's Terraform scripts.

You need to download provider.tf, vars.tf and create a terraform.tfvars file with your own credentials in this format:

vsphere_user= "admin@acme.local"
vsphere_password= "password"
vsphere_server= "vcenter.A-B-C-D.vmwarevmc.com"

I have uploaded a working template for Windows and for Linux. 
