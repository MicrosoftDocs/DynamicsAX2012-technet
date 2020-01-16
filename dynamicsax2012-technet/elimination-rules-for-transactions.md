---
title: Elimination rules for transactions
TOCTitle: Elimination rules for transactions
ms:assetid: 0e14c0d5-fa26-49fe-bad6-c4ec5b7101ab
ms:mtpsurl: https://technet.microsoft.com/library/Gg230910(v=AX.60)
ms:contentKeyID: 37820197
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- transactions
- elimination
- elimination transactions
- elimination rules
audience: Application User
ms.search.region: Global
---

# Elimination rules for transactions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Elimination transactions are required when a parent legal entity does business with one or more subsidiary legal entities and uses consolidated financial reporting. Transactions that occur between legal entities that are part of the same organization must be eliminated, because consolidated financial statements must include only transactions between the consolidated organization and other entities outside that organization. Therefore, transactions between legal entities that are in the same organization must be removed, or eliminated, from the general ledger so that they do not appear on financial reports.


> [!NOTE]
> <P>We recommend that you use Management Reporter for Microsoft Dynamics ERP to combine the financial results for multiple legal entities in a consolidated format. Management Reporter lets you create consolidated financial reports across legal entities, use Microsoft Excel to import consolidation data from other sources, and translate amounts into any number of reporting currencies without having to run the consolidation process in Microsoft Dynamics AX.</P>
> <P>For more information about how to consolidate transactions by using Management Reporter, see <A href="https://go.microsoft.com/fwlink/?linkid=389548">Financial consolidations and currency translation</A>.</P>



You can set up elimination rules to create elimination transactions in a legal entity that is specified as the destination legal entity for eliminations. This destination legal entity is known as the elimination legal entity. Elimination journals can be generated either during the consolidation process or by using an elimination journal proposal.

Before you set up elimination rules, you should become familiar with the following terms:

  - Source legal entity – The legal entity where the amounts that are being eliminated were posted.

  - Destination legal entity – The legal entity where elimination rules are posted.

  - Elimination legal entity – The legal entity that is specified as the destination legal entity for eliminations.

  - Consolidated legal entity – The legal entity that is created to report financial results for a group of legal entities. The financial data from the legal entities is consolidated into this legal entity, and then a financial report is created by using the combined data.

The following table shows the types of transactions that might have to be eliminated.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Transaction type</p></th>
<th><p>Example</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Sales order entry and invoicing (centralized processing)</p></td>
<td><ul>
<li><p>You sell a product to a customer on behalf of another legal entity in your organization.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Sales order entry (intercompany/intracompany) and invoicing</p></td>
<td><ul>
<li><p>You sell products between legal entities in your organization.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Purchase orders (centralized processing)</p></td>
<td><ul>
<li><p>You purchase inventory, supplies, services, fixed assets, and other products from a vendor on behalf of another legal entity in your organization.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Inventory management (intercompany/intracompany)</p></td>
<td><ul>
<li><p>You transfer one legal entity’s inventory to the fixed assets of another legal entity in your organization.</p></li>
<li><p>You transfer one legal entity’s inventory to the inventory of another legal entity in your organization.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>In-transit inventory tracking</p></td>
<td><ul>
<li><p>You transfer items between warehouses in the same legal entity, but across different geographical sites.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Accounts payable centralized invoice processing</p></td>
<td><ul>
<li><p>You record an invoice on behalf of another legal entity in your organization.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Accounts payable centralized payment processing</p></td>
<td><ul>
<li><p>You pay an invoice on behalf of another legal entity in your organization.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Cash management and treasury (centralized processing)</p></td>
<td><ul>
<li><p>You process tax payments, tax refunds, interest charges, loans, advances, dividend payments, and prepaid royalties or commissions.</p></li>
<li><p>You pay an expense on behalf of another legal entity in your organization. The invoice is entered in the destination legal entity’s books, and you must cross-settle between legal entities. For example, one legal entity pays the expense report of an employee in another legal entity. In this case, the employee’s expense report has expenses that are related to another legal entity.</p></li>
<li><p>You transfer cash from one legal entity to another in your organization.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Accounts receivable (centralized processing)</p></td>
<td><ul>
<li><p>You receive cash for another legal entity’s customer invoice, and you deposit the check into that legal entity’s bank account.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Payroll (centralized processing, intercompany/intracompany)</p></td>
<td><ul>
<li><p>You pay another legal entity’s payroll. For example, a legal entity pays its own payroll for its employees, but charges back work that an employee did for another legal entity during that pay run. Or, an employee worked half-time for legal entity A and half-time for legal entity B, and the benefits are across all pay. In these cases, the employee’s pay includes pay from both legal entities. Not only are the salaries posted, but taxes, benefits, deductions, and accruals for salaries are also posted.</p></li>
<li><p>You transfer labor from one department or division to another.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Fixed assets (intercompany/intracompany)</p></td>
<td><ul>
<li><p>You transfer fixed assets to another legal entity’s fixed assets or inventory.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Allocations (intercompany/intracompany)</p></td>
<td><ul>
<li><p>You process corporate allocations. Allocations are activities to any account that is allocated, regardless of the originating module.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Example

Your legal entity, legal entity A, sells widgets to another legal entity in your organization, legal entity B. The following example shows how transactions that occur between the two legal entities might have to be eliminated:

  - Legal entity A sells a widget that costs 10.00 to legal entity B for 10.00.

  - Legal entity A sells a widget that costs 10.00 to legal entity B for 10.00, plus 2.00 in actual shipping costs.

  - Legal entity A sells a widget that costs 10.00 to legal entity B for 15.00 and recognizes a margin on the sale.

  - Legal entity A sells a widget that costs 10.00 to legal entity B for 15.00 and recognizes half of the margin on the sale. Legal entity B recognizes the other half of the margin on the sale. As a result, the revenue is split. Split revenue provides an incentive to order from another legal entity in the organization instead of from an external organization.

All these transactions create intercompany transactions that are posted to due-to and due-from accounts. In addition, these transactions might include markup and markdown amounts when the amount of the intercompany sale is not equal to the cost of the goods that were sold.

## See also

[Set up elimination rules for transactions](set-up-elimination-rules-for-transactions.md)

[Process elimination transactions using the Consolidation, Online form](process-elimination-transactions-using-the-consolidation-online-form.md)

[Process elimination transactions using the Elimination proposal form](process-elimination-transactions-using-the-elimination-proposal-form.md)

  


