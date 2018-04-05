# Key Exam Points

* Termination protection is turned off by default, you must turn it on

* On an EBS-backed instance, the default action is for the root EBS volume to be deleted when the instance is terminated

* EBS Root Volumes of your DEFAULT AMI's cannot be encrypted.  You can also use a third party tool (such as bit locker, etc) to encrypt the root volume, or this can be done when creating AMI's in the AWS console or using the API

* Additional volumes can be encrypted