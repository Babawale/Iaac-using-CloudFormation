### Project Title - Deploy a high-availability web app using CloudFormation
This folder contains the CloudFormation codes for the "ND9991 - C2- Infrastructure as Code - Deploy a high-availability web app using CloudFormation" project. The folder contains the following files:

#### README.md
This README file that descibes the contents of the folder

#### "Udagram Infra Diagram.jpeg"
Infrastructure diagram

#### udagraminfra.yml
This YAML file contains the code for the network infrastructure

#### udagraminfra-params.json
This JSON file contains the chosen infrastructure Parameters for increasing the generic nature of the YAML code. For example, the JSON file contains a "ParameterKey" as "EnvironmentName" and "ParameterValue" as "UdacityUdagramProject". 

In YAML code, the `${EnvironmentName}` would be substituted with `UdacityUdagramProject` accordingly.

#### udagramservers.yml
This YAML file contains the deployment code for the servers

#### udagramservers-params.json
This contains the parameters for the deployment of servers

#### create.sh
Shell script to easily create the CloudFormation stack

#### update.sh
Shell script to easily update the CloudFormation stack
