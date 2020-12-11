# ELK-Project-Demo
Cybersecurity Bootcamp ELK Stack Demonstration

# Background & Purpose #
The ELK demonstartion was created to 

# Scope #
This ELK project was deployed in an Azure Cloud environment. This ELK stack monitored Filebeats and Metricbeats for a DVWA application on the virtual network.

# Implementation #

## Virtual Network Creation ##

1. Create a virtual network with a network IP range 10.0.00/16
2. Create a default subnet with an IP range 10.0.0.0/32

## Establish a Network Security Group ##

Immediately created a netowrk security group that by default blocked all traffic to protect the environment as it was being built out. The NSG is subsequently modified to allow specific traffic as the infrastructure is built out.