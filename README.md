# Couchbase on the AWS Cloud
> Couchbase Server Enterprise Edition version 5.0
> Couchbase Sync Gateway Enterprise Edition version  1.4.1-3

## Deployment Options
AWS Quick Start Team

This Quick Start reference deployment guide includes architectural considerations and configuration steps for deploying a Couchbase cluster on the Amazon Web Services (AWS) cloud. It discusses best practices for deploying Couchbase on AWS using services such as Amazon Elastic Compute Cloud (Amazon EC2) and Amazon Virtual Private Cloud (Amazon VPC). It also provides links to automated AWS CloudFormation templates that you can leverage for your deployment or launch directly into your AWS account.

The guide is for IT infrastructure architects, administrators, and DevOps professionals who are planning to implement or extend their Couchbase workloads on the AWS cloud.

The following links are for your convenience. Before you launch the Quick Start, please review the architecture, configuration, network security, and other considerations discussed in this guide.

## Architecture Design
Deployment Guide: PDF https://s3-us-west-2.amazonaws.com/cs-couchbase-quickstart/Couchbase+Quick+Start+Guide.pdf Word https://s3-us-west-2.amazonaws.com/cs-couchbase-quickstart/Couchbase+Quick+Start+Guide.docx
![Quick Start Couchbase Design Architecture](https://s3-us-west-2.amazonaws.com/cs-couchbase-quickstart/Couchbase-architecture-design.png)

## Change Log
### October 2017
* Added new documentation with architecture design 
* Moved couchbase to private subnet
* Added bastion submodule
* Added "EBS encryption" parameter to default yes
* Updated AMIs to marketplace listings
* Add m4 and r4 instance types
* Forced HTTPS only for 18901
* Added dynamic AMI population
* Create options to use BYOL, Hourly and none
