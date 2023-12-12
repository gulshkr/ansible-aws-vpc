# ansible-aws-vpc

# What are the problems
Complete Infrastructure setup is complex
Not repeatable
Difficult to track
Chance of human error
Managing manually is time consuming task


# What are the solutions
Configuration Management of infrastructure
Automatic setup (NO human errors)
Centralize change management
Version Control [IAAC]
Repeatable
Resuable


# Steps:
Setup VPC[Secure & HA]
Provision Ec2 Instances, ELB, Sec Grp etc
Provision VPROFILE STack on EC2 Instances
Build artifact
MYSQL
Memcache
RabbitMQ
Tomcat
Nginx

1st execution - image in the previous report - vpc stack setup
//Pull the code 
//Execute the playbook  
//Setup the stack


2nd execution - instances and load balancer setup

3rd execution - pre profile stack provisioning
Nginx server
Tomcat server
Rabbit mq
Memcache server
Mysql setup



# Flow of execution 
Login to AWS
Create ec2 instance to run ansible playbook
Install ansible
Install boto
Setup ec2 role for ansible
Fetch source code from project ansible for aws
Execute vpc playbook
Playbook to launch ec2 elb sec grp for vprofile
Get into vprofile vpc
Playbooks for vprofile stack setup






# Need any help please mention me or ping me on github.
