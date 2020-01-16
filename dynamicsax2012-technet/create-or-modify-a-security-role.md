---
title: Create or modify a security role
TOCTitle: Create or modify a security role
ms:assetid: 69f36fc7-9792-410f-9f75-5a3cb74ab97c
ms:mtpsurl: https://technet.microsoft.com/library/Gg731823(v=AX.60)
ms:contentKeyID: 35132671
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Create or modify a security role 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If the security roles that are provided with Microsoft Dynamics AX do not meet the needs of your business, you can create new roles. You can create a custom role that is based on an existing role, or you can build a completely new role.

Work with managers who oversee the different groups in your business to determine the appropriate permission levels for roles. For example, work with a manager in the Finance department to determine permission levels for Finance roles.

Only the Microsoft Dynamics AX administrator can create or modify a role.


> [!IMPORTANT]
> <P>Be aware that modifying roles may affect your licensing requirements. For more information about how licensing relates to security, see the <A href="http://go.microsoft.com/fwlink/?linkid=228370">Security roles and licensing white paper</A> for Microsoft Dynamics AX 2012.</P>



1.  Click **System administration** \> **Setup** \> **Security** \> **Security roles**.

2.  To create a new role, click **New**. To modify an existing role, select the role.

3.  If you are creating a new role, enter the name that you want to appear for the role in the Application Object Tree (AOT).
    

    > [!NOTE]
    > <P>AOT names must contain only alphanumeric or underscore characters. AOT names cannot begin with a number, and they cannot contain special characters or spaces.</P>



4.  Enter or modify the display name of the role.

5.  Enter or modify the description of the role.

6.  To add security privileges to the selected role, click **Add...** to open the **Add privileges to role** form.
    
    Find the security privileges that you want to add. You can sort and view the privileges by role, process cycle, or duty/privilege. You can also enter a privilege name or keywords in the **Find** field.
    

    > [!TIP]
    > <P>Security is organized hierarchically. Permissions on specific application elements are combined into privileges, privileges are combined into duties, and duties are grouped into process cycles. You can assign either duties or privileges to roles. For more information about the security hierarchy, see <A href="security-architecture-of-the-microsoft-dynamics-ax-application.md">Security architecture of the Microsoft Dynamics AX application</A>.</P>

    
    To include all of the permissions from another role, open the **Security roles** form, and drag the role that has the permissions that you want to the role that you are modifying. By dragging one role to another, you create a hierarchical relationship, where the main role contains all of the permissions of the sub-role. If you change the permissions of a sub-role, the changes also apply to the main role.
    
    A role cannot contain duties that conflict according to the rules for the segregation of duties. For more information, see [Set up segregation of duties](set-up-segregation-of-duties.md).
    
    To remove a duty, privilege, or sub-role from the role, select the duty, privilege, or sub-role, and then click **Remove**.

7.  To change the role’s permission level on securable objects such as controls, tables, fields, and server methods, right-click the role, and then click **Override permissions**.
    

    > [!NOTE]
    > <P>Overrides for securable objects are not associated with specific duties or privileges. If you apply an override, the access level for the securable object is set for the role, regardless of access levels specified by the duties and privileges assigned to that role.</P>



8.  To limit access to rows, or records, in the database based on a query, you can use record-level security. To apply filters for record-level security, right-click the role, and then click **Record-level security**. For more information, see [Manage record level security](manage-record-level-security.md).
    

    > [!IMPORTANT]
    > <P>The record-level security feature will become obsolete in a future release. If you are setting up new filters, we recommend that you create data security policies by using the extensible data security framework.</P>



9.  When you have finished modifying the role, click **Close** in the **Security roles** form.

## See also

[Assign users to security roles](assign-users-to-security-roles.md)

  


