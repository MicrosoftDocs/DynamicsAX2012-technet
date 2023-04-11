---
title: Add and maintain your users
TOCTitle: Add and maintain your users
ms:assetid: 6912e764-5d73-4883-a2b5-507e944f1d7c
ms:mtpsurl: https://technet.microsoft.com/library/Hh271551(v=AX.60)
ms:contentKeyID: 36384183
author: tfehr
ms.author: daxcpft
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- user
- users
- VendProfileContactListPage
- VendUserRequestExternalAdd
- VendUserRequestExternalInactivateAdd
- VendUserRequestExternalListPage
- additions
- addition
- maintainance
audience: Application User
ms.search.region: Global
---

# Add and maintain your users 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In the Vendor portal, you can submit requests to add new users if you are the Vendor portal administrator for your organization. Vendor users are the contacts in your organization who interact with the customer by using the Vendor portal. You can modify a request and resubmit it, or delete a request, as long as the request has not been approved. You can also submit requests to delete approved users. After you submit a user request to workflow, you can view the status of the request as the customer completes the workflow tasks.

Before a user can be granted access to the Vendor portal, you must add the person as a contact in your profile. For more information about how to add a new contact, see [Maintain your contacts](maintain-your-contacts.md).

Every user of the Vendor portal must have unique credentials. For example, if you are using Windows Live ID for authentication, every user must have a unique Windows Live ID. The assignment of credentials is determined by configuration settings and how users are provisioned. For more information, see [About provisioning vendor users](about-provisioning-vendor-users.md).

When you request access for your user, you can request that the user be assigned a role of either vendor administrator or vendor. For more information about the tasks that are permitted for these vendor-specific roles, see [About user roles](about-user-roles.md).

## Add a new user

1.  Click **Contacts** on the Quick Launch.

2.  On the **Contacts** page, click the ID for the contact that you want to create a user request for, and then on the **Action Pane**, on the **Requests** tab, click **Add vendor user**.

3.  On the **Create new user request** page, select a role for the contact. The email address is used to notify the contact when the user request is approved or rejected.

4.  Select the authentication method. The method defines how the user signs into the Vendor portal.

5.  Click **Save and close**.

6.  On the **View user request** page, you can perform the following tasks:
    
      - Click **Edit** to modify the information.
    
      - Click **Close** to close without submitting the request.
    
      - Click **Submit** to send the request to the customer for approval. You can add an optional comment to the customer before you submit the request.
    
      - Click **Close** to defer submitting the request.

7.  To view the status of your user requests, click **User requests** on the Quick Launch. The status of a request changes as the request is processed:
    
      - **Draft** – The request has not been submitted for approval.
    
      - **Submitted** – The request has been submitted to workflow.
    
      - **Pending approval** – The request is in review.
    
      - **Approved** – The customer has approved the request.
    
      - **Completed** – The user request process is completed.
    
      - **Cancelled** – You have canceled the user request.
    
      - **Rejected** – The customer has declined to approve the request.

New user requests are sent for approval to the vendor account manager for the customer. If a request is approved, the vendor account manager adds the user to Microsoft Dynamics AX and the request status is set to **Completed**. The new user can then access the Vendor portal.

## Recall and resubmit a user request

If you want to modify a user request that you have submitted for approval, you can recall the request from the approval process. You can recall a user request only if the request does not have a status of **Approved** or **Completed**.

1.  Click **User requests** on the Quick Launch.

2.  On the **User requests** page, click the **Request ID** for the request that you want to resubmit, and then click **Actions** \> **View history**.

3.  On the **Workflow history details** page, on the **Action Pane**, click **Recall**, and then close the page.

4.  On the **View user request** page, click **Edit** to modify the user request.

5.  To resubmit the request, click **Actions** \> **Submit**.

6.  You can add an optional comment for the customer before you submit the request. If you want to defer submitting the request, click **Close**.

## Recall and delete a user request

You can recall a user request from workflow only if the request does not have a status of **Approved** or **Completed**. After you recall the request, you can delete the request, or modify and resubmit it.

1.  Click **User requests** on the Quick Launch.

2.  On the **User requests** page, click the **Request ID** for the request that you want to delete, and then click **Actions** \> **View history**.

3.  On the **Workflow history details** page, on the **Action Pane**, click **Recall**, and then close the page.

4.  On the **View user request** page, click **Close**.

5.  On the **User requests** page, select the request that you want to delete, and then click **Delete**.

6.  Click **OK** to confirm the deletion.

## Delete an existing user

1.  Click **Contacts** on the Quick Launch.

2.  On the **Contacts** page, select the user who no longer requires access to the Vendor portal, and then click **Actions** \> **Inactivate vendor user**. The **Inactivate vendor user** button is available only if the contact is set up as a user in the Vendor portal.

3.  To save the request and submit the request to workflow, click **OK**. To close the request without saving it, click **Cancel**.

Requests to delete a user are sent for approval to the customer. After the request is approved, the user is removed from the system and the contact no longer has access to the Vendor portal. The status of the request is **Completed**.

## See also

[About the Vendor portal](about-the-vendor-portal.md)

[Maintain your company profile](maintain-your-company-profile.md)

[Maintain your contacts](maintain-your-contacts.md)

[About user roles](about-user-roles.md)

[About provisioning vendor users](about-provisioning-vendor-users.md)

  


