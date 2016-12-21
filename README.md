# JP DevOps
## setup for Provisioning and Configuring Servers

This repository providing instructions to Provision and configure webserver in  Amazon AWS. 

## Instructions on getting started
a. To get started, you need to sign up with [Amazon AWS] (https://aws.amazon.com/premiumsupport/signup) .

b. you need to get the Access and Secret token for AWS. The instructions to download these tokens can be found [here](http://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_temp.html).

c. You need to set these tokens as environment variables. The names of the environment variables are - 
```
AWS_ACCESS_KEY
AWS_SECRET_KEY
```

d. Next for AWS you need to generate a key-pair, security group and .pem file . 

##Steps to follow in order to provision the VM's

a. Clone this repository into your local system.

b. Run the following script to install the dependencies:
```
bash InstallDeps.sh
```
e. In order to provision the VM's simply run the script:
```
bash ProvisionServers.sh
```

f. Go to the management consoles and verify that the VM's have been provisioned.

##Installing http via ansible
```
bash InstallWebserver.sh
```
"# redis" 
