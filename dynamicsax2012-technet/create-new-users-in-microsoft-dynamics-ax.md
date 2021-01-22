---
title: Create new users in Microsoft Dynamics AX
TOCTitle: Create new users in Microsoft Dynamics AX
ms:assetid: 4b742341-9d6e-4629-bbe5-620086b7fee8
ms:mtpsurl: https://technet.microsoft.com/library/Aa548139(v=AX.60)
ms:contentKeyID: 35132626
author: Khairunj
ms.author: daxcpft
ms.date: 06/27/2014
mtps_version: v=AX.60
---

# Create new users in Microsoft Dynamics AX 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX users are internal employees of your organization, or external customers and vendors, who require access to Microsoft Dynamics AX to perform their jobs. Any individual who must access Microsoft Dynamics AX must be added to the list of Microsoft Dynamics AX users in the **Users** form.

For users and groups that are in AD DS, you can use the **Active Directory Import Wizard** to import the users into Microsoft Dynamics AX.

This topic contains the following sections:

  - Add a new user

  - Import users from Active Directory

  - Change a user ID

## Add a new user

To add a single new user to Microsoft Dynamics AX, complete the following procedure. Use this procedure to add a user from AD DS or a user that is authenticated by a claims-based authentication provider. For more information about claims-based authentication in Microsoft Dynamics AX, see [Deploy an Enterprise Portal site that uses forms-based authentication](deploy-an-enterprise-portal-site-that-uses-forms-based-authentication.md).

1.  Click **System administration** \> **Common** \> **Users** \> **Users**.

2.  Click **User**.

3.  In the **User ID** field, enter a unique identifier for the user. A user ID is required. The user ID can contain a maximum of eight characters.
    
    You can’t change the information in the **User ID** field after the user record has been saved. For information about how to change a user ID, see Change a user ID.

4.  Optional: In the **User name** field, enter the user or group's name.

5.  In the **Network domain** field, enter the user or group's Active Directory Domain Services (AD DS) domain, if the user or group is authenticated by AD DS. If the user is authenticated by a claims-based authentication provider, this field displays the name of the trusted identity provider in SharePoint that authenticates the user.

6.  In the **Alias** field, enter a network alias if the user or group is in AD DS. If the user is not in AD DS, enter an e-mail address.

7.  In the **Account type** field, select whether the user or group is authenticated by AD DS or by a claims-based authentication provider.
    

    > [!WARNING]
    > <P>You must select the correct account type for the user or group to be validated. For example, an AD DS group is not recognized if <STRONG>Active Directory user</STRONG> is selected in the <STRONG>Account type</STRONG> field.</P>



8.  In the **Default company** list, select the company that the user logs on to by default. If you do not select a company, Microsoft Dynamics AX uses the current company that the administrator is logged on to.

9.  To grant the user access to Microsoft Dynamics AX, select **Enabled**.
    

    > [!NOTE]
    > <P>The <STRONG>External</STRONG> option is automatically selected when a user is designated as a web user.</P>



10. Click **Assign roles** to select the security roles that are assigned to the user. If you must assign the user to a role in a particular organization, select a role, and then click **Assign organizations**.
    
    For more information about how to assign users to roles manually or automatically, see [Assign users to security roles](assign-users-to-security-roles.md).
    
    Many users, especially external users, access Microsoft Dynamics AX by using Enterprise Portal for Microsoft Dynamics AX. For more information about how to grant access to Enterprise Portal, see [Enable users to access Enterprise Portal](enable-users-to-access-enterprise-portal.md).

## Import users from Active Directory

If you must create multiple new users, and those users are listed in AD DS, use the **Active Directory Import Wizard** to import the users into Microsoft Dynamics AX. For more information, see [Work with users from Active Directory](work-with-users-from-active-directory.md).

1.  Click **System administration** \> **Common** \> **Users** \> **Users**. Then click **Import**.

2.  The **Welcome to Active Directory Import Wizard** page is displayed. Click **Next \>**.

3.  The **Select Users to import from Active Directory** page is displayed. Select the AD DS domain to import users from, and then enter search criteria for the AD DS users or groups that you want to import.
    

    > [!NOTE]
    > <P>You cannot search for users by using only the <STRONG>Title</STRONG> field. To search on the <STRONG>Title</STRONG> field, you must also include at least one other field in the search criteria.</P>

    
    Click **Next \>**.

4.  The **Select users** page is displayed. This page shows the results of the AD DS search that was performed in the previous step. Select the check boxes next to the users to add to Microsoft Dynamics AX, and then click **Next \>**.

5.  Verify the users to be imported into Microsoft Dynamics AX.
    
    The wizard creates user IDs of up to five characters for the new Microsoft Dynamics AX users. The user ID is the first five characters of the AD DS alias.
    
    When multiple users in the group have the same first five characters in their AD DS aliases, the wizard automatically generates Microsoft Dynamics AX user IDs that consist of the first four characters of the AD DS alias, followed by a digit.
    
    You can’t change user IDs while you are running the wizard. For information about how to change a user ID, see Change a user ID.
    
    Click **Next \>**.

6.  The **Select roles** page is displayed. Use this page to assign security roles to the list of users. The roles that you select will be assigned to all the users that you are importing. If the users must be assigned to different roles, you can skip this page and assign roles to individual users after the users are imported.
    
    When you assign a user to a role by using this wizard, you cannot assign the user to a role in a specific organization. The user is assigned to the role in all organizations. To modify an individual user’s settings after you import users, use the **User** form.
    
    Click **Next \>**.

7.  The **Select profile** page is displayed. Use this page to assign profiles to the list of users. A user profile determines the content that is displayed on the Role Center page for the users who are assigned to that profile.
    
    Click **Next \>**.

8.  The **Completing the Active Directory Import Wizard** page is displayed. Click **Finish** to close the wizard.

## Change a user ID

When you import users from AD DS, user IDs are generated automatically. You can’t change user IDs while you are running the wizard, and you can’t change a user ID by using the **User ID** field in the **Users** form. To change a user ID, you must rename the key in the database. When you change a user ID by using this procedure, all related user settings are modified to use the new user ID. For example, the usage information in the SysLastValue table is updated to reference the new user ID.


> [!NOTE]
> <P>The user ID is the primary key of the user information table. Renaming the primary key can take some time, because all references to the key are also updated in the database.</P>



1.  Click **System administration** \> **Common** \> **Users** \> **Users**.

2.  Right-click a user in the list and select **Record info**.

3.  Click **Rename**.

4.  Enter a new value for the user ID, and then click **OK**. You must enter a unique value.

5.  Click **Yes** to confirm.

## See also

[Active Directory Import Wizard (form)](https://technet.microsoft.com/library/hh242519\(v=ax.60\))

[Assign users to security roles](assign-users-to-security-roles.md)

  


