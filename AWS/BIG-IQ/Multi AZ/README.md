# AWS DO Declarations via BIG-IQ

## Description

These declarations are for use within my AWS VPC, via the BIG-IQ instances that are currently deployed in that VPC.  Variable substitution is expected to be handled upstream before reaching BIG-IQ (e.g. Postman, Terraform, etc.)

| Filename | Description |
| -------- | ----------- |
| biq-gslb-x-standalone | This is for a standalone GSLB deployment |
| biq-ltm-x-east-cluster | These declatations will configure and license a pair of BIG-IPs for LTM/AVR and setup device clustering in the east availability zone |
| biq-ltm-x-west-cluster |These declatations will configure and license a pair of BIG-IPs for LTM/AVR and setup device clustering in the west availability zone |
