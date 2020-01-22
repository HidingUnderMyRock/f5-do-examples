# AWS DO Declarations via BIG-IQ

## Description

These declarations are for use within my AWS VPC, via the BIG-IQ instances that are currently deployed in that VPC.  Variable substitution is expected to be handled upstream before reaching BIG-IQ (e.g. Postman, Terraform, etc.)

| Filename/Directory | Description |
| -------- | ----------- |
| Different AZ | These declarations will be used when the BIG-IPs are deployed in different availability zones |
| Same AZ | These declarations will be used when the BIG-IPs are deplyed in the same availability zone |
| biq-ltm-standalone | This is for a standalone BIG-IP deployment |
