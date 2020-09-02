# -terraform-providers-proxmox
step 1  install terraform providers
git clone https://github.com/nopnop334/terraform-providers-proxmox.git
cd terraform-providers-proxmox
mv terraform* /usr/local/bin
chmod 755 /usr/local/bin/terraform*
step 2 test init terraform
git clone https://github.com/nopnop334/test-terraform-init.git
cd test-terraform-init
terraform init
