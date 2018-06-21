---
title: 'Examples: Project contract funding'
TOCTitle: 'Examples: Project contract funding'
ms:assetid: 6eb89b24-46e9-4ca4-b951-81cafbb6517b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh771576(v=AX.60)
ms:contentKeyID: 43881149
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Examples: Project contract funding [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If you assign multiple funding sources to a project, you can control the portion of the contract value that each source is responsible for by assigning an allocation percentage to each funding source. Additionally, you can control the order in which costs are allocated to each funding source by assigning an allocation priority to each funding source.


> [!NOTE]
> <P>For information about how priority settings affect how funds are allocated for a project, see <A href="configure-funding-allocation-priorities.md">Configure funding allocation priorities</A>.</P>



## Simple multiple funding source examples

The following table provides scenarios for managing funding allocation among multiple funding sources. These scenarios are based on the following assumptions:

  - Priority settings are factored into the allocation of funds before other funding rule criteria are applied.

  - No date range has been specified for when the funding rule is in effect.


> [!NOTE]
> <P>In the <STRONG>Project management and accounting parameters</STRONG> form, you can specify the order in which funding rule criteria are weighed when the system determines where funds should be allocated first. For more information about the priority criteria in funding rules, see <A href="set-up-funding-rules-for-a-project-contract.md">Set up funding rules for a project contract</A>.</P>



<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Scenario</p></th>
<th><p>Funding source</p></th>
<th><p>Allocation percentage</p></th>
<th><p>Allocation priority</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>You want to allocate costs to one funding source until its funds are exhausted, allocate costs to a second funding source until its funds are exhausted, and finally allocate the remaining costs to a third funding source.</p></td>
<td><ul>
<li><p>Funding source 1</p></li>
<li><p>Funding source 2</p></li>
<li><p>Funding source 3</p></li>
</ul></td>
<td><ul>
<li><p>100%</p></li>
<li><p>100%</p></li>
<li><p>100%</p></li>
</ul></td>
<td><ul>
<li><p>1</p></li>
<li><p>2</p></li>
<li><p>3</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>You want to allocate 75 percent of costs to one funding source and 25 percent to a second funding source. When either of those funding sources is exhausted, you want to pay the remaining costs from a third funding source.</p></td>
<td><ul>
<li><p>Funding source 1 </p></li>
<li><p>Funding source 2</p></li>
<li><p>Funding source 3</p></li>
</ul></td>
<td><ul>
<li><p>75%</p></li>
<li><p>25%</p></li>
<li><p>100%</p></li>
</ul></td>
<td><ul>
<li><p>1</p></li>
<li><p>1</p></li>
<li><p>2</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>You want to allocate 75 percent of costs to one funding source and 25 percent to a second funding source. When either funding source is exhausted, you want to split the remaining costs between a third and fourth funding source.</p></td>
<td><ul>
<li><p>Funding source 1</p></li>
<li><p>Funding source 2</p></li>
<li><p>Funding source 3</p></li>
<li><p>Funding source 4</p></li>
</ul></td>
<td><ul>
<li><p>75%</p></li>
<li><p>25%</p></li>
<li><p>50%</p></li>
<li><p>50%</p></li>
</ul></td>
<td><ul>
<li><p>1</p></li>
<li><p>1</p></li>
<li><p>2</p></li>
<li><p>2</p></li>
</ul>
<p></p></td>
</tr>
<tr class="even">
<td><p>You want to allocate the first 25 percent of costs to one funding source and the rest to another.</p></td>
<td><ul>
<li><p>Funding source 1</p></li>
<li><p>Funding source 2</p></li>
</ul></td>
<td><ul>
<li><p>25%</p></li>
<li><p>100%</p></li>
</ul></td>
<td><ul>
<li><p>1</p></li>
<li><p>2</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Complex multiple funding source example

You have three funding sources, and you want to use them in the following order:

1.  Use funding source 2 and funding source 3 equally until funding source 2 is exhausted.

2.  Continue to use funding source 3 until it is exhausted.

3.  Use funding source 1 after funding source 3 is exhausted.

To accomplish this goal, you do the following:

1.  Set up funding limits for funding source 2 and funding source 3 for their respective amounts.

2.  Create the following funding rules:
    
      - Rule 1: Allocate 50 percent of transactions to funding source 2 and 50 percent to funding source 3.
    
      - Rule 2: Allocate 100 percent of transactions to funding source 3.
    
      - Rule 3: Allocate 100 percent of transactions to funding source 1.

This setup works because transactions are checked against rules and limits to see whether any of them apply to the transaction. If no specific rules or limits apply to the transaction, the All transactions rule applies. The All transactions rule matches all transactions.

If the system finds a rule that matches a transaction specifically, the percentage that has been allocated in that rule is applied first, but only after the matches are checked against any limits that have been set up. If a limit has been met, and a funding source’s funds are exhausted, the funding rule that is associated with the funding limit is disregarded, and the system checks for the next rule that applies.

In some cases, only part of a transaction can be allocated under a rule. This might happen because a limit is reached when the transaction is allocated. In this case, only a certain amount is allocated according to that rule, such as 50 percent to each funding source. This is the case in rule 1, described earlier in this section. The remainder is allocated according to the next rule in line.

The following table examines this scenario in more detail.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Focus</p></th>
<th><p>Details</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Funding rules</p></td>
<td><ul>
<li><p>Rule 1: All transactions. Allocate funding source 2 at 50% and funding source 3 at 50%.</p></li>
<li><p>Rule 2: All transactions. Allocate funding source 3 at 100%.</p></li>
<li><p>Rule 3: All transactions. Allocate funding source 1 at 100%.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Funding limits</p></td>
<td><ul>
<li><p>Funding source 1 limit = 10,000.00</p></li>
<li><p>Funding source 2 limit = 500.00</p></li>
<li><p>Funding source 3 limit = 750.00</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Transaction 1</p></td>
<td><p><strong>Transaction amount:</strong> 100.00</p>
<p><strong>Funding:</strong> The transaction is paid according to rule 1 only. This is because the transaction is fully paid after rule 1 is applied. The transaction is funded equally between funding source 2 and funding source 3.</p>
<ul>
<li><p>Funding source 2: 50.00</p></li>
<li><p>Funding source 3: 50.00</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Transaction 2</p></td>
<td><p><strong>Transaction amount:</strong> 5,000.00</p>
<p><strong>Funding:</strong> The transaction is paid according to all three rules.</p>
<p><strong>Rule 1</strong></p>
<ul>
<li><p>Funding source 2: 450.00</p></li>
<li><p>Funding source 3: 450.00</p></li>
</ul>
<p><strong>Rule 2</strong></p>
<ul>
<li><p>Funding source 3: 250.00</p>
<p>(750.00 – 50.00 – 450.00 = 250.00)</p></li>
</ul>
<p><strong>Rule 3</strong></p>
<ul>
<li><p>Funding source 1: 3,850.00</p>
<p>(5000.00 – 450.00 – 450.00 – 250.00 = 3,850.00)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Total funds that are distributed for each funding source</p></td>
<td><ul>
<li><p>Funding source 1: 3,850.00</p></li>
<li><p>Funding source 2: 500.00</p></li>
<li><p>Funding source 3: 750.00</p></li>
</ul></td>
</tr>
</tbody>
</table>


## See also

[Project contracts (form)](https://technet.microsoft.com/en-us/library/aa586038\(v=ax.60\))

[Set up funding limits for funding sources in a project contract](set-up-funding-limits-for-funding-sources-in-a-project-contract.md)

[Assign funding sources to a project contract](assign-funding-sources-to-a-project-contract.md)

[Set up funding rules for a project contract](set-up-funding-rules-for-a-project-contract.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

