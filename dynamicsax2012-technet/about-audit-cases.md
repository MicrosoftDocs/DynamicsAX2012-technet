---
title: About audit cases
TOCTitle: About audit cases
ms:assetid: 9fd6aac1-f9d9-4025-a4d2-6c273d5684a7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh271615(v=AX.60)
ms:contentKeyID: 36384247
ms.date: 05/01/2014
mtps_version: v=AX.60
f1_keywords:
- audit policy
- audit
- audit case
- audit policy violation
- audit violation
- violation
---

# About audit cases [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Audit cases** page to view and filter the list of audit cases, or to export audit case data to Microsoft Excel. Each audit case is a group of related audit policy violations.

## How audit cases are generated

Audit policies are sets of defined business rules that are used to identify expense reports, purchase orders, and vendor invoices that do not comply with the requirements of a particular organization.

Each audit policy rule includes criteria to define a policy violation. The rule is used to evaluate a set of documents and select those documents that match the specified criteria. For example, one policy rule might select expense reports that have meals that exceed 50.00. Another policy rule might select vendor invoices that are payable to a particular vendor.

For each document that is selected, a violation is created. That violation is a record that a particular document, such as invoice 12345, does not comply with the policy rule. Related audit violation records are grouped together and associated with audit cases.

After the audit cases have been generated, they are handled using the typical processes for case management.

Audit cases can also be created manually. For more information, see [Create, modify, or delete a case](create-modify-or-delete-a-case.md).

## Troubleshoot audit cases

## No audit cases are displayed

If no audit cases are displayed, either no audit violations have occurred or audit policies have not been set up.

  - Verify in the Microsoft Dynamics AX client that audit policies have been set up and configured correctly.

  - To determine whether audit violations have occurred, open the **Batch job history** form in the Microsoft Dynamics AX client and view the log file. Any violations that were found will be listed there.

## See also

[Enterprise Portal and Microsoft Excel](enterprise-portal-and-microsoft-excel.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

