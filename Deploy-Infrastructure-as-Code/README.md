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
http://udagr-webap-oe3086mk3nbq-174419873.us-east-1.elb.amazonaws.com/