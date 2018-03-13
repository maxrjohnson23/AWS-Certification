## Scenario - External Active Directory Federation

User is not on the company network and requires credentials to access AWS S3

**Active Directory first, then you receive temporary credential**
1. User browses to the FQDN for the external-facing ADFS server (SSO)

2. Sign in to Active Directory environment

3. Receive SAML Assertion (Secure Assertive Markup Language) - browser cookie

4. Browser points to AWS SAML sign-on site to request temporary credentials

5. Creates AWS console sign on page to log in