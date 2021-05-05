---
title: Add and maintain contacts and users
TOCTitle: Add and maintain contacts and users
ms:assetid: b66f6767-b819-4a61-aa1f-44c0e4bd03ad
ms:mtpsurl: https://technet.microsoft.com/library/Hh271631(v=AX.60)
ms:contentKeyID: 36384263
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- EPCSSContactListPage
- EPCSSCustSignUpUser
- EPCSSUserRequestExternalListPage
- EPCSSUserRequestExternalAdd
audience: Application User
ms.search.region: Global
---

# Add and maintain contacts and users 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In the Customer self-service portal, you can submit requests to add new users if you are the portal administrator for your organization. Users are the contacts in your organization who interact with the portal owner by using the Customer self-service portal. You can modify a request and resubmit it. You can also delete a request, as long as the request has not been approved. You can also submit requests to delete approved users. After you submit a user request to workflow, you can view the status of the request while the portal owner finishes the workflow tasks.

Before a user can be granted access, you must add the person as a contact in your profile. Also, each user of the Customer self-service portal must have unique credentials.

## Add a new contact

1.  Click **Contacts** on the Quick Launch

2.  On the **Action Pane**, on the **Contact** tab, in the **New** group, click **Contact**.

3.  Enter the name and title of the new contact person and then click **Create**.

4.  Enter additional contact details, and then click **Save and close** to save the new contact and return to the **Contacts** page. The new contact appears on the list of contacts.

## Add a new user

1.  Click **Contacts** on the Quick Launch.

2.  On the **Contacts** page, click the contact that you want to create a user request for, and then on the **Action Pane**, on the **Contact** tab, in the **New** group, click **Add customer user**.

3.  On the **Create new user request** page, select a role for the contact. The email address is used to notify the contact when the user request is approved or rejected.

4.  The authentication method defines how the user signs into the Customer self-service portal. The method is predefined and cannot be changed.

5.  Click **Save and close**.

6.  On the **View user request** page, you can perform the following tasks:
    
      - Click **Edit** to modify the information.
    
      - Click **Close** to close without submitting the request.
    
      - Click **Submit** to send the request to the portal owner for approval. You can add an optional comment to the portal owner before you submit the request.
    
      - Click **Close** to defer the submission of the request.

7.  To view the status of your user requests, click **User requests** on the Quick Launch. The status of a request changes as the request is processed:
    
      - **Draft**– The request has not been submitted for approval.
    
      - **Submitted**– The request has been submitted to workflow.
    
      - **Pending approval** – The request is in review.
    
      - **Approved** – The portal owner has approved the request.
    
      - **Completed** – The user request process is completed.
    
      - **Canceled** – You have canceled the user request.
    
      - **Rejected** – The portal owner has declined to approve the request.

New user requests go for approval to a designated sales account manager. If a request is approved, the account manager adds the user to Microsoft Dynamics AX and the request status is set to **Completed**. The new user can then access the Customer self-service portal.

## Recall and resubmit a user request

If you want to modify a user request that you have submitted for approval, you can recall the request from the approval process. You can recall a user request only if the request does not have a status of **Approved** or **Completed**.

1.  Click **User requests** on the Quick Launch.

2.  On the **User requests** page, click the **Request ID** for the request that you want to resubmit, and then click **Actions** \> **View history**.

3.  On the **Workflow history details** page, on the **Action Pane**, click **Recall**, and then close the page.

4.  On the **View user request** page, click **Edit** to modify the user request.

5.  To resubmit the request, click **Actions** \> **Submit**.

6.  You can add an optional comment for the portal owner before you submit the request. If you want to defer submitting the request, click **Close**.

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

2.  On the **Contacts** page, select the user who no longer requires access to the Customer self-service portal, and then click **Inactivate customer user** on the **Action Pane**. The **Inactivate customer user** button is available only if the contact is set up as a user in the Customer self-service portal.

3.  To save the request and submit the request to workflow, click **OK**.

Requests to delete a user must go for approval to the portal owner. After approval, the user is removed from the portal. The status of the request is **Completed**.

## See also

[About shopping for items](about-shopping-for-items.md)

[Sign up for an account](sign-up-for-an-account.md)

  


