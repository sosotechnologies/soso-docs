# Welcome to Sosotech Docs

This is the front page of Sosotech Docs.

## Terraform module structure

ready modules
 s3, ec2 

 Im using the development environment in this path --> /sosoweekly/week02/client/module-client/development to call my main module folders found in /sosoweekly/week02/modules
 
 ready modules
 s3, ec2 

 Im using the development environment in this path --> /sosoweekly/week02/client/module-client/development to call my main module folders found in /sosoweekly/week02/modules

week02 

       ├── modules
       │
       │   └── ec2
       │
       │       ├── main.tf

       │       ├── output.tf
       │       └── variables.tf
       ├── client
       └── module-client
                    └── staging       
                    └── production
                    └── test
                    └── development
                                    └── ec2-module-code
                                                  ├── main.tf
                                                  ├── output.tf
                                                  └── variables.tf
                                    └── ...
          
=> Call the module (EX: ec2) using this PATH: source = "../../../../modules/ec2"