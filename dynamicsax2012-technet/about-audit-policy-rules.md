---
title: About audit policy rules
TOCTitle: About audit policy rules
ms:assetid: 27b4fb10-283b-4dcb-8a72-5085826fbe1c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208490(v=AX.60)
ms:contentKeyID: 36056213
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- audit
- audit policy rules
- policy rules
- audits
---

# About audit policy rules 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use audit policies to evaluate expense reports, vendor invoices, and purchase orders to make sure that they comply with policy rules that you create. All of the rules that are associated with an audit policy are run in batch mode, according to a schedule that you specify.

Each policy rule is an instance of a policy rule type. For each policy rule type, only one policy rule can be active at a time.


> [!NOTE]
> <P>This topic includes information about features that were added or changed for cumulative update 6 or later for Microsoft Dynamics AX 2012 R2. This information also applies to AX 2012 R3.</P>



## Queries and query types

When you create an audit policy rule, you first select a policy rule type. The policy rule type specifies the Application Object Tree (AOT) query to use as the starting point for creating the policy rule. It also specifies the query type to use for the policy rule.

The query determines the source document that the policy rule evaluates. It also specifies the fields in the source document that identify both the legal entity and the date to use when documents are selected for audit.

The query type controls the default fields in the query form and in the **Audit policy rule** form.

The following table shows the query types that are available for audit policy rules.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Query type</strong></p></th>
<th><p>Purpose</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Conditional</strong></p></td>
<td><p>Evaluate source document attributes against specified values.</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Aggregate</strong></p></td>
<td><p>Evaluate multiple source documents or source document lines against a policy rule by aggregating numeric values.</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Sampling</strong></p></td>
<td><p>Randomly select a specified percentage of the source documents to evaluate for policy violations.</p></td>
<td><p>When you select this option, use the <strong>Audit policy rule</strong> form to specify the percentage of documents to randomly select for audit.</p></td>
</tr>
<tr class="even">
<td><p><strong>Duplicate</strong></p></td>
<td><p>Evaluate source documents to determine whether they contain duplicate entries in specified fields.</p></td>
<td><p>When you select this option, use the <strong>Audit policy rule</strong> form to specify the number of days to add to the start of the document selection date range when documents are evaluated for duplicate entries.</p></td>
</tr>
<tr class="odd">
<td><p><strong>List search</strong></p></td>
<td><p>Evaluate source documents for specific entities.</p></td>
<td><p>The root document of the query defines the document that is being audited. The query must contain a join with the DirParty table.</p>
<p>This option can be used only with the following AOT queries:</p>
<ul>
<li><p><strong>AuditPolicyExpenseList</strong> (<strong>Expense report monitored employees</strong>)</p></li>
<li><p><strong>AuditPolicyPurchList</strong> (<strong>Purchase order monitored vendors</strong>)</p></li>
<li><p><strong>AuditPolicyVendInvoiceList</strong> (<strong>Vendor invoice monitored vendors</strong>)</p></li>
</ul>
<p>In Microsoft Dynamics AX 2012 or Microsoft Dynamics AX 2012 R2:</p>
<p>When you select this option, specify the monitored entities in the <strong>Additional options</strong> form before you create the policy rule.</p>
<p>In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2:</p>
<p>When you select this option, specify the monitored entities in the <strong>Audit policy rule</strong> form.</p></td>
</tr>
<tr class="even">
<td><p><strong>Keyword search</strong></p></td>
<td><p>Evaluate source documents to determine whether they contain certain words.</p></td>
<td><p>In Microsoft Dynamics AX 2012 or Microsoft Dynamics AX 2012 R2:</p>
<p>When you select this option, enter the words to look for in the <strong>Additional options</strong> form before you create the policy rule. The <strong>Audit policy rule</strong> form also includes options that let you specify the tables and fields to evaluate for the words you entered.</p>
<p>In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2:</p>
<p>When you select this option, enter the words to look for in the <strong>Audit policy rule</strong> form. The <strong>Audit policy rule</strong> form also includes options that let you specify the tables and fields to evaluate for the words you entered.</p></td>
</tr>
</tbody>
</table>


For more information about queries for audit policy rules, see [Policy rule type (form)](https://technet.microsoft.com/en-us/library/hh208562\(v=ax.60\)).

## Common parameters

All of the policy rules for a particular audit policy share the same batch parameters and the same document selection date range. These parameters are specified for the policy in the **Additional options** form.

## See also

[Key tasks: Audit policies](key-tasks-audit-policies.md)

[About audit policy violations and cases](about-audit-policy-violations-and-cases.md)

[Audit policy rule (form)](https://technet.microsoft.com/en-us/library/hh209490\(v=ax.60\))

[Policy rule type (form)](https://technet.microsoft.com/en-us/library/hh208562\(v=ax.60\))

[Audit policy rule test result (form)](https://technet.microsoft.com/en-us/library/hh208603\(v=ax.60\))

[Additional options (form)](https://technet.microsoft.com/en-us/library/hh227519\(v=ax.60\))

[Case grouping criteria (form)](https://technet.microsoft.com/en-us/library/hh209729\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

