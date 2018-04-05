# Security Groups

## Overview

* Security groups are basically a virtual firewall which allows traffic to or from instances based on a set of rules

* Example: Locking down port 22 to disable SSH into your instances

* All inbound traffic is disabled by default and is enabled through rules in the security groups

* All outbound traffic is allowed

* Can't deny anything through a security group, can only allow.  No conflicts can exist between multiple security groups

* Cannot block specific IP addresses using security groups, instead use Network Access Control Lists

## Notes 

* Any rule applied to a security group takes effect immediately

* Rules are STATEFUL, so if you have HTTP allowed inbound, then outbound HTTP is allowed automatically, regardless of the current outbound rules

* Default security group allows all traffic on all ports within the security group

* Can have multiple security groups applied to an EC2 instance

* Can have any number of EC2 instances within a security group