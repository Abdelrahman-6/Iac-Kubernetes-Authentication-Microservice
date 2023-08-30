# CD12352 - Infrastructure as Code Project Solution
# [Abdelrahman Nafea]

## Spin up instructions
Use the create-stack.sh script to create the network stack then the application stack as shown below.
./create-stack.sh udagraminfra network.yml network-parameters.json
./create-stack.sh udagramservers udagram.yml udagram-parameters.json

## Tear down instructions
Use the delete-stack.sh script to delete stacks as shown below
./delete-stack.sh udagraminfra
./delete-stack.sh udagramservers

## URL CHECK
http://udacity-project-udagram-s3-abdelrahman.s3-website-us-east-1.amazonaws.com/index
http://udagr-WebAp-13A4AYASXTU6C-347986745.us-east-1.elb.amazonaws.com
