# 4640-w9-lab-start-w25

## Generate Key + Upload ##
First generate an ssh key to upload and use:
```ssh-keygen -t ed25519 -f <key/name>```

Run the script provided passing the .pub keyname as an arguement, which will upload the key to the AWS account associated with the AWS CLI that is set up. 

## Packer ##
CD into the packer directory and use the ```packer init .``` command.
Optionally check the validity of the files with ```packer validate .```
Build the file using ```packer build .```

## Terraform ## 
CD into the terraform directory and use the ```terraform init``` command to initialize the directory.
Optionally validate files with ```terraform validate``` command.
Apply changes with ```terraform apply``` command.
Terraform will prompt to confirm the changes. 
After using the provided infastructure, clean up with the ```terraform destroy``` command. 
