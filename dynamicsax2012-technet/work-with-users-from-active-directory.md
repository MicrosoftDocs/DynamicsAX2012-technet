---
title: Work with users from Active Directory
TOCTitle: Work with users from Active Directory
ms:assetid: e503f808-e3de-456a-8f07-409e2c06326e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa497043(v=AX.60)
ms:contentKeyID: 39555423
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Work with users from Active Directory [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before users can be made Microsoft Dynamics AX users, they must be defined in Active Directory Domain Services (AD DS).

AD DS is a Microsoft Windows–based directory service that catalogs information about all the objects on a network and distributes that information throughout the network. These objects include people, computers, and printers. Security is integrated with AD DS through logon authentication and access control. For more information about AD DS, see [Active Directory Overview](http://go.microsoft.com/fwlink/?linkid=47868).

Before you install or deploy Microsoft Dynamics AX, carefully plan the user topology of your AD DS directory service. The computers that run Microsoft Dynamics AX must have access to computers in the same domain on which AD DS runs in native mode.

For information about how to configure AD DS, see one of the following resources:

  - [Deploy Active Directory Domain Services (AD DS) in Your Enterprise (Windows Server 2012)](http://technet.microsoft.com/en-us/library/hh472160.aspx)

  - [Deployment guide for Active Directory Domain Services on Windows Server 2008](http://go.microsoft.com/fwlink/?linkid=164995)

  - [Deployment guide for Active Directory Domain Services on Windows Server 2003](http://go.microsoft.com/fwlink/?linkid=164994)

Existing structures in AD DS do not require modification to support Microsoft Dynamics AX users. If you have AD DS domains, and all the domains in the forest are set up to have two-way trust, Microsoft Dynamics AX recognizes all the users in the domains. Work with the system administrator to understand the existing structures in AD DS.

## Create service accounts for required functionality

You must create the dedicated domain accounts that are required by various components of Microsoft Dynamics AX. For more information, see [Create service accounts](create-service-accounts.md).

## Import users from AD DS

After a user is listed in AD DS, you can manually add that user to Microsoft Dynamics AX. If you use the Active Directory Import Wizard, you can also import users from AD DS by specifying various search criteria.

For more information about how to add users, see [Create new users in Microsoft Dynamics AX](create-new-users-in-microsoft-dynamics-ax.md).

## Administrator permissions

The Microsoft Dynamics AX administrator does not have to be a domain administrator to import users from AD DS. However, a Microsoft Dynamics AX administrator who is also a domain administrator can see all users in AD DS and import those users into Microsoft Dynamics AX. Because of security functionality in the Group Policy objects (GPOs) for AD DS, a Microsoft Dynamics AX administrator who is not a domain administrator can see only a subset of the users in AD DS.

To see the complete list of users in AD DS during import, a Microsoft Dynamics AX administrator who is not a domain administrator must be a member of the **Authenticated users** security group on the domain. Use the following procedure to add a member to the **Authenticated users** security group.

1.  In **Active Directory Users and Computers**, on the **View** menu, make sure that **Advanced Features** is selected.

2.  Right-click a user that you cannot see when you run the import wizard, and then select **Properties**.

3.  Click the **Member Of** tab. Confirm that the user is listed as a member of the **Domain Users** group.

4.  Click the **Security** tab. Select the **Authenticated Users** group, and then make sure that **Read** is set to **Allow**.

If you want all authenticated users to see the complete list of users in AD DS during import, grant the **Authenticated Users** security group **Read** permissions to all objects.

1.  In **Active Directory Users and Computers**, on the **View** menu, make sure that **Advanced Features** is selected.

2.  Click the **Users** organizational unit. The **User Properties** dialog box appears.

3.  Click the **Security** tab, and select the **Authenticated Users** group.

4.  Click the **Advanced** tab. Select **Authenticated Users Name**, and then click **Edit**.

5.  Make sure that **Read all properties** is selected. Then, in the **Apply to** box, select **This object and all descendant objects**.

## Duplicate alias IDs

When you import users from AD DS into Microsoft Dynamics AX, the import wizard tries to create Microsoft Dynamics AX user IDs from the AD DS aliases. However, a Microsoft Dynamics AX user ID is limited to five characters, whereas an AD DS alias can have up to 255 characters. If the first five characters of the AD DS alias are the same for more than one user, the wizard generates alternative Microsoft Dynamics AX user IDs for these users.

When alternative user IDs are generated, if the alias has more than five characters, the first four characters of the first name and a single character from the last name are used. If there are still duplicates, the first three characters of the first name and two characters from the last name are used.

You can’t change user IDs while running the wizard. However, you can change user IDs later to make them more meaningful. For more information, see [Create new users in Microsoft Dynamics AX](create-new-users-in-microsoft-dynamics-ax.md).

## Assign an AD DS group to a role

You can assign AD DS groups to roles in Microsoft Dynamics AX. When an AD DS group is assigned to a role, membership in the role corresponds to membership in the group.


> [!WARNING]
> <P>When an AD DS group is assigned to a security role, Microsoft Dynamics AX is unable to calculate conflicts in segregation of duties for individual users who are part of the AD DS group.</P>


  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

