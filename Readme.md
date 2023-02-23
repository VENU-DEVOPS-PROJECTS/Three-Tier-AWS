Building a 3-Tier Architecture in AWS

Steps :
1: Create the VPC
2: Create and attach the Internet Gateway
3: Create Public Subnets
4: Create the NAT gateway
5: Configure route tables
6: Build the web tier
--> Create Launch templates
--> Create Autoscaling group
7: Build the App tier
--> Create Launch templates
--> Create Autoscaling group
-------------------------------------------------------> Ansible code developed till here to deploy VPC,Subnets,NAT GW,IGW,Route Tables.
8: Build the Database
9: Testing the environment

Full documenatation here : https://medium.com/aws-in-plain-english/build-a-3-tier-architecture-via-aws-bcdce5909e52
