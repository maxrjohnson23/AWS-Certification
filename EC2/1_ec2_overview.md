# EC2 - Elastic Compute Cloud

## What is EC2?

* Amazon Elastic Compute Cloud (EC2) is a web service that provides resizable compute capacity in the cloud.

* Amazon EC2 reduces the time required to obtain and boot new server instances to minutes, allowing you to quickly scale capacity, both up and down, as your computing requirements change.

## EC2 Options

* On Demand - allow you to pay a fixed rate by the hour (or second) with no commitment

* Reserved instances - provide you with capacity reservation, and offer a significant discount on the hourly charge for an instance - 1 year or 3 year terms

* Spot - enable you to bid whatever price you want for instance capacity, providing for even greater savings if your applications have flexible start and end times

* Dedicated Hosts - Physical EC2 server dedicated for your use.  Dedicated Hosts can help you reduce costs by allowing you to use your existing server-bound software licenses.  

## Use Cases

* On Demand
  * Users that want the low cost and flexibility of Amazon EC2 without any up-front payment or long-term commitment
  * Applications with short term, spiky, or unpredictable workloads that cannot be interrupted
  * Applications being developed or tested on EC2 for the first time

* Reserved 
  * Applications with steady state or predictable usage
  * Applications that require reserved capacity
  * Users able to make upfront payment to reduce their total computing costs even further
    * Standard Reserved Instances (RI) - Up to 75% off on demand
    * Convertible RI's (Up to 54% off on demand) - Capability to change the attributes of the RI as long as the exchange results in the creation of RI's of equal or greater value
    * Scheduled RI's available to launch within the time windows you reserver.  This options allows you to match your capacity reservation to a predictable recurring schedule that only require a fraction of a day, week, or a month.

* Spot
  * Applications that have flexible start and end times
  * Applications that are only feasible at very low compute prices
  * Users with urgent computing needs or a large amount of additional capacity

* Dedicated Hosts
  * Useful for regulatory requirement that may not support multi-tenant virtualization
  * Great for licensing which does not support multi-tenancy or cloud deployments
  * Can be purchased On-Demand (hourly)
  * Can be purchased as a Reservation for up to 70% off the On-Demand price
  