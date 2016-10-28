vpc-network-only
======================

## Description
This [CloudCoreo](http://www.cloudcoreo.com) repository will bring up a solid vpc for you to start with. It is across 3 datacenters with a public and private subnet in each. No resources will be launched that cost money.

## Tags
1. Network
1. VPC

## Categories

1. Network

<h3>OVERRIDE OPTIONAL VARIABLES</h3>
* <b>VPC_NAME:</b>
  * required: true
  * description: this is the name of your vpc as defined by your [CloudCoreo](http://www.cloudcoreo.com) setup
  * default: test-vpc
* <b>PRIVATE_SUBNET_NAME:</b>
  * required: true
  * description: the [CloudCoreo](http://www.cloudcoreo.com) name of the private vpc subnets
  * default: test-private-subnet
* <b>PRIVATE_ROUTE_NAME:</b>
  * required: true
  * description: the name to give to the private route
  * default: test-private-route
* <b>PUBLIC_SUBNET_NAME:</b>
  * required: true
  * description: the [CloudCoreo](http://www.cloudcoreo.com) name of the public vpc subnets
  * default: my-public-subnet
* <b>PUBLIC_ROUTE_NAME:</b>
  * required: true
  * description: the name to give to the public route
  * default: my-public-route

## Diagram
![alt text](https://raw.githubusercontent.com/CloudCoreo/vpc-network-only/master/images/vpc-network-only.png "Public and Private nets across 3 subnets")
