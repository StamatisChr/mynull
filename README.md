# README.md

This repository contains terraform code 

## Prerequisites 

- Have terraform 1.x.x installed.
- Copy of this code

## How to use the code?

### Get the code

Option 1. 
Clone the github repository:
```
git clone git@github.com:StamatisChr/mynull.git
```


Change directory:
```
cd mynull
```


Option 2. 
Download the code via `master.zip`
```
curl -o mynull.zip -L https://github.com/StamatisChr/mynull/archive/refs/heads/main.zip
unzip mynull.zip
```


Change directory:
```
cd mynull-main
```

### download the providers

Run:
```
terraform init
```

### run the code

Run:
```
terraform apply
```

Review the output values.

### destroy

Run:
```
terraform destroy
```


