# aws-elb-autoscaling
Auto Scaling VM-Series firewalls in AWS

This repository provides AWS CloudFormation Templates (CFT) and related Lambda functions to enable auto scaling of VM-Series next generation firewalls in AWS. They use AWS elastic load balancing (ELB) services such as classic ELB, ALB and NLB to provide elastic, on-demand, scale out of security to match increased demand for the applications protected by VM-Series. It uses a common design pattern of a load balancer sandwich to protect Internet-facing applications. VM-Series provides visibility and protection of the inbound traffic. This allows network and security administrators to use the same automation tools and Panorama to centrally manage their security in the cloud, as their on-premises environments. Review the support policy section of each folder to understand how to get help. 

## History
### Version 1.0 - Mar 2017
### Version 2.0 - Jan 2018
### Version 2.0.1 - bug fixes
### Version 2.1 - Community supported aka best-effort release
* Support for separating the frontend firewall VPC from the backend application VPC using AWS PrivateLink or VPC peering
* Support for specific combinations of external and internal load balancing

The initial release of version 2.1 is provided as a community supported, i.e. best effort, release. You can consider this as an open beta to introduce new features and collect feedback for improving the generally available release that will be officially supported.