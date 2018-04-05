# EBS Volumes and EC2

## Summary

* Volumes exist on EBS as a virtual hard disk

* Snapshots
  * Stored in S3
  * Point in time copy of the volume
  * Snapshots are incremental - only changes are saved
  * Can take snapshots while instance is running, but you should stop the instance first if it is a root device

* There are several types of EBS volumes that can be mounted on an EC2 instance

* Can take snapshots and create new images based on backups

* Can create AMIs both from volumes and snapshots

* EBS volumes and EC2 instances must be located in the same availability zone to be mounted

* EBS volumes (except magnetic) can be upgraded on the fly, including changing size and storage type, without having to stop the EC2 instance

* To move volumes to other availability zones you can create additional volumes and images from snapshots and copy them other regions/availability zones

