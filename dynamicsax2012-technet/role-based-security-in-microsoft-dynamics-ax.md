---
title: Role-based security in Microsoft Dynamics AX
TOCTitle: Role-based security in Microsoft Dynamics AX
ms:assetid: 498dde2e-9881-4281-a3f1-ac3753f5794a
ms:mtpsurl: https://technet.microsoft.com/library/Gg731787(v=AX.60)
ms:contentKeyID: 35132622
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Role-based security in Microsoft Dynamics AX 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In role-based security, access is not granted to individual users, only to security roles. Users are assigned to roles. A user who is assigned to a security role has access to the set of privileges that is associated with that role. A user who is not assigned to any role has no privileges.

In Microsoft Dynamics AX, role-based security is aligned with the structure of the business. Users are assigned to security roles based on their responsibilities in the organization and their participation in business processes. The administrator grants access to the duties that users in a role perform, not to the program elements that users must use.

Because rules can be set up for automatic role assignment, the administrator does not have to be involved every time that a user's responsibilities change. After security roles and rules have been set up, business managers can control day-to-day user access based on business data.

## Role-based security concepts

This section provides an overview of the elements of role-based security in Microsoft Dynamics AX. The security model is hierarchical, and each element in the hierarchy represents a different level of detail. Permissions represent access to individual securable objects, such as menu items and tables. Privileges are composed of permissions and represent access to tasks, such as canceling payments and processing deposits. Duties are composed of privileges and represent parts of a business process, such as maintaining bank transactions. Both duties and privileges can be assigned to roles to grant access to Microsoft Dynamics AX.

The following illustration shows the elements of role-based security and their relationships.

![role-based security](images/Gg731787.Role-basedsecurity(AX.60).gif "role-based security")

The following sections explain the elements of the security model in more detail.

## Security roles

All users must be assigned to at least one security role in order to have access to Microsoft Dynamics AX. The security roles that are assigned to a user determine the duties that the user can perform and the parts of the user interface that the user can view.

Administrators can apply data security policies to limit the data that the users in a role have access to. For example, a user in a role may have access to data only from a single organization. The administrator can also specify the level of access that the users in a role have to current, past, and future records. For example, users in a role can be assigned privileges that allow them to view records for all periods, but that allow them to modify records only for the current period.

By managing access through security roles, administrators save time because they do not have to manage access separately for each user. Security roles are defined one time for all organizations. In addition, users can be automatically assigned to roles based on business data. For example, the administrator can set up a rule that associates a Human resources position with a security role. Any time that users are assigned to that position, those users are automatically added to the appropriate security roles. Users can also be automatically added to or removed from roles based on the Active Directory groups that they belong to.

Security roles can be organized into a hierarchy. The role hierarchy allows the administrator to define a role based on another role. For example, the sales manager role could be defined as a parent role of the manager role and the salesperson role. A parent role automatically inherits the duties, privileges, and conditions that are assigned to its child roles. Therefore, a user who is assigned to the parent role can perform all of the tasks that users in the child roles can perform. A role can have one or more child roles or one or more parent roles.

By default, sample security roles are provided. All functionality in Microsoft Dynamics AX is associated with at least one of the sample security roles. The administrator can assign users to the sample security roles, modify the sample security roles to fit the needs of the business, or create new security roles. By default, the sample roles are not arranged in a hierarchy.


> [!NOTE]
> <P>The sample security roles do not correspond to Role Centers.</P>



For more information about how to work with security roles, see the following topics:

  - [Security role reference](security-role-reference.md)

  - [Create or modify a security role](create-or-modify-a-security-role.md)

  - [Assign users to security roles](assign-users-to-security-roles.md)

  - [Data security in Microsoft Dynamics AX](data-security-in-microsoft-dynamics-ax.md)

## Process cycles

A business process is a coordinated set of activities in which one or more participants consume, produce, and use economic resources to achieve organizational goals.

To help the administrator locate the duties that must be assigned to roles, duties are organized by the business processes that they are part of. In the context of the security model, business processes are referred to as process cycles. For example, in the accounting process cycle, you may find the **Maintain ledgers** and **Maintain bank transactions** duties.

Process cycles are used for organization only. The process cycles themselves cannot be assigned to roles.

## Duties

Duties correspond to parts of a business process. The administrator assigns duties to security roles. A duty can be assigned to more than one role.

In the security model for Microsoft Dynamics AX, duties contain privileges. For example, the **Maintain bank transactions** duty contains the **Generate deposit slips** and **Cancel payments** privileges. Although both duties and privileges can be assigned to security roles, we recommend that you use duties to grant access to Microsoft Dynamics AX.

You can assign related duties to separate roles. These duties are said to be segregated. By segregating duties, you can better comply with regulatory requirements, such as those from Sarbanes-Oxley (SOX), International Financial Reporting Standards (IFRS), and the United States Food and Drug Administration (FDA). In addition, segregation of duties helps reduce the risk of fraud, and helps you detect errors or irregularities.

Default duties are provided. The administrator can modify the privileges that are associated with a duty, or create new duties.

For more information about how to work with duties, see the following topics:

  - [Set up segregation of duties](set-up-segregation-of-duties.md)

  - [Create or modify a security privilege, duty, or process cycle](create-or-modify-a-security-privilege-duty-or-process-cycle.md)

## Privileges

In the security model for Microsoft Dynamics AX, a privilege specifies the level of access that is required to perform a job, solve a problem, or complete an assignment. Privileges can be assigned directly to roles. However, for easier maintenance, we recommend that you assign only duties to roles.

A privilege contains permissions to individual application objects, such as user interface elements and tables. For example, the **Cancel payments** privilege contains permissions to the menu items, fields, and tables that are required to cancel payments.

By default, privileges are provided for all features in Microsoft Dynamics AX. The administrator can modify the permissions that are associated with a privilege, or create new privileges.

## Permissions

Each function in Microsoft Dynamics AX, such as a form or a service, is accessed through an entry point. Menu items, web content items, and service operations are referred to collectively as entry points.

In the security model for Microsoft Dynamics AX, permissions group the securable objects and access levels that are required to run a function. This includes any tables, fields, forms or server side methods that are accessed through the entry point.

Only developers can create or modify permissions. For more information about how to work with permissions, see the Microsoft Dynamics AX developer documentation. Be aware that modifying permissions may affect your licensing requirements. For more information about how licensing relates to security, see the [Security roles and licensing white paper](http://go.microsoft.com/fwlink/?linkid=228370) for Microsoft Dynamics AX 2012.


> [!IMPORTANT]
> <P>In the licensing model for Microsoft Dynamics AX, entry points are referred to as menu items.</P>



## See also

[Manage users](manage-users.md)

[Manage roles](manage-roles.md)

[Data security in Microsoft Dynamics AX](data-security-in-microsoft-dynamics-ax.md)

[Set up segregation of duties](set-up-segregation-of-duties.md)

  


