command:$ terraform plan -out tfplan -var "pemfile=YOURPEMFILE" $ terraform apply -auto-approve tfplan $ terraform destroy

steps:
clone the repo
copy your respective pem file to the local repo
run terraform
