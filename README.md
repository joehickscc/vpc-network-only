vpc-network-only
======================


## Description
This [CloudCoreo](http://www.cloudcoreo.com) repository will bring up a solid vpc for you to start with. It is across 3 datacenters with a public and private subnet in each. No resources will be launched that cost money.


## Hierarchy
![composite inheritance hierarchy](https://raw.githubusercontent.com/CloudCoreo/vpc-network-only/master/images/hierarchy.png "composite inheritance hierarchy")



## Required variables with no default

**None**


## Required variables with default

### `VPC_NAME`:
  * description: the name of the VPC
  * default: test-vpc


### `VPC_OCTETS`:
  * description: the /16 net of the VPC to look for - i.e 10.11.0.0
  * default: 10.11.0.0


### `REGION`:
  * description: use default except for multiple region use cases
  * default: PLAN::region

### `PRIVATE_ROUTE_NAME`:
  * description: the name to give to the private route
  * default: test-private-route


### `PRIVATE_SUBNET_NAME`:
  * description: the cloudcoreo name of the private vpc subnets
  * default: test-private-subnet


### `PUBLIC_ROUTE_NAME`:
  * description: the name to give to the public route
  * default: test-public-route


### `PUBLIC_SUBNET_NAME`:
  * description: the cloudcoreo name of the public vpc subnets
  * default: test-public-subnet



## Optional variables with default

### `VPC_TAGS`:
  * description: tags to apply to the vpc
  * default: 


## Optional variables with no default

### `SUFFIX`:
  * description: when used will use the value to suffix the names of all converged objects

## Tags
1. Network
1. VPC

## Categories
1. Network



## Diagram
![alt text](https://raw.githubusercontent.com/CloudCoreo/vpc-network-only/master/images/diagram.png "Public and Private nets across 3 subnets")


## Icon
![icon](https://raw.githubusercontent.com/CloudCoreo/vpc-network-only/master/images/icon.png "icon")


