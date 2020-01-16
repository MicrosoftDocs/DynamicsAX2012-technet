---
title: Assign users to security roles
TOCTitle: Assign users to security roles
ms:assetid: 214ee45b-5b99-4ea8-9454-f4297f68e38c
ms:mtpsurl: https://technet.microsoft.com/library/Gg751367(v=AX.60)
ms:contentKeyID: 35132576
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Assign users to security roles 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To access Microsoft Dynamics AX, users must be assigned to security roles. You can assign users to roles automatically, based on business data, or you can assign users to roles manually. We recommend that you assign roles automatically most of the time.


> [!IMPORTANT]
> <P>Users must exist in Microsoft Dynamics AX before they can be assigned to roles. Even if you use automatic role assignment, users are not automatically added to Microsoft Dynamics AX. For more information about how to add users, see <A href="create-new-users-in-microsoft-dynamics-ax.md">Create new users in Microsoft Dynamics AX</A>.</P>



You can assign individual users or Active Directory groups to a role.

Users can be assigned to multiple roles. If a user is assigned to multiple roles that grant different levels of access to the same item, the user has the highest level of access that the various roles grant. For example, if the user is a member of both role A, which has View access to sales orders, and role B, which has Create access to sales orders, the user has Create access to sales orders.

## Automatically assign users to roles

Set up rules for automatic role assignment to guarantee that role membership is based on current business data. If you use automatic role assignment, permissions are automatically updated when people change jobs in an organization.

Rules for automatic role assignment run at a fixed interval by using the batch framework. The batch job for role assignment belongs to the default, or blank, batch group.


> [!TIP]
> <P>If automatic role assignment is not working as expected, make sure that the batch job is enabled. Additionally, make sure that the default batch group is assigned to a batch server, and that batch servers are currently processing batches. Upgrades and other non-interactive processes can disable the batch job, and batch servers may be configured to run only at certain times of the day.</P>



If a rule for automatic role assignment encounters a conflict that is related to the segregation of duties, the user who has the conflict cannot be automatically assigned to the role. Instead, the user is marked as excluded from the role. The user is also listed in the **Segregation of duties unresolved conflicts** form. (Click **System administration** \> **Setup** \> **Security** \> **Segregation of duties** \> **Segregation of duties unresolved conflicts**.) For more information, see [Set up segregation of duties](set-up-segregation-of-duties.md).

1.  Click **System administration** \> **Setup** \> **Security** \> **Assign users to roles**.

2.  Select a role. The users who are currently assigned to the role are displayed.

3.  In the **Rules for dynamically assigning users to role** pane, click **Add rule** to open a list of queries that can be used for automatic role assignment. Queries in the list use the UserInfo table as the primary data source, and the User field is included in the list of fields.
    

    > [!IMPORTANT]
    > <P>By default, the <STRONG>Security administrator</STRONG> role has access to only a subset of tables and fields in Microsoft Dynamics AX. If the <STRONG>Security administrator</STRONG> role is required to use other tables in a query, the permissions for the role must be modified to grant access to those tables. For more information, see <A href="https://technet.microsoft.com/library/hh209290(v=ax.60)">Override permissions (form)</A>.</P>



4.  Select a query in the list.
    
    To modify a query, select it, and then click **Edit query**. In the **Inquiry** form, use the **Range** tab to add or remove fields. Click **OK** to save the query. When you save a query, it runs immediately.

5.  The rule is assigned a default name. If necessary, you can modify the name or add a description by typing in the list.

## Exclude users from automatic role assignment

Users who are automatically assigned to roles cannot be removed from those roles by the administrator. However, the administrator can exclude users from roles. When you exclude a user from a role, the user’s role assignment is no longer controlled automatically. When the rules for automatic role assignment run, or when an Active Directory group is assigned to a role, excluded users are listed in the role membership, but they are marked as excluded. The excluded users are not granted the access that is associated with the role. Excluded users cannot be assigned to the role until the administrator removes the exclusion.

1.  Click **System administration** \> **Setup** \> **Security** \> **Assign users to roles**.

2.  Select a role. The users who are currently assigned to the role are displayed.

3.  In the **Users assigned to role** pane, click **Manually assign / exclude users** to open the **Assign users to or exclude users from role** form.

4.  Select the users who you want to exclude from the role. To select multiple users, hold down the **CTRL** key, and then click each user that you want to exclude.
    
    Click **Exclude from role** to exclude the users from the role.
    
    To remove exclusions, select the users who you want to remove exclusions for, and then click **Reset status**.
    
    When you remove an exclusion by resetting the user’s status, the user’s role is again assigned automatically. However, the user is not immediately assigned to the role or excluded from the role when you reset the status. Instead, the user is either assigned to the role or removed from the role the next time that the rules for automatic role assignment run.

5.  When you have finished making changes, close the **Assign users to or exclude users from role** form.

## Manually assign users to roles

Manually assign users to roles when role membership cannot be based on data in Microsoft Dynamics AX. For example, you can manually assign roles if an employee goes on vacation, and another employee must temporarily perform that employee's duties. Users who are manually assigned to security roles must also be manually removed by the administrator. These users are not removed from roles by rules for automatic role assignment.

1.  Click **System administration** \> **Setup** \> **Security** \> **Assign users to roles**.

2.  Select a role. The users who are currently assigned to the role are displayed.

3.  In the **Users assigned to role** pane, click **Manually assign / exclude users** to open the **Assign users to or exclude users from role** form.

4.  Select the users who you want to add to the role. To select multiple users, hold down the **CTRL** key, and then click each user that you want to add.

5.  Click **Assign to role** to add the users to the role.
    
    Do not assign users to roles that contain duties that conflict according to the rules for the segregation of duties. If you attempt to assign a user to a role, and the duties of that role conflict with the duties of a role that was previously assigned to the user, a message is displayed. The user is not assigned to the new role. For more information, see [Set up segregation of duties](set-up-segregation-of-duties.md).
    

    > [!WARNING]
    > <P>When an Active Directory Domain Services group is assigned to a security role, Microsoft Dynamics AX is unable to calculate conflicts in segregation of duties for individual users who are part of the Active Directory Domain Services group.</P>



6.  When you have finished making changes, close the **Assign users to or exclude users from role** form.

## See also

[Create or modify a security role](create-or-modify-a-security-role.md)

  


