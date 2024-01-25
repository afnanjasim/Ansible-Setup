# Basic Ansible Setup 

The setup node contains 2 target machines and 1 controller.

command:$ terraform plan -out tfplan -var "pemfile=YOURPEMFILE" $ terraform apply -auto-approve tfplan $ terraform destroy

steps:
clone the repo
copy your respective pem file to the local repo
run terraform
