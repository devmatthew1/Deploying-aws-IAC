# AWS CLOUD FORMATION SCRIPTS
This repository contains scripts that to create, update and deletes infrastructures on aws 
*create an s3 bucket with the name : "surelay-page"

# HOW TO RUN THE SCRIPT
*Get the IAM secret key for cloudformation from aws

-To create network infrastructures run : 

./create.sh surelay-udp2 network-infra.yml network-parameters.json

-To create servers run

./create.sh surelay-ups2-servers server-infra.yml server-parameters.json

# HOW TO TEST

here is the url for testing

http://surel-webap-1cd1cpht2m6s8-1067091405.us-west-2.elb.amazonaws.com/


aws --version
aws configure

use us-west-2
aws s3 ls
