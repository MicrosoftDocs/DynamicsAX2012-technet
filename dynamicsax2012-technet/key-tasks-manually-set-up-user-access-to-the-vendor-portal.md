---
title: 'Key tasks: Manually set up user access to the Vendor portal'
TOCTitle: 'Key tasks: Manually set up user access to the Vendor portal'
ms:assetid: 8899ef84-e217-44c5-80e4-ba1480e9992c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh209340(v=AX.60)
ms:contentKeyID: 36058450
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- setup
- vendor portal
- user access
---

# Key tasks: Manually set up user access to the Vendor portal [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Some organizations do not use the user request process to manage vendor users' access to the Vendor portal in Enterprise Portal for Microsoft Dynamics AX. Instead, they rely on system administrators to perform the user management tasks manually. In these cases, the system administrator must create the vendor user, set up the vendor user profile, and assign user permissions.

Microsoft Dynamics AX supports a number of authentication methods. However, if you are not using the user request process to manage vendor user access, you must use Active Directory Domain Services (AD DS) authentication. To use the AD DS authentication, you must create an AD DS user account for the vendor contact before you set them up in Microsoft Dynamics AX. Instructions for adding users to an AD DS group can be found on [Microsoft TechNet](http://technet.microsoft.com).

This topic outlines the steps that you must take to set up vendor users when you are not using the user request process to control user access to the Vendor portal.

## What do you want to do?

Learn more about...

Create a Microsoft Dynamics AX user for the contact at the vendor company

Associate the vendor user in Microsoft Dynamics AX with the vendor company

Assign the vendor contact to a vendor role

Inactivate a Vendor portal user

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[Manage vendor requests overview](manage-vendor-requests-overview.md)

[Configuring Enterprise Portal for vendor requests](configuring-enterprise-portal-for-vendor-requests.md)

## Create a Microsoft Dynamics AX user for the contact at the vendor company

You enable vendors to update their vendor profile and complete transactions in the Vendor portal. Before contacts at the vendor location can perform these tasks, they must be users in Microsoft Dynamics AX.

1.  Click **System administration** \> **Common** \> **Users** \> **Users**. Press CTRL+N to create a new user.
    

    > [!IMPORTANT]
    > <P>If you are creating new users in Microsoft Dynamics AX while you are working through the Initialization Checklist, make sure that you have entered license information before you add users. If you add a user before you enter license information, the user may be granted elevated permissions (Administrator permissions) in the program.</P>



2.  In the **User** form, on the **General** FastTab, in the **Alias** field, enter the prospective vendor contact’s user alias exactly as it is stored in Active Directory Domain Services (AD DS).

3.  In the **Network domain** field, enter the user's AD DS domain.

4.  In the **User ID** field, enter any unique identification for this individual. The user identification is restricted to a maximum of five characters.

5.  Optional: In the **User name** field, enter the user's name.

6.  In the **Default company** field, select the legal entity that this user can access in Microsoft Dynamics AX. If you do not select a legal entity, Microsoft Dynamics AX uses the legal entity that the administrator is currently logged onto.
    

    > [!NOTE]
    > <P>If you have set up multiple legal entities in Microsoft Dynamics AX to reflect the structure of your organization, you must grant users access to each of these legal entities.</P>



7.  To allow the user to access Microsoft Dynamics AX, select **Enabled**. The program checks to make sure that the user is listed in AD DS. If the user is not listed, the program returns an error.
    

    > [!NOTE]
    > <P>The <STRONG>External</STRONG> check box is read-only. An external user is any individual who accesses Microsoft Dynamics AX by using Enterprise Portal for Microsoft Dynamics AX or a web browser. This option is automatically set if the user is stored in AD&nbsp;DS as described in the topic <A href="enable-users-to-access-enterprise-portal.md">Enable users to access Enterprise Portal</A> in the Enterprise Portal Administration Guide.</P>



8.  Press CTRL+S to save your changes.

Back to top

## Associate the vendor user in Microsoft Dynamics AX with the vendor company

The vendor contact is now a Microsoft Dynamics AX user. Now the contact must be linked to the vendor company as an external relation.


> [!NOTE]
> <P>Users cannot access Microsoft Dynamics AX until they are added to at least one user role.</P>



1.  Click **System administration** \> **Common** \> **Users** \> **User relations**.

2.  In the **User relations** form, in the left pane, select the vendor user.

3.  Under **External relations**, click **Add**.

4.  In the **Relation type** field, select **Vendor**.

5.  In the **Legal entity** field, select the legal entity with which the vendor contact is associated.
    

    > [!NOTE]
    > <P>You must add the vender as an external relation to each legal entity in your organization that the vendor will do business with.</P>



6.  In the **Name** field, select the vendor.

7.  Press CTRL+S to save your changes.

Back to top

## Assign the vendor contact to a vendor role

Now that the vendor contact is a user in Microsoft Dynamics AX and has a user profile that is associated with the vendor company, you must assign the vendor to a vendor-specific role. This role gives the vendor access to the Vendor portal.

1.  Click **System administration** \> **Setup** \> **Security** \> **Assign users to roles**.

2.  In the **Assign users to roles** form, in the left pane, select the **Vendor (external)** role.

3.  In the **Users assigned to role** pane, click **Manually assign / exclude users**.

4.  In the **Assign users to or exclude users from role** form, select the vendor user from the user list, and then click **Assign to role**. Then click **Close**.

Back to top

## Inactivate a Vendor portal user

You may have to remove a vendor user's access to the Vendor portal. For example, you would remove access if the vendor contact left the company.

1.  Click **System administration** \> **Common** \> **Users** \> **Users**.

2.  On the **Action Pane**, in the **Maintain** group, click **Edit in grid**.

3.  In the **Users** form, select the vendor user from the user list, and then clear the **Enabled** check box.


> [!NOTE]
> <P>A vendor user should be inactivated only if the vendor user does not have additional external roles that provide access to either the Microsoft Dynamics AX client or an Enterprise Portal web portal. For example, the user may have access to the Customer portal or the Employee services portal. In these cases, you should delete the <STRONG>Vendor (external)</STRONG> role for the vendor user and remove the user from the list of users who are assigned the <STRONG>Vendor (external)</STRONG> role.</P>



Back to top

## Find form help

[Users (list page)](https://technet.microsoft.com/en-us/library/hh227603\(v=ax.60\))

[User relations (form)](https://technet.microsoft.com/en-us/library/aa575077\(v=ax.60\))

[Assign users to roles (form)](https://technet.microsoft.com/en-us/library/hh209671\(v=ax.60\))

## Find related tasks

[Key tasks: Set up vendor user provisioning](key-tasks-set-up-vendor-user-provisioning.md)

[Key tasks: Set up vendor add requests](key-tasks-set-up-vendor-add-requests.md)

[Key tasks: Review new vendor requests from employees](key-tasks-review-new-vendor-requests-from-employees.md)

[Key tasks: Manage prospective vendor requests](key-tasks-manage-prospective-vendor-requests.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

