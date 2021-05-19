# terraform

#VMware vSphere　リポジトリ  
*https://registry.terraform.io/providers/hashicorp/vsphere/latest

#実行方法  
*terraform init  
*terraform plan -var 'vsphere_user=administrator@vsphere.local' -var 'vsphere_password=xxxx' -var 'vsphere_server=172.20.15.11'  
*terraform apply -var 'vsphere_user=administrator@vsphere.local' -var 'vsphere_password=xxxx' -var 'vsphere_server=172.20.15.11'  
