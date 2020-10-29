# AWSCloudformation
Contains Templates for Cloudformation

EC2withSecurityGroup contains a template separated into 4 parts for creating a EC2 instance.
a. Parameters: Include what are the runtime parameters like type of instance, Key Value pair and an IP address to SSH into the EC2 instance.
b. Mappings: Key and associated value to decide the type of hardware, region the EC2 instance will be created in.
c. Resources: This is mandatory section that includes the EC2 resources properties. In this template it is instance type, instance security group and region.
d. Outputs: Values returned when we view our stack properties through AWS CLI, in this template we return the instance ID, availability zone, Public IP and Public DNS.
