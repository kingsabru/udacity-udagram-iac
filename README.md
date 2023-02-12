# Udacity Udagram IAC
This project contains the solutions to Udacity Cloud DevOps **Project 2: Deploying a High availability web app using CloudFormation**

## App Public URL
http://udagr-webse-16z8yitoxjbxu-1057925370.us-east-1.elb.amazonaws.com/

## Usage
You can run the codedeploy scripts in two easy steps:
```bash
# Ensure that the AWS CLI is configured before runniing the command below
# Create the network infrastructure
# Check the region in the create.sh file
# Replace profile name or use default name
./create.sh udagramStack udagram.yml udagram-parameters.json my-profile-name
# Create servers
# Change the AMI ID and key-pair name in the servers.yml
# Check the region in the update.sh file
# Replace profile name or use default name
./update.sh udagramStack udagram.yml udagram-parameters.json my-profile-name
```