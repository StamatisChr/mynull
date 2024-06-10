# README.md

This repository contains terraform code that does not create resources and can be used for tests with VCS provider on Terraform Cloud or Terraform Enterprise. To achieve that is using the terratform null provider and terraform random provider
https://registry.terraform.io/providers/hashicorp/null/latest/docs


https://registry.terraform.io/providers/hashicorp/random/latest/docs

## Prerequisites 

- Have terraform 1.x.x installed.
- Have git installed and configured.

## How to use the code?

Clone the github repository:
```
git clone git@github.com:StamatisChr/mynull.git
```

Change directory:
```
cd mynull
```

Run:
```
terraform init
```

Run:
```
terraform apply -auto-approve
```

Review the output values.



