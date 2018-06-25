---
title: About audit policy violations and cases
TOCTitle: About audit policy violations and cases
ms:assetid: c8745a77-0733-4a13-952a-d4a95ddcd9a2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242849(v=AX.60)
ms:contentKeyID: 36059319
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- audit policy
- audit
- policy rule violation
- policy violation
- audit case
- audit policy violation
- policy case
- audit violation
---

# About audit policy violations and cases [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Audit policies are used to identify expense reports, purchase orders, and vendor invoices that do not comply with business rules that you define and configure as audit policy rules.

## How audit cases are generated

Audit policies are run in batch mode. When you run an audit policy, all the policy rules that are part of that policy are run at the same time.

Each policy rule evaluates a set of documents and selects those that are in the document selection date range and that match the specified criteria. For example, one policy rule might select expense reports that have meals that exceed 50.00. Another policy rule might select vendor invoices that are payable to a particular vendor.

For each document in the set that is selected, a violation is generated. That violation is a record that a particular document, such as invoice 12345, does not comply with the policy rule.

Multiple audit violation records are grouped together and associated with audit cases. By default, cases for each audit policy are grouped by the audit policy rule. If you prefer, you can select other criteria for grouping using the **Case grouping criteria** form. You could, for example, group expense headers by project ID and vendor invoices by vendor account. If you were to do this, all expense header violations that have the same project ID would be grouped in the same case, and all vendor invoices that have the same vendor account would be grouped in the same case.


> [!NOTE]
> <P>For audit policy rules that are based on a <STRONG>Duplicate</STRONG> query type, violations are not grouped by policy rule or by the criteria specified on the <STRONG>Case grouping criteria</STRONG> form. Instead, they are grouped by the criteria that are built into the audit policy rule. For example, if a policy rule evaluates expense reports for duplicate expenses of the same amount, merchant ID, and date, all expenses that have the same values in those fields would be one case. If other expenses had different values, those would be a separate case.</P>



After the audit cases have been generated, they are handled using the typical processes for case management.

## Document selection date ranges

When the policy is run, each policy rule selects documents of the specified type that have a date that is in the document selection date range. The document selection date range is specified in the **Additional options** form. Many documents have more than one date associated with them. The date field that is used by the audit policy rule is specified in the **Policy rule type** form.

The document selection date range has additional functions for an audit policy.

  - The policy uses the version of each policy rule that is effective on the last day of the document selection date range. Effective dates for each policy rule can be seen on the **Audit policies** list page. (Click **Compliance and internal controls** \> **Common** \> **Policies** \> **Audit policies**.)

  - The policy uses the organization nodes that are associated with the policy on the last day of the document selection date range. Only the organization nodes that are currently associated with the policy are displayed on the **Audit policies** list page. (Click **Compliance and internal controls** \> **Common** \> **Policies** \> **Audit policies**.)

  - For policy rules that are based on a **List search** query type, the policy evaluates documents for monitored entities that are effective on the last day of the document selection date range.

## See also

[Key tasks: Audit policies](key-tasks-audit-policies.md)

[About audit policy rules](about-audit-policy-rules.md)

[Case management](case-management.md)

[Case grouping criteria (form)](https://technet.microsoft.com/en-us/library/hh209729\(v=ax.60\))

[Additional options (form)](https://technet.microsoft.com/en-us/library/hh227519\(v=ax.60\))

[Policy rule type (form)](https://technet.microsoft.com/en-us/library/hh208562\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

