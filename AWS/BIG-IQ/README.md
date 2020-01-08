# AWS DO Declarations via BIG-IQ

## Description

These declarations are for use within my AWS VPC, via the BIG-IQ instances that are currently deployed in that VPC.  Variable substitution is expected to be handled upstream before reaching BIG-IQ (e.g. Postman, Terraform, etc.)

| Filename | Description |
| -------- | ----------- |
| biq-ltm-x-cluster | These declatations will configure and license a pair of BIG-IPs for LTM/AVR and setup device clustering |
| biq-ltm-standalone | This declaration will configure and license a standalone BIG-IP for LTM/AVR use |
