# Security Groups

## Overview 
* Security groups are basically a virtual firewall which allows traffic to or from instances based on a set of rules

* Example: Locking down port 22 to disable SSH into your instances

* External traffic is disabled by default and is enabled through rules in the security groups

* Can't deny anything through a security group, can only allow.  No conflicts can exist between multiple security groups


## Notes 
* Any rule applied to a security group takes effect immediately

* Rules are stateful, so if you have HTTP allowed inbound, then outbound HTTP is added automatically, regardless of the current outbound rules

* Default security group allows all traffic on all ports within the security group

* Can have multiple security groups applied to an EC2 instance