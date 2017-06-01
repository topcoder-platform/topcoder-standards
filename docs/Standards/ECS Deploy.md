## ECS Deploy Standard

Standards for Deploying ECS Applications on AWS

### Overview

Where possible, software deployments to AWS should use ECS (over EBS or stand alone servers). Rationalle:

* Scaling
* Load Balancing
* Full control over resources created (especially as comparred to EBS)
    * This prevents new, unneeded resources from being created on AWS

### Deployment Strategy

The AWS environment and VPC are setup in advance to accomidate EC2 deployments. This means the following resources are already in place and do not need to be created when a new application is deployed:

* Network Subnets
* Security Groups
* Load balancers

The following resoures will be automatically created for each new application deployed to ECS:

* An Autoscaling Group
* A Launch Configuration
* ECS Resources
    * A Cluster
    * A Repository
    * A Task Definition
    * A Service


### Production Deployments on AWS East
dsds

### Thing 2
sasasa

### Thing 2
sasasa

### Thing 2
sasasa

### Thing 2
sasasa