# AWS DO Declarations via BIG-IQ

## Description

These declarations are for use within my AWS VPC, via the BIG-IQ instances that are currently deployed in that VPC.  Variable substitution is expected to be handled upstream before reaching BIG-IQ (e.g. Postman, Terraform, etc.)

| Filename/Directory | Description |
| -------- | ----------- |
| Across AZ | These declarations are used when the BIG-IP cluster is deployed across different availability zones |
| Multi AZ | These declarations are used to deploy multiple clusters and standalone BIG-IPs.  Two clusters in one availability zone, another cluster in a different availability zone, and two standalone BIG-IPs for GSLB in both availability zones. |
| Same AZ | These declarations are used when the BIG-IP cluster is deplyed in the same availability zone |
| biq-ltm-standalone | This is for a standalone BIG-IP deployment |
| biq-gslb-standalone | This is for a standalone GSLB deployment |
