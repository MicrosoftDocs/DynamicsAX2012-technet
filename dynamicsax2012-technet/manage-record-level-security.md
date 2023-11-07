---
title: Manage record level security
TOCTitle: Manage record level security
ms:assetid: ddbe0898-8504-4203-8aa0-f2821aa7cd60
ms:mtpsurl: https://technet.microsoft.com/library/Aa570084(v=AX.60)
ms:contentKeyID: 39555417
author: tonyafehr
ms.date: 05/02/2014
mtps_version: v=AX.60
description: Learn how to manage record-level security in Microsoft Dynamics AX 2012. Understand role-based restrictions, data security policies, and setup process.
---

# Manage record level security 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Record-level security builds on the restrictions enforced by role-based security. By using role-based security, you restrict the menus, forms, and reports that role members can access. By using record level security to set restrictions on specific records or tables in the database, you can restrict the data that is shown in reports and on forms.


> [!NOTE]
> <P>The record-level security feature will be removed in a future release. If you previously set up record-level security filters, they will continue to function. If you are setting up new filters, we recommend that you create data security policies using the extensible data security framework. For more information about data security policies, see <A href="https://technet.microsoft.com/library/hh272123(v=ax.60)">Overview of Security Policies for Table Records</A>.</P>



The following examples demonstrate how you can use record-level security.

  - Allow members of a Sales role to see only the accounts they manage.

  - Prohibit financial data from appearing on forms or reports for a specific role.

  - Prohibit account details or account IDs from appearing on forms and reports for a specific role.

  - Restrict form and report data according to location or country/region.

When a record-level security policy and a data security policy filter the same data, they may not work together as expected. For example, if the constrained table in the data security policy differs from the primary table in the record-level security filter, the existing record-level security policy is not added to the data security policy query. To achieve the desired behavior, you must add the ranges from the record-level security policy to the data security policy query.

## Before you set up record-level security

The process of setting record-level security involves selecting a database table in the Record Level Security Wizard. Tables store the data shown in reports and on forms. You might find it helpful to work with a developer who has knowledge of the database tables when configuring record-level security. The developer can help you select the table that directly corresponds to the report or form elements to which you want to restrict access.

Also, verify the following before you begin:

  - Determine whether the role that will be assigned record-level security already exists. For information about how to create a new role, see [Create or modify a security role](create-or-modify-a-security-role.md).

  - Determine whether the role has permission to the report or form. If, for example, the Project accountant role does not have access to the General ledger module, then it does not make sense to assign record level security to tables in that module. For information about role permissions, see [Create or modify a security role](create-or-modify-a-security-role.md).

## Set up record-level security

Setting up record-level security is a two-part process. First, you must select a role and a database table by using the Record Level Security Wizard. Next, you must create a query that specifies the fields to filter on and the criteria to be applied.

## Use the Record Level Security Wizard

1.  Click **System administration** \> **Setup** \> **Security** \> **Record level security**.

2.  Press CTRL + N to open the **Record level security** wizard.

3.  Select the role for which you want to create a filter, and then click **Next \>**.

4.  Select the table to filter. By default, the main database tables are shown. Click **Show all tables** to expand the selection.
    

    > [!IMPORTANT]
    > <P>You cannot use record-level security filters on the tables in an inheritance hierarchy. For example, the DirPerson and DirOrganizationBase tables inherit from the DirPartyTable table. Record-level security filters cannot be used on any one of these tables.</P>

    
    Click **Next \>**.

5.  Click **Finish**.

## Create a query

1.  In the **Record level security** dialog box, select the role and table association that you just created and then click **Query**. The **Inquiry** dialog box is displayed.

2.  Select the first item listed on the **Range** tab. If no item is listed, press CTRL + N.

3.  In the **Field** list, select the field that you want to filter on.

4.  In the **Criteria** field, enter or select the filter criteria for the designated field.

5.  As necessary, press CTRL + N to add fields and criteria.

6.  Click **OK**.

7.  Inform members of the selected role that they must close their current client sessions and start a new session. If it is necessary, end active sessions from the **Online users** form. For information about how to end active sessions, see [Monitor users](monitor-users.md).

8.  Verify that record-level security is enforced on the report or form by logging on to Microsoft Dynamics AX as a member of the specified role. You should see only the information specified in the query for the designated criteria. If you see additional information, troubleshoot the query.

## Range filters on surrogate foreign keys

If you must specify a range filter on a column that is a surrogate foreign key, we recommend that you use data security policies instead of record-level security. For more information about data security policies, see [Overview of Security Policies for Table Records](https://technet.microsoft.com/library/hh272123\(v=ax.60\)).

A surrogate foreign key is a column in one table that retrieves its values from, or is joined to, a column in another table. Because it is a surrogate key, its value has no meaning to people and is used only to identify a record in the table. A large number generated by the system, such as RecId, could be a surrogate key.

In the **Advanced Filter** form, a range filter on a surrogate foreign key is applied to the table that is referenced by the foreign key. However, in record-level security, a range filter must be applied to the current table. This means that record-level security will treat a range filter on a surrogate foreign key as an invalid range.

  


