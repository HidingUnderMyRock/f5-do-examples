# AWS DO Declarations via BIG-IQ

## Description

*These are a work in progress, and are currently identical to the same AZ declarations*

These declarations are for use within my AWS VPC, via the BIG-IQ instances that are currently deployed in that VPC.  Variable substitution is expected to be handled upstream before reaching BIG-IQ (e.g. Postman, Terraform, etc.)

| Filename | Description |
| -------- | ----------- |
| biq-ltm-x-cluster | These declatations will configure and license a pair of BIG-IPs for LTM/AVR and setup device clustering |
