---
title: Virtual company accounts in Microsoft Dynamics AX
TOCTitle: Virtual company accounts in Microsoft Dynamics AX
ms:assetid: 8b4f6374-8ef5-49aa-942a-50d354a192d7
ms:mtpsurl: https://technet.microsoft.com/library/Aa834413(v=AX.60)
ms:contentKeyID: 35132715
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Virtual company accounts in Microsoft Dynamics AX 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you create a virtual company account, you specify a collection of tables that is shared among a group of companies. When users save information in one of those tables, the data is available to the other company accounts in the group.


> [!NOTE]
> <P>A company is a type of legal entity. A company is the only kind of legal entity that you can create, and every legal entity is associated with a company ID.</P>



We recommend that you set up virtual companies when you first implement Microsoft Dynamics AX. If data has already been entered in the tables, data integrity can be affected when you combine records into a shared table later.

We do not recommend that you use virtual company accounts to share anything other than reference data and master data. You must not use virtual company accounts to share transactional data.

This topic includes the following information about virtual company accounts:

  - Company-specific data and shared data

  - Create a table collection

  - Before you create a virtual company account

  - Create a virtual company account

  - Allow non-administrators to create virtual company accounts

  - Delete a virtual company account

## Company-specific data and shared data

Many of the tables in Microsoft Dynamics AX contain data that is company-specific. Company-specific data must be entered separately for each company. By default, users can access data only for the company that they are currently logged on to. To share this data among company accounts but maintain it only one time, you must create virtual company accounts.

Some tables are not company-specific. Therefore, by default, the data is available to all organizations. We recommend that you not include these tables in virtual companies.

Even when tables are shared, number sequences are always maintained for each company account. If you plan to use number sequences to automatically number records that are shared, we recommend that you create the data for the shared table in the company account where the number sequence was set up. Alternatively, make sure that there is no overlap between allocated numbers across the company accounts. Otherwise, numbers that are already used might be assigned again.

Some tables contain fields that are available only when you are logged on to a company account that operates in a particular country/region. When you maintain shared data, remember that the available fields may change, depending on the company that you are logged on to.

## Create a table collection

Before you set up a virtual company account, you must create table collections that include the tables that will be shared in the virtual company account.

A table collection defines a set of tables that have no foreign key relationships with tables outside the table collection. Each table occurs only one time in any one table collection, but tables can be added to more than one table collection. No data is stored in a table collection. Only companies and virtual companies store data.

Consider the following information when you are deciding which tables to include in a table collection:

  - If a table has a foreign key relationship with another table, we recommend that you include the referenced table in the table collection. If you do not include the referenced table in the table collection, you must make sure that data is not entered in the foreign key field. Referential integrity can be affected if business logic that accesses the shared table does not have access to records in the referenced table.

  - If two tables have a composite relationship, both tables must be part of the table collection. If the table that contains the foreign key relationship is not included in the table collection, maintenance of the data differs, depending on the company that you are logged on to. Referential integrity may also be affected, because business logic that accesses the shared table will not have access to records in the table that has been omitted.

  - Adding a table that is not company-specific to a table collection has no effect, because the records in the table are already available to all organizations.

  - The database administrator may need to tune indexes to improve performance, depending on which tables are shared in a virtual company. For more information about how to design indexes, start with [Index Design Basics](https://technet.microsoft.com//library/ms179560\(v=sql.105\).aspx) in the SQL Server documentation.

The following procedure describes how to create table collections by using drag-and-drop operations in the Application Object Tree (AOT).

1.  In the Microsoft Dynamics AX client, press CTRL+SHIFT+W to open a development workspace.

2.  Open two instances of the AOT, and display them side by side.

3.  In one instance of the AOT, expand **AOT** \> **Data Dictionary** \> **Tables**.

4.  In the other instance of the AOT, expand **AOT** \> **Data Dictionary** \> **Table Collections**.

5.  Right-click **Table Collections**, and then click **New Table Collection**.

6.  Right-click the table collection that you just created, and then click **Rename**. Name the new table collection appropriately.

7.  Drag tables into the new table collection.

For information about the table collections that are required to support specific scenarios for virtual companies in Microsoft Dynamics AX, see the following topics:

  - [Virtual company scenarios: Financials](virtual-company-scenarios-financials.md)

  - [Virtual company scenarios: CRM](virtual-company-scenarios-crm.md)

  - [Virtual company scenarios: Supply chain management (SCM)](virtual-company-scenarios-supply-chain-management-scm.md)

  - [Virtual company scenarios: Travel and expense](virtual-company-scenarios-travel-and-expense.md)

  - [Virtual company scenarios: Project management and accounting](virtual-company-scenarios-project-management-and-accounting.md)

  - [Virtual company scenarios: Retail](virtual-company-scenarios-retail.md)

## Before you create a virtual company account

Your system must meet the following requirements before you can create or modify a virtual company:

  - The instance of Application Object Server (AOS) that the administrator is connected to must be the only instance that is running. All other AOS instances must be shut down.

  - Only the administrator who is creating the virtual company account can be connected. Only one active client connection is allowed.

  - If a company account already contains data in company-specific tables, we do not recommend that you associate it with a virtual company. The existing data is not moved to the virtual company. Therefore, data can be corrupted, and you may have to manually update records in the database.

  - If you used virtual companies in a previous release, you can continue to use them. However, before you create new virtual companies to share data, we recommend that you verify whether the data that you want to share is already stored in a shared table. For more information, see [About organizations and organizational hierarchies](about-organizations-and-organizational-hierarchies.md).

## Create a virtual company account

1.  Click **System administration** \> **Setup** \> **Virtual company accounts**.

2.  Click **New** to create a new virtual company account.

3.  In the **Company accounts** field, enter a company ID.

4.  In the **Name of company accounts** field, enter a name for the virtual company.

5.  Click the **Company accounts** tab, and then select the company accounts to include in the virtual company.
    
      - To add a company account, select the company name in the **Remaining company accounts** list, and then click the left arrow button (**\<**) to move the company account to the **Selected company accounts** list.
    
      - To remove a company account, select the company name in the **Selected company accounts** list, and then click the right arrow button (**\>**) to move the company account to the **Remaining company accounts** list.

6.  Click the **Table collections** tab, and then select the tables to share in the virtual company.

7.  After you create or modify a virtual company account, you must restart the Microsoft Dynamics AX client to update the client with information about the new virtual company account.

## Allow non-administrators to create virtual company accounts

The system administrator can grant permission to create virtual company accounts to users who are not administrators.

1.  Assign the user to a role that has the **Maintain virtual company accounts** privilege. By default, the **Information technology manager** role has this privilege. For more information, see [Assign users to security roles](assign-users-to-security-roles.md).

2.  If you assign the user to a role other than **Information technology manager**, use the **Override permissions** form to make sure that the role has **Full control** permissions to the TableCollectionList table and the VirtualDataAreaList table. For more information, see [Create or modify a security role](create-or-modify-a-security-role.md).

3.  Disconnect all other client connections to the AOS instance, and shut down all AOS instances except the instance that is being used to create virtual company accounts. For more information, see [Monitor users](monitor-users.md).

## Delete a virtual company account

When you delete a virtual company, the shared data that is associated with the virtual company is not deleted automatically. This data remains available in cross-company queries. To delete a virtual company, you must remove the associated data from the tables that were shared via the virtual company.

  


