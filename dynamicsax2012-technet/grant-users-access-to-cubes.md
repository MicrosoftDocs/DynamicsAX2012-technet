---
title: Grant users access to cubes
TOCTitle: Grant users access to cubes
ms:assetid: dd6bba5a-22d8-4bf0-9355-bee63b45818b
ms:mtpsurl: https://technet.microsoft.com/library/Aa570082(v=AX.60)
ms:contentKeyID: 35133093
author: Khairunj
ms.date: 06/03/2014
mtps_version: v=AX.60
---

# Grant users access to cubes 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Security for analysis cubes is set up independently from security for Microsoft Dynamics AX. To grant users access to cubes, you must assign the users to database roles in Microsoft SQL Server Analysis Services.

When you deploy the cubes that are included with Microsoft Dynamics AX, default roles are created in the database where you deploy the cubes. The following procedures explain how you can assign users to these default roles.


> [!IMPORTANT]
> <P>Keep the following information in mind when assigning users to roles in Analysis Services:</P>
> <UL>
> <LI>
> <P>Role members have permission to view all data in the cubes that the role has access to. For example, if you assign a user to the <STRONG>Project supervisor</STRONG> role, that user will have access to all data in the Project accounting cube.</P>
> <LI>
> <P>The default roles that are created in Analysis Services are not synchronized with the security roles in Microsoft Dynamics AX. For example, if you modify the permissions of the <STRONG>Accountant</STRONG> role in Microsoft Dynamics AX, it does not affect the <STRONG>Accountant</STRONG> role in Analysis Services.</P></LI></UL>



## Assign users to a database role

Complete the following procedure to assign users to a database role.

1.  In SQL Server Management Studio, connect to your Analysis Services instance.

2.  In the tree view, expand the **Databases** \> **\[Database Name\]** \> **Roles** node.

3.  Right-click the appropriate role, and then click **Properties**. The **Edit Role – \[Role Name\]** form is displayed.

4.  In the **Select a page** area, click **Membership**.

5.  Click **Add**. The **Select Users or Groups** form is displayed.

6.  Add the appropriate Active Directory users or user groups to this role.
    
      - To add an Active Directory user to the role, enter the user’s name in the following format: \[DomainName\]\\\[UserName\]. Click **OK**.
    
      - To add an Active Directory group to the role, complete the following steps:
        
        1.  Click **Object Types**.
        
        2.  In the **Object Types** form, select the **Groups** check box. Click **OK**.
        
        3.  The **Select Users or Groups** form is redisplayed. Enter the name of the user group in the following format: \[DomainName\]\\\[UserGroupName\]. Click **OK**.
    

    > [!NOTE]
    > <P>Analysis Services supports Windows authentication only. Users who do not have Active Directory accounts will not be able to access cube data. This means that users who access Enterprise Portal for Microsoft Dynamics AX using claims-based authentication will not be able to view cube data in reports and web parts.</P>
    > <P>If you configure Enterprise Portal to use claims-based authentication, you should remove the reports and web parts that were designed to display cube data. For more information about using claims-based authentication with Enterprise Portal, see <A href="flexible-authentication-in-microsoft-dynamics-ax-2012.md">Flexible Authentication in Microsoft Dynamics AX 2012</A>.</P>



## Specify which cubes a database role has access to

Complete the following procedure to specify which cubes a database role has access to. To see a list of the cubes each role has access to by default, see [Default Analysis Services roles](default-analysis-services-roles.md).

1.  In SQL Server Management Studio, connect to your Analysis Services instance.

2.  In the tree view, expand the **Databases** \> **\[Database Name\]** \> **Roles** node.

3.  Right-click the appropriate role, and then click **Properties**. The **Edit Role – \[Role Name\]** form is displayed.

4.  In the **Select a page** area, click **Cubes**. A list of the cubes that are contained in the database is displayed.

5.  In the **Access** column, specify the type of access that you want the selected role to have for each cube. You can select **None**, **Read**, or **Read/Write**.

6.  Click **OK**.

  


