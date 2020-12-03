# Exercises for CloudFormation

# Sample01.yaml
Create an EBS volume.
# Sample02.yaml
Creates a sample website, with an ELB and Autoscaling Group.  Please see History for step-by-step comments.
# Sample03.yaml
Creates a VPC with 2 Public & 2 Private subnets, 1 Internet GW for public subnets, each private subnet will have 1 Nat GW each in public subnet w/in same AZ, security group with no ingress.
https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-ec2-vpc.html
# Sample04.yaml
Sample template nesting Sample01 and passing parameters.
# Sample05.yaml
Sample template for Windows server, ability to choose installed Roles & Features... WIP, need to complete 'AllowedPattern'
https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/cfn-windows-stacks-bootstrapping.html
# Sample06.yaml
Sample template for nesting Sample03 & Sample05.  Sample05 will use VPC Outputs to create Windows Server in new public subnet
# Sample07.yaml 
Sample template for creating Windows EC2 and changing admin user to use a password stored in Secrets Manager.
# Sample08.yaml
Sample template for creating DMS Components (Replication Instance, Endpoints, Tasks)
