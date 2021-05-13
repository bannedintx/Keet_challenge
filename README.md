# Keet_challenge
Keet Health code challenge
Based on the instructions I have completed the following: 
  defined the AWS provider
  Provisioned the ec2 instance
  Installed Docker
  Ran the nginx imgae
  Configured the output for the internal IP address
  
Aside from the basic instructions I have included extra configurations that would be recommened to ensure reliability: 
  Defined the VPC
  Configured a container repository that would be required to store Docker
  The addition of IAM roles were configured to grant access from the ec2 to the container repository
  Configuration of ec2 security groups to allow ports 80,443, and 22
  
