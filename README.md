### Project Title - Deploy a high-availability web app using CloudFormation
This project demonstrates the deployment of web servers for a highly available web app using CloudFormation (Infrastructure as Code). Writing the code that creates and deploys the infrastructure and application for an Instagram-like app from the ground up. This includes deploying the networking components, followed by servers, security roles and software.  I also design a architecture diagram  as a visual aid to understand the CloudFormation script.

This folder contains the CloudFormation codes for the "ND9991 - C2- Infrastructure as Code - Deploy a high-availability web app using CloudFormation" project. The folder contains the following files:

#### [Web App Architecture Diagram for Udagram on AWS](Web-App-Architecture-Diagram-for-Udagram-on-AWS.jpeg)
Infrastructure diagram and Web Architecture Diagram 
![Diagram of CI/CD Pipeline we will be building.](Web-App-Architecture-Diagram-for-Udagram-on-AWS.jpeg)

#### [tpc-udagram-network.yml](tpc-udagram-network.yml)
Deploys the network infrastructure.

#### [tpc-udagram-network-params.json](tpc-udagram-network-params.json)
Parameters for the network infrastructure

In YAML code, the `${EnvironmentName}` would be substituted with `UdacityUdagramProject` accordingly.

#### [tpc-udagram-server.yml](tpc-udagram-server.yml)
Deploys the web servers

#### [tpc-udagram-server-params.json](tpc-udagram-server-params.json)
Parameters for the web servers

#### [create.sh](create.sh)
Helper script to create the CloudFormation stack

#### [update.sh](update.sh)
Helper script to update the CloudFormation stack


#### [delete.sh](delete.sh)
Helper script to delete the CloudFormation stack
