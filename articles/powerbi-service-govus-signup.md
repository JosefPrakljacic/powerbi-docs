﻿<properties
   pageTitle="Sign Up for Power BI for United States Government customers"
   description="For U.S. Government customers, learn how to sign up your US Government organization for the Power BI US Government service"
   services="powerbi"
   documentationCenter=""
   authors="davidiseminger"
   manager="mblythe"
   backup=""
   editor=""
   tags=""
   qualityFocus="no"
   qualityDate=""/>

<tags
   ms.service="powerbi"
   ms.devlang="NA"
   ms.topic="article"
   ms.tgt_pltfrm="NA"
   ms.workload="powerbi"
   ms.date="01/31/2017"
   ms.author="davidi"/>

# Enroll your US Government organization in the Power BI service

The **Power BI service** has a version available for United States Government customers as part of the **Office 365 US Government Community** subscriptions. The **Power BI service** version discussed in this article is specifically designed for US Government customers, and is separate and different from the commercial version of the **Power BI service**.

For more information about the **Power BI service** for US Government, including its features and limitations, check out [Power BI for United States Government customers - Overview](powerbi-service-govus-overview.md).

> **Note:** This article is intended for administrators who have authority to sign up their US Government organization for Power BI. If you are an end-user, contact your administrator about getting a subscription to Power BI for US Government.

![](media/powerbi-service-govus-signup/service_govus_signup_1.png)

## Select the right sign-up process for your US Government organization

Your US Government organization might be new to the **Office Government Cloud**, or might already have a subscription. The following sections detail the sign-up steps based on where you are with the Office Government Cloud and Power BI, and are different based on your existing subscription. 

Once you have signed up for Power BI US Government some features may not work until your sales or support representative completes your onboarding process. To find out about these features see the [Power BI for United States Government customers - Overview](powerbi-service-govus-overview.md). To complete the onboarding process to enable these features, contact your sales or support representative.


### US Government organizations that are new Office Cloud customers

If your organization is a new **Office Government Cloud** customer, follow these steps:

> **Note:** These steps should be performed by the portal administrator.

1.  Go to [https://products.office.com/en-us/government/office-365-web-services-for-government](https://products.office.com/en-us/government/office-365-web-services-for-government). Note: if you don't want to sign up for Office Government Cloud at this time, please reach out to your sales representative. 

2.  Select Office G3 and complete the form for an Office trial

3.  Once you are an Office Cloud customer continue on with the steps below for "Existing Office Government Cloud customers"

### Existing Office Government Cloud customers

If your organization is an existing **Office Government Cloud** customer, but you don't have a **Power BI** subscription (Free or otherwise), follow these steps:

> **Note:** These steps should be performed by the portal administrator.

1.  Log in to your existing Office Government Cloud account and go to the admin portal

2.  Select **Billing**.

3.  Select **Purchase Service**.

4.  Select the Power BI Pro Government Option and choose between **Try** and **Buy Now**

5.  Complete your order

6.  Assign users to the account.

    ![](media/powerbi-service-govus-signup/service_govus_signup_5.png)

7. Log in to the **Power BI service** for US Government customers at [https://app.powerbigov.us](https://app.powerbigov.us)

## Additional Signup Information
The below is additional information for signing up for Power BI US Government in various licensing migration cases.

### Direct Power BI Trial to Pro Customer Onboarding
-  Click and follow through the Billing\Purchase Service\PowerBI Pro Gov and select purchase and not Trial
-  Fill in the necessary and get the licenses
-  Remove the PowerBI Pro Trial or remove the old licenses and Assign the new ones to the users
-  Login to https://app.powerbigov.us

### Reseller Power BI Trial to Pro Customer Onboarding
-  Go to Billing\Subscriptions and click on Power BI Pro for Government subscription. There you will see:
   -  Available
   -  Assigned
   -  Assign to users links
-  If you still have the Trial assigned:
   -  Click on Assigned under the Trial subscription and remove the users you want to add to paid
   -  Go to the Paid subscription and assign those users

### “Whitelisting” Instructions
“Whitelisting” is a process that the Power BI engineering team uses to move customers from the commercial cloud environment into the secure, Government cloud environment. This ensures that a number of features available in the US Government cloud, [described below](#gaps-solved-by-whitelisting), work as expected.

As mentioned in the documentation [here](powerbi-service-govus-overview.md), customers who are migrating from Power BI Free to Power BI Pro will encounter the [below gaps](#gaps-solved-by-whitelisting) until their tenant is “whitelisted” by the Power BI engineering team. The following scenarios explain this.

If the tenant has Power BI Free in their tenancy, both the Free and Gov Pro licenses can co-exist, but one or the other client will need to be broken. If the tenant is added to the “whitelist”, then any user currently using Free will no longer be able to login to PowerBI using the Desktop Client and will experience the below gaps. All the clients (Gateway/Desktop/Mobile) will work as expected for the Pro customers.

To get “whitelisted”, fill out the intake form [here](http://www.surveygizmo.com/s3/3289410/ca030551f535). Once complete the Power BI team will include the your domain information into their payload. ETA for completion is 2-3 weeks from submission.

### Mixed Power BI Free to Pro Customer Onboarding
In the case where a customer has users leveraging the Power BI ‘free’ SKU and then purchases Pro licenses for some but not all of their users. 

Before “whitelisting” 
-  The 500 ‘free’ users running in commercial can continue to run as is. 
-  The 100 Power BI Pro Gov licenses will show up in the portal and the administrator can assign them to users. The assigned users can then leverage Power BI Pro, understanding that the [gaps solved by “whitelisting”](#gaps-solved-by-whitelisting) will exist until they are “whitelisted”. The Pro user will not lose data from their ‘free’ license once the admin assigns them the Pro license. 

After “whitelisting” 
-  The 500 ‘free’ users running in commercial can continue to run, but the client app will stop authenticating as expected. 
-  The 100 Pro users running in government are good to go and all tools function as expected. 
 
Identifying users running Power BI 'free' 
-  To identify users running Power BI ‘free’ within a tenant, admins can run the licensing report and ‘free’ users will show up for “Power BI Standard” 

### Gaps solved by “whitelisting”
-  Gateway, Mobile, and Desktop can’t authenticate
-  You cannot access Azure commercial data sources
-  PBIX files must be manually uploaded from commercial
-  Power BI mobile apps are not available


## More Information

﻿There are all sorts of things you can do with Power BI. For more information and learning, including an article that shows you how to sign up for the service, check out the following resources:

-   [Overview of Power BI for US Government](powerbi-service-govus-overview.md)

-   [Guided Learning for Power BI](powerbi-learning-0-0-what-is-power-bi/.md)

-   [Get started with the Power BI service](powerbi-service-get-started.md)

-   [Getting started with Power BI Desktop](powerbi-desktop-getting-started.md)