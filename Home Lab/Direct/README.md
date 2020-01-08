# Lab Declarations direct to BIG-IP

## Description

These declarations are for use within my vSphere lab, directly to the BIG-IP instances that are currently deployed in that lab.  Variable substitution is expected to be handled upstream before reaching BIG-IQ (e.g. Postman, Terraform, etc.)

| Filename | Description |
| -------- | ----------- |
| gslb-standalone | This declaration will configure and license a standalone BIG-IP for LTM/DNS/AVR use |
| ltm-cluster-x | These declatations will configure and license a pair of BIG-IPs for LTM/AVR and setup device clustering |
| ltm-standalone | This declaration will configure and license a standalone BIG-IP for LTM/AVR use |