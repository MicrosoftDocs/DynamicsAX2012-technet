---
title: 'Scenario: Mapping security in Microsoft Dynamics AX to Analysis Services'
TOCTitle: 'Scenario: Mapping security in Microsoft Dynamics AX to Analysis Services'
ms:assetid: 509f0bbf-e63d-4c12-9f6a-6484aeb08b2a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ129499(v=AX.60)
ms:contentKeyID: 46661153
ms.date: 06/04/2014
mtps_version: v=AX.60
---

# Scenario: Mapping security in Microsoft Dynamics AX to Analysis Services 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Security for analysis cubes is set up independently of security for Microsoft Dynamics AX. This topic describes methods that you can use to map the security that you implemented in Microsoft Dynamics AX to security in Microsoft SQL Server Analysis Services.

## Mapping Microsoft Dynamics AX roles to Analysis Services roles

When you deploy the cubes that are included with Microsoft Dynamics AX, default roles are created in the Analysis Services database where you deploy the cubes. These roles correspond to roles in Microsoft Dynamics AX. If you assign a user to a specific role in Microsoft Dynamics AX, you should assign that user to the corresponding role in Analysis Services. For example, if you assign a user to the **Accountant** role in Microsoft Dynamics AX, assign that user to the **Accountant** role in Analysis Services. For a list of the default roles that are created in Analysis Services, see [Default Analysis Services roles](default-analysis-services-roles.md).

## Determining which Microsoft Dynamics AX roles have access to privileges and duties

Microsoft Dynamics AX has a role-based security model. The security model is hierarchical, and each element in the hierarchy represents a different level of detail. Permissions represent access to individual securable objects, such as menu items and tables. *Privileges* are composed of permissions and represent access to tasks, such as viewing a report. *Duties* are composed of privileges and represent parts of a business process, such as maintaining bank transactions. Both duties and privileges can be assigned to roles to grant access to Microsoft Dynamics AX. For more information about the security model for Microsoft Dynamics AX, see [Role-based security in Microsoft Dynamics AX](role-based-security-in-microsoft-dynamics-ax.md).

For example, assume that you have created or modified privileges and duties in Microsoft Dynamics AX. The following procedures explain how to determine which Microsoft Dynamics AX roles have been assigned to specific privileges and duties. You can then assign users to corresponding roles in Analysis Services.

## Determine which roles have access to a privilege

Follow these steps to determine which roles in Microsoft Dynamics AX have access to a privilege.

1.  Open Microsoft Dynamics AX.

2.  Click the **Windows** icon, which is located in the upper-right corner. Then click **New Development Workspace**. The Application Object Tree (AOT) is displayed.

3.  Expand the **Security** \> **Privileges** node.

4.  Right-click a privilege, and then click **Add-Ins** \> **Security tools** \> **View related security roles**.
    
    The **Roles** form is displayed. This form lists the Microsoft Dynamics AX roles that have access to the privilege.

5.  Assign the users in those Microsoft Dynamics AX roles to corresponding roles in Analysis Services. For information about how to assign users to roles in Analysis Services, see [Grant users access to cubes](grant-users-access-to-cubes.md).

## Determine which roles have access to a duty

Follow these steps to determine which roles in Microsoft Dynamics AX have access to a duty.

1.  Open Microsoft Dynamics AX.

2.  Click the **Windows** icon, which is located in the upper-right corner. Then click **New Development Workspace**. The AOT is displayed.

3.  Expand the **Security** \> **Duties** node.

4.  Right-click a duty, and then click **Add-Ins** \> **Security tools** \> **View related security roles**.
    
    The **Roles** form is displayed. This form lists the Microsoft Dynamics AX roles that have access to the duty.

5.  Assign the users in those Microsoft Dynamics AX roles to corresponding roles in Analysis Services. For information about how to assign users to roles in Analysis Services, see [Grant users access to cubes](grant-users-access-to-cubes.md).

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

