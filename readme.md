# Sample infrastructure for AWS VPN Client

## Description

This CloudFormation template create VPC with two subnets without internet gateway

One subnet contains EC2 and secound is attached to VPC Client Endpoint

VPC Client Endpoint is using mutual authentication so there is need Certificate for server and client side in AWS Certificate Manager 