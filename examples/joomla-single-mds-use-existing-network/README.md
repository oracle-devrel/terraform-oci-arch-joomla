## Create Joomla single-node + custom network injected into module
This is an example of how to use the oci-arch-joomla module to deploy Joomla (single-node) with MDS and network cloud infrastrucutre elements injected into the module..
  
### Using this example
Update terraform.tfvars with the required information.

### Deploy the Joomla
Initialize Terraform:
```
$ terraform init
```
View what Terraform plans do before actually doing it:
```
$ terraform plan
```
Use Terraform to Provision resources:
```
$ terraform apply
```
