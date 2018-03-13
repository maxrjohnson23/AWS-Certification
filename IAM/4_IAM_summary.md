## IAM Summary
* IAM consists of the following
  * Users
  * Groups - a way to group our users and apply policies to them collectively
  * Roles
  * Policy Documents - JSON format of key/value pairs
* IAM is universal - does not apply to a specific region
* Root account is the account created when first setting up the AWS account.  It has complete admin access
* New users have NO permissions by default
* New users are assigned an Access Key & Secret Access Key when first created
  * These are not the same as a password, as you cannot log into the AWS console using them
  * These can be used to access AWS via the command line or APIs
  * Only view these once
* Always set up MFA on the root account
* Can create and customize password character and rotation policies