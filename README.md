Nico's Terraform scripts.


You will need to download provider.tf, vars.tf and terraform.tfvars file.

I have uploaded a working template for Windows and for Linux. 


If you're new to Terraform:

<!-- wp:paragraph -->
<p>On Mac, the easies thing would be to:</p>
<!-- /wp:paragraph -->

<!-- wp:list -->
<ul><li>Install brew : <a href="https://brew.sh/">https://brew.sh/</a>  </li><li>Install Terraform using brew : <strong>brew install terraform</strong></li></ul>
<!-- /wp:list -->

<!-- wp:paragraph -->
<p>On Windows or other platforms, you can always download it from Hashicorp: <a href="https://www.terraform.io/downloads.html">https://www.terraform.io/downloads.html</a></p>
<!-- /wp:paragraph -->

<!-- wp:list -->
<ul><li>Download the files from the repo/li><li>Update the files with the right variables (cluster, resource pool, template, network, passwords, etc... )</li><li>Run the following commands (make sure Terraform is in the PATH or if not, that the files are in the same place as your Terraform exe if you're using Windows):<ul><li>terraform init</li><li>terraform plan </li><li>terraform apply</li><li>[terraform destroy]</li></ul></li><li>And that's it!</li></ul>
<!-- /wp:list -->
