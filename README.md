### Members: Keziah Wacnang, Austin Park

**To generate ssh key pair:**
* `ssh-keygen -t ed25519 -f ~/.ssh/aws -C "Lab07"`

**Using the `import_lab_key` script for AWS**
* `./import_lab_key ~/.ssh/aws.pub`

**To run the included terraform**
* go to the `terraform` directory first
* `terraform init` - to initialize the directory
* `terraform validate` - to check validity of config
* `terraform plan` - to do a dry run
* `terraform apply` - to run and build your instances


**Resources:**
* https://docs.ansible.com/ansible/latest/collections/ansible/builtin/package_module.html
* 