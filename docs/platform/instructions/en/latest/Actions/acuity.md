---
title: Acuity

permalink: platform/instructions/en/latest/Actions/acuity

---

<base target="_blank">
<container>

**Overview**

Connect your Acuity Scheduling account with the Kore.ai XO Platform to streamline appointment scheduling and automation. The platform integrates with Acuity using Basic Auth, allowing you to pre-authorize the connection or enable end users to authenticate during conversations.

</container>

<container>

**Authorization**
 
To connect to a Acuity account, Kore.ai uses Basic Auth. The developer can use pre-authorized credentials during the configuration process or let the end user authorize during the conversation by creating an authorization profile. 
 
 
 |Authorization Type                      | Basic |
 |----------------------------------------|-------|
 |Pre-authorize the Integration           |  Yes  |
 |Allow Users to Authorize the Integration|  Yes  |


**Pre-authorize the Integration**
 
To make the integration process smoother for customers, you can pre-authorize it by providing the necessary authorization credentials to obtain the access token.

**Basic**
 
1. Provide API key and API secret to authorize the integration.  
2. Follow the steps below to get the required credentials from your Acuity dashboard.
 
      i. Login to your Acuity account at Acuity Scheduling.  https://acuityscheduling.com/
      
     ii. Navigate to the "Go To Scheduling" section, find the "Integrations" tab, and go to the "API" section.
     
    iii. Copy the API key and User ID from the "API" section into Kore.ai XO Platform.
     
     iv. Click Enable.

 
**Allow Users to Authorize the Integration**
 
This method requires the end user to provide credentials during the conversation for authorization.
 
**Basic**
 
1. Select All Users to Authorize the Integration.
 
2. Click Select Authorization.
 
3. Select Create New.
 
4. Select the type of authorization mechanism. 
 
   i. Select Basic Auth
  
   ii. Provide a name for the Authorization Profile
 
5. Save Authorization Profile.
 
6. Select the created Authorization Profile to complete integration.
 
7. Click Enable.

</container>
