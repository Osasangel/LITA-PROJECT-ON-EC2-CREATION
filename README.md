# LITA PROJECT ON EC2 CREATION
 Develop a solution that meets SmartShop's requirements by leveraging AWS services such as EC2,  Virtual Private Cloud (VPC), and Identity and Access Management (IAM).
## Project work flow
### Create a GITHUB
create a new repository in the GITHUB to show my documentation workflow.
### Create a Security Group
A Security Group names OsasMonebi_Lita was created to allow SSH and HTTP traffic. it has 2 inbound rules and 1 outbound rule count.
Below is the image of my Security Group created.
![SGP](/SGP.png)
### Create a Key Pair
A unique Key pair named OsasMonebi_LitaKP was generated and this keypair helps maintain dat consistency by preventing duplicate records
Below is the image of my Keypair created
![Keypair](/KeyPair.png)
### Generate an EC2  Instances
An EC2 Instances with the name OsasMonebi_Lita with two subnets a public subnet with IPV4 Address 52.206.172.62 and a Private subnet of IPV4 address 10.0.8.247
Below is the image of my EC2 created
![Instance](/Instance.png)
### Run the SSH Client 
The SSH Client connect to the created Instances by running a command to ensure that my Key is not Publicly Viewable
Below is the image of the SSH Client  
![SSH Client](/Client.png)
### Create the Apache Web Server
Below is the image of the Apache Web Server 
![AWebs](/AWebs.png)
## In Conclusion
A  solution that meets SmartShop's requirements by leveraging AWS services such as EC2,  Virtual Private Cloud (VPC), and Identity and Access Management (IAM) has been created
Thank you
