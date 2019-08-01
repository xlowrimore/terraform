# Terraforming Jenkins
This project will launch a single server t2.micro EC2 instance with Amazon Linux AMI, update it's kernal, install java, install and start Jenkins.

# AWS CLI Setup
1. https://docs.aws.amazon.com/cli/latest/userguide/install-windows.html


2. Open PowerShell


3. Type AWS Configure


4. Set Access_Key & Secrect_Key from your AWS user


5. In (LINE 3) shared_credentials_file, add: **/Users/"youruserprofile"**   to    ./aws/credentials"


6. Done


###### Files you need to replace
key_name = "your AWS keyname"


place init.tpl file in your Terraform directory 
