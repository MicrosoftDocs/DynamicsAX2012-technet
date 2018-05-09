---
title: Manage data access by using the Table Permissions Framework
TOCTitle: Manage data access by using the Table Permissions Framework
ms:assetid: 101d7291-6637-4519-9859-1b357398939d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh965683(v=AX.60)
ms:contentKeyID: 46331993
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Manage data access by using the Table Permissions Framework 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Table Permissions Framework (TPF) enables administrators to add an additional level of security to tables that store sensitive data.

When the Application Object Server (AOS) attempts to perform an operation on a table that is authorized by TPF, the AOS verifies that members of the user’s role have permission to perform the operation. If members of the role do not have the appropriate permissions, the AOS does not complete the operation.


> [!NOTE]
> <P>TPF can be enabled on any table in the Microsoft Dynamics AX database. However, for the sake of time and efficiency, administrators assign TPF to tables that are considered to be sensitive or to be of critical business value. For information about tables where TPF is enabled by default, see the <A href="table-permissions-framework-reference.md">Table Permissions Framework reference</A>.</P>



## Example

TPF adds table-level security that verifies user rights regardless of the origin of the request. For example, consider the following scenario:

1.  Contoso Corporation implemented Microsoft Dynamics AX. Users access data by using the Microsoft Dynamics AX client, Enterprise Portal, the Application Integration Framework, and a third-party application that connects to Microsoft Dynamics AX by using the .NET Business Connector.

2.  The administrator configured a security role called Senior Leadership, and members of this role have access to sensitive data about financial information and trade secrets. One of the database tables that stores this sensitive information is called FinancialResults. This table was added as part of a customization done by a partner after Microsoft Dynamics AX was installed.

3.  In the Application Object Tree (AOT), the administrator configures the FinancialResults table so that the Application Object Server (AOS) must authorize all operations for that table.

4.  Soon thereafter, a malicious user discovers a vulnerability in Contoso's third-party application that connects to Microsoft Dynamics AX by using the .NET Business Connector. The malicious user connects to the database as a member of the Sales Representative security role and attempts to read the data in the FinancialResults table.

5.  Before allowing the read operation, the AOS verifies that the user is a member of the Senior Leadership security role and that members of the role have permission to read the data. The malicious user is not a member of the Senior Leadership security role. Therefore, the AOS denies the read operation.

## Set authorization requirements on database tables by using the Table Permissions Framework

To enable TPF, the administrator specifies a value for the **AOSAuthorization** property on a specific table in the AOT. By default, this value is set to **None**.

The **AOSAuthorization** property can be used to authorize Create, Read, Update, and Delete operations. For some tables, you might specify a subset of operations, such as Create, Update, and Delete. If you specify a subset, the AOS authorizes the Create, Update, and Delete operations, but allows any Microsoft Dynamics AX users to perform View operations. For other tables, you should authorize all operations because the data is sensitive.

When the **AOSAuthorization** property is set for a table, table methods that cause the AOS to verify permissions are invoked on each affected table row. For more information, see [AOSAuthorization Property on Tables](https://technet.microsoft.com/en-us/library/bb278259\(v=ax.60\)).

Use the following procedure to enable TPF on database table.

1.  In the AOT, expand **Data Dictionary** \> **Tables**.

2.  Select a table. The properties for the table are displayed in the right pane.

3.  Click the **AOSAuthorization** property and select a new value by using the drop-down list.

4.  Click **Save All**.

## Ensure that security roles can access data in a TPF-protected table

If you enabled TPF for a table, you might have to specify or expand permissions for roles that require access to the table.

If a table uses TPF, and the security role does not have explicit access to the table, the user may see the following message: “User \<UserName\> is not authorized to update a record in table \<TableName\>. Request denied. Access Denied: You do not have sufficient authorization to modify data in database.”

Use the following procedure to determine which roles require access to the table.

1.  In the AOT, expand **Data Dictionary** \> **Tables**.

2.  Right-click a table, and then click **Add-ins** \> **Security tools** \> **View related security roles**. The **Roles related to table** form is displayed. This form shows all security roles that access the selected table and the privileges that the table is included in.

Use the **Override permissions** form to grant the role access to the TPF-protected table. For more information, see [Create or modify a security role](create-or-modify-a-security-role.md).

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

