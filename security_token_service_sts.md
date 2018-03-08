# Security Token Service (STS)

### Grants users limited and temporary access to AWS resources

* Federation (typically Active Directory)
  * Uses Security Assertion Markup Language (SAML)
  * Grants temporary access based off the users Active Directory credentials.  Does not need to be a users in IAM
  * Single sign on allows users to log in to AWS console without assigning IAM credentials
* Federation with Mobile Apps
  * Use Facebook/Amazon/Google or other OpenID providers to log in 
* Cross Account Access
  * Lets users from one AWS account access resources in another