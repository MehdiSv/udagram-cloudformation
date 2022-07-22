# Udagram - Deploy a high-availability web app using CloudFormation
This folder contains the following files:


### udagram-servers.yml and udagram-servers.json
CloudFormation code using YAML describing the servers. EC2 + LoadBalancer + Listener + Listener Rule + Autoscaling group + LaunchConfig.
Also includes the EC2 IAM role.

### udagram-network.yml and udagram-network.json
CloudFormation code using YAML describing the network. VPC + Subnets (Private and public) + NAT gateway + Routes.

### create.sh and update.sh
Two bash scripts to launch the aws cloudformation create and update stack cli commands.

## Website URL:
http://udagr-webap-xe5dhlv7fzqm-614673600.us-west-2.elb.amazonaws.com/
