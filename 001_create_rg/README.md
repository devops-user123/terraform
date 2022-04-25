# Folder
001_create_rg

# Introduction
This is the first terraform script to create RESOUCE GROUP

# Folder Structure
    tf_main -> 
        main.tf -> which has main terraform scripts
    README.md -> is containing all the help

# Pre-requisites
1. Need to have Azure Service Prinicipal -> With Contributor Role assigned
2. Set below environment variables
    ARM_TENANT_ID
    ARM_SUBSCRIPTION_ID
    ARM_CLIENT_ID
    ARM_CLIENT_SECRET    

# Terraform Commmands
- Run all the terraform commands from tf_main folder.
- No need to import/reference. With in the folder, Terraform understands and reads all the .tf files

``` 
Terraform Init
Terraform Validate
Terraform Plan
Terraform Apply
Terraform Destroy
``` 

