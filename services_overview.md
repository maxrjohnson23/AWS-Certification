## Compute
* EC2 - VMS
* EC2 Container - Docker containers at scale
* Elastic Beanstalk - Upload code only, handles infrastructure automatically
* Lambda - Upload code to the cloud and control execution, don't need to manage underlying machines
* Lightsail - VPS service, allocated machines with fixed IP
* Batch - Batch computing in the cloud

## Storage ##
* S3 - Buckets for object storage
* EFS - Elastic Files system - networked file storage
* Glacier - data archival
* Snowball - bring large amounts of data into AWS datacenter
* Storage Gateway - VMS that replicate information to S3

## Databases ##
* RDS - Relational Database Service (MySQL, Postgres, etc)
* DynamoDB - Non-relational Databases
* Elasticache - Caching level for DB 
* Red Shift - Data warehousing and complex queries for BI

## Migration ##
* AWS Migration Hub - Track application migration process
* Application Discovery Service - Detects applications and dependencies
* Database Migration Service - Easy way to migrate from on-prem to AWS
* Server Migration Service - Migrate virtual and physical servers
* Snowball - Between storage and migration for large data sets

## Networking / CDN ##
* VPC - Virtual private cloud, all networking aspects
* CloudFront - Amazon's CDN, media delivery
* Route53 - DNS Service
* API Gateway - Create APIs for services
* Direct Connect - Running dedicated line from office/datacenter to VPC

## Developer Tools ##
* CodeStar - Project management, release toolchain between developers
* CodeCommit - Source control for private git repos
* CodeBuild - Compile, test, package
* CodeDeploy - Automated deployment to EC2, Lambda, or on-prem
* CodePipeline - Orchestrate and continous delivery
* XRay - Debug and analyze serverless applications
* Cloud9 - Web IDE

## Management Tools ##
* CloudWatch - Monitoring services, sys admin
* CloudFormation - Solutions architect, scripting infrastructure based on code
* CloudTrail - Auditing for AWS console and logging changes
* Config - Monitors entire config for AWS
* OpsWorks - Similar to Elastic Beanstalk, automate environment config with Chef and Puppet
* Service Catalog - Manage catalog of IT services approved for use.  Large organizations
* Systems Manager - Managing AWS/EC2 resources.  Patching many instances, etc.
* Trusted Advisor - Security advice and AWS service usage/saving
* Managed Services - AWS can manage for you

## Media Services ##
* Elastic Transcoder - Video transcoding, resizing, etc
* MediaConvert - File based transcoding for broadcast
* MediaLive - live processing of video streams
* MediaPackage -  Protect videos for delivery
* MediaStore - Storage optimized for media
* MediaTailor - Targeted ads in video streams

## Machine Learning ##
* SageMaker - Deep learning/neural networks for developers
* Comprehend - Sentiment analysis around data
* DeepLens - AI camera on the physical camera
* Lex - Powers Alexa service, AI chatting
* Machine Learning - Normal machine learning based on data analysis
* Polly - Text to speech
* Rekognition - File analysis for images, text, video, etc.
* Amazon Translate - Machine translation for different languages
* Transcribe - Transcribe to closed captions from speech recognition

## Analytics ##
* Athena - Analytics across S3 data using SQL
* EMR - Elastic Map Reduce, processing large amounts of data
* CloudSearch - Service services for AWS
* ElasticSearch Service - Search service
* Kinesis - Ingesting large amounts of data into AWS, social media feeds, etc
* QuickSight - Business intelligence toolchain
* Data Pipeline - Moving data between AWS services
* Glue - ETL, migrating large amounts of data

## Security/Identity ##
* IAM - Identity Access Management
* Cognito - Device authentication, mobile apps, etc.  Temporary AWS Access
* GuardDuty - Monitor for malicious access on your account
* Inspector - Check for security vulnerabilites on your EC2 instances
* Macie - Scan S3 buckets for PII (names, addresses, etc.)
* Certificate Manager - SSL certs for free w/ domain registration
* CloudHSM - Hardware security module, dedicated key storage Hardware
* Directory Service - Integrate MS Active Directory
* WAF - Web application firewall, sql injection, XSS prevention
* Shield - DDoS Mitigation, expanded by Advance Shield for support team, won't charge for billing
* Artifact - Audit and compliance reports

## Mobile ##
* Mobile Hub - Management console for applications, cloud config file, SDK for mobile
* Pinpoint - Targeted push notifications for engagement (local restaurant, etc)
* AWS AppSync - Update data in web and mobile in real-time, offline updates
* Device Farm - Testing apps on a variety of live devices
* Mobile Analytics - analytic service for mobile applications

## AR/VR ##
* Sumerian - General release name for VR platform, common set of tools to create environments.  Build 3d rooms without code

## Application Integration ##
* Step Functions - managing lambda functions and coordination
* Amazon MQ - Messaging queues
* SNS - Notification service (billing, etc.)
* SQS - Service queues, decoupling infrastructure, polling queues
* SWF - Simple workflow service, job tracking and workflow management, Amazon uses it for package lifecycle

## Customer Engagement ##
* Connect - Contact center as a service
* Simple Email Service - Sending high volumes of emails

## Business Productivity ##
* Alex for Business - Use it for business tasks (dial-in, reordering supplies, etc)
* Chime - Video conferencing (zoom, hangouts)
* Work Docs - Dropbox for AWS, store and secure documents
* WorkMail - Similar to Office365, Gmail

## Desktop and App Streaming ##
* Workspaces - VDI Solution
* AppStream 2.0 - Streaming applications running in the cloud, similar to Citrix

## IoT ##
* IoT - Devices and sensor information
* IoT Device Management - managing devices at scale
* Amazon FreeRTOS - Realtime operating system for microcontrollers
* Greengrass - Run local compute, data caching, messaging, for devices

## Game Development ##
* GameLift - Service to develop games and VR





