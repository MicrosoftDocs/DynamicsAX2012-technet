---
title: About provisioning vendor users
TOCTitle: About provisioning vendor users
ms:assetid: 734aac7f-b569-4c31-8867-261d4a419035
ms:mtpsurl: https://technet.microsoft.com/library/Hh209227(v=AX.60)
ms:contentKeyID: 36058142
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About provisioning vendor users 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic presents scenarios for user request provisioning and provides an overview of the difference between automatic and manual provisioning. It also provides an outline of the workflow for vendor requests and user requests.

User provisioning automates the process of creating Microsoft Dynamics AX user accounts and assigning user permissions. This simplifies the process of creating users and helps ensure appropriate control of users and their access to the Vendor portal.


> [!NOTE]
> <P>Microsoft Dynamics AX 2012 supports flexible authentication. Flexible authentication allows users to be authenticated in Microsoft Dynamics AX by using Windows Live ID, Active Directory Federation Services (AD FS), or forms-based authentication. When you use flexible authentication, users do not have to be listed in Active Directory Domain Services (AD&nbsp;DS) to access forms or data in Microsoft Dynamics AX. For more information, see <A href="deploy-an-enterprise-portal-site-that-uses-forms-based-authentication.md">Deploy an Enterprise Portal site that uses forms-based authentication</A>.</P>



Several steps must be completed before user provisioning is operational in Microsoft Dynamics AX. For more information, see [Key tasks: Set up vendor user provisioning](key-tasks-set-up-vendor-user-provisioning.md).

## Scenarios for provisioning vendor users

The following table outlines different types of vendor user requests and when each type might be used.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>User request type</p></th>
<th><p>Purpose</p></th>
<th><p>Request submitted by</p></th>
<th><p>Reason for the request</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Add user request (prospective vendor)</p></td>
<td><p>Request credentials for the vendor contact at a prospective vendor company</p></td>
<td><p>Workflow</p></td>
<td><p>A vendor request was approved. The vendor contact needs access to Enterprise Portal for Microsoft Dynamics AX to complete the vendor application.</p></td>
</tr>
<tr class="even">
<td><p>Add user request (vendor)</p></td>
<td><p>Request credentials for a new vendor contact at a vendor company with which you already do business</p></td>
<td><p>The Vendor portal administrator at the vendor company</p></td>
<td><p>A vendor contact was added as a contact in the Vendor portal. Now the contact needs logon information to view data in the Vendor portal and take action on it.</p></td>
</tr>
<tr class="odd">
<td><p>Inactivate user request (vendor)</p></td>
<td><p>Remove credentials for a vendor user</p></td>
<td><p>The Vendor portal administrator at the vendor company</p></td>
<td><p>Access to the Vendor portal must be removed because a user no longer holds a position that requires access to the Vendor portal.</p></td>
</tr>
</tbody>
</table>


## Provisioning users automatically and manually

**Provision users automatically**

If you authenticate vendor users by using forms-based authentication, Active Directory Federation Services (AD FS), or Windows Live ID, you can configure the user request workflow to provision users automatically. When the user request workflow template is configured to automatically provision users, the following actions are automatically performed after the request is approved:

1.  A user is created in Microsoft Dynamics AX. The user alias in Microsoft Dynamics AX is the same alias that is used when the user logs on through the authentication provider.

2.  A profile is created for the user. Also, an external relationship is added to associate the vendor company with the legal entities in which the vendor is allowed to do business.

3.  A security role is assigned to the vendor.
    
      - For prospective vendors, the security role is **Vendor prospect (external)**.
    
      - For vendor users, the security role is either **Vendor portal administrator (external)** or **Vendor (external)**.

**Provision users manually**

If you are not using the vendor request process to control employee requests for new vendors and the vendor onboarding process, you can set up vendor users manually without using the user request workflow. For more information, see [Key tasks: Manually set up user access to the Vendor portal](key-tasks-manually-set-up-user-access-to-the-vendor-portal.md). We do not recommend that you use this process if your organization is large or complex.


> [!NOTE]
> <P>The vendor request process requires that you use the user request process to generate a new user request for the vendor contact at the prospective vendor company. You cannot manually create a prospective vendor user request.</P>



## How vendor requests and user requests work together

Vendor user provisioning is an important part of the vendor request process. The following list provides an overview of the process.

1.  An employee of your company wants to do business with a vendor who is not an approved vendor for your organization. The employee submits a new vendor request.

2.  A reviewer reviews the request.

3.  The vendor request is approved, which initiates the user request workflow.

4.  After the request is approved, the user is set up in Microsoft Dynamics AX in one of the following ways:
    
      - The user is provisioned automatically by the workflow process. After the user provisioning process is completed and the user is set up, workflow changes the status of the user request to **Completed** and the vendor request status changes to **Vendor invited**.
    
      - The system administrator creates the new user from the user request and then sets up the user manually. After the system administrator sets up the user in Microsoft Dynamics AX, the system administrator returns to the user request and sets the workflow status to **Completed**. Then, workflow changes the status of the vendor request to **Vendor invited**.

5.  An invitation to complete the vendor application is automatically sent to the contact at the prospective vendor company.

6.  The prospective vendor contact fills out the vendor application on the **Vendor registration** page in Enterprise Portal.

7.  The reviewer reviews and approves the vendor application.

8.  After the vendor application is approved, the vendor contact’s role is automatically changed in the Microsoft Dynamics AX client. The **Vendor prospect (external)** role is removed and the **Vendor portal administrator (external)** role is assigned.
    

    > [!NOTE]
    > <P>The initial vendor contact is automatically assigned the <STRONG>Vendor administrator (external)</STRONG> role. This allows the vendor contact to submit user requests on behalf of other vendor contacts. Only users who have the <STRONG>Vendor portal administrator (external)</STRONG> role can submit user requests in the Vendor portal.</P>



9.  The role in the vendor contact’s user profile is automatically updated from prospective vendor to vendor.

10. An email message is automatically sent to the contact at the prospective vendor company to inform them that their application has been approved. The message also provides logon information that the vendor contact can use to access the Vendor portal.

11. In the Vendor portal, the contact can now submit requests to grant other workers at the vendor company access to the Vendor portal

## See also

[Key tasks: Set up vendor user provisioning](key-tasks-set-up-vendor-user-provisioning.md)

  


