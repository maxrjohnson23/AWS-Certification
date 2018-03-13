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
  
## Key Terms
**Federation**: Combining or joining a list of users in one domain (such as IAM) with a list of
users in another domain (such as Active Directory, Facebook, etc.)

**Identity Broker**: A service that allows you to take an identity from point A
and join it (federate it) to point B

**Identity Store**: Services like Active Directory, Facebook, Google, etc.

**Identities**: A user of a service like Facebook, etc.

## Scenarios
**Scenario 1 - Credential Based**
1. Develop an identity broker to communicate with LDAP and AWS STS

2. Identity Broker always authenticates with LDAP first, then with AWS STS

3. Application then gets temporary access to AWS resources

**Scenario 2 - Role Based**
1. Develop an identity broker to communicate with LDAP and AWS STS

2. Identity Broker always authenticates with LDAP first, gets an IAM Role associated with the user

3. Application then authenticates with STS and assumes that IAM role

4. Application uses that IAM role to interact with S3
