*create an s3 bucket with the name : "surelay-page"

*how to run it ?

  you can run this command :
  
    ./create.sh surelay-udp2 network-infra.yml network-parameters.json
    ./create.sh surelay-ups2-servers server-infra.yml server-parameters.json

*how to test 

here is the url for testing

http://surel-webap-1cd1cpht2m6s8-1067091405.us-west-2.elb.amazonaws.com/


aws --version
aws configure

use us-west-2
aws s3 ls
