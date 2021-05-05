---
title: Add users and assign roles in RapidStart Services
TOCTitle: Add users and assign roles in RapidStart Services
ms:assetid: 9b8f8491-022f-434d-a359-3a57ec392139
ms:mtpsurl: https://technet.microsoft.com/library/Dn194004(v=AX.60)
ms:contentKeyID: 52348263
author: Khairunj
ms.author: daxcpft
ms.date: 09/18/2015
mtps_version: v=AX.60
f1_keywords:
- add RapidStart users
- assign RapidStart roles
- RapidStart role assignment
- RapidStart user enrollment
- RapidStart user sign-up
---

# Add users and assign roles in RapidStart Services 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Beginning October 1, 2015, RapidStart services will no longer be supported. For more information, see the announcement on CustomerSourcehttps://mbs.microsoft.com/partnersource/northamerica/news-events/news/RapidStartServicesDiscontinued or PartnerSourcehttps://mbs.microsoft.com/customersource/northamerica/news-events/news-events/news/RapidStartServicesDiscontinued.

This topic explains how to add users in your organization to an implementation of Microsoft Dynamics ERP RapidStart Services and select a role for each user. Depending on the roles that you assign to them, users can perform various tasks, including the following:

  - Create and manage configuration projects in RapidStart Services

  - Copy templates and functional areas from other tenants in RapidStart Services

  - Answer configuration questions about your installation of Microsoft Dynamics AX 2012

  - Design custom questions to add to the configuration questions that are provided by Microsoft


> [!NOTE]
> <P>Only users who are assigned the role of Customer administrator can add users and and assign roles in RapidStart Services.</P>



After you receive an email message from dynamicsonline@microsoft.com that confirms that online services for Microsoft Dynamics ERP have been activated for you, use this procedure to add users and assign roles.

1.  In the email message that you receive from dynamicsonline@microsoft.com, click the activation link to go to the online services website.

2.  Click **Sign In**, and then sign in by using your Microsoft account. Be sure to use the Microsoft account that you gave to the partner so that the partner could sign you up for RapidStart Services.

3.  Review the terms of service agreement and the privacy statement, and then click **Activate**.

4.  On the **Dashboard** page in Customer Portal, in the navigation pane on the left, click **User Management**.

5.  On the **User Management** page, on the **Action Pane**, in the **New** group, click **User**.

6.  On the **Add New User** page, enter the user’s name, the email address that the user uses to sign in to his or her Microsoft account, and the contact email address for the user. The email address for the user’s Microsoft account can differ from the user’s contact email address.

7.  Select one of the following roles for the user:
    
      - **Administrator** – Allow the user to perform all tasks in RapidStart Services, such as assigning permissions to other users, creating configuration projects, designing new questions, answering questions, viewing reports, and connecting to and loading configuration data into a Microsoft Dynamics ERP implementation.
    
      - **Designer** – Allow the user to create new templates, functional areas, question groups, and questions to support custom solutions that are added to Microsoft Dynamics AX.
    
      - **Configurator** – Allow the user to create and manage RapidStart Services and answer configuration questions.
    
      - **Viewer** – Allow a user who is a RapidStart Services Configurator or Designer to copy functional areas and templates from another organization. The Viewer role must be assigned to a user in addition to their role as a Designer or Configurator. A Viewer role assignment by itself does not provide a user with RapidStart Services access.
    
    Click **Save**.

8.  On the **User management** page, select the user that you created, and then, on the **Action Pane**, click **Send Invitation**.

The user receives an email message that contains a link that they must click in order to activate their account. After the user clicks the link, the user must sign in to RapidStart Services by using the Microsoft account that you entered in step 6.

## See also

[Learn about the end-to-end provisioning process in RapidStart Services](learn-about-the-end-to-end-provisioning-process-in-rapidstart-services.md)

[Try out Microsoft Dynamics ERP RapidStart Services](try-out-microsoft-dynamics-erp-rapidstart-services.md)

[Activate your Partner Portal account for Microsoft Dynamics ERP RapidStart Services](activate-your-partner-portal-account-for-microsoft-dynamics-erp-rapidstart-services.md)

[Add a Customer administrator to a service in RapidStart Services](add-a-customer-administrator-to-a-service-in-rapidstart-services.md)

  


