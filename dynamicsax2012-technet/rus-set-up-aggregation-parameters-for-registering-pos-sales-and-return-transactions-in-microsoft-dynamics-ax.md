---
title: (RUS) Set up aggregation parameters for registering POS sales and return transactions in Microsoft Dynamics AX
TOCTitle: (RUS) Set up aggregation parameters for registering POS sales and return transactions in Microsoft Dynamics AX
ms:assetid: 0130aa5a-d725-45a8-83f3-f0f11b82b98b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn716015(v=AX.60)
ms:contentKeyID: 62200258
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.RetailParameters
- MsDynAx060.Forms.RetailParameters
---

# (RUS) Set up aggregation parameters for registering POS sales and return transactions in Microsoft Dynamics AX 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can set up the aggregation parameters that are used to aggregate the point of sale (POS) sales and return transactions when the transactions are registered in Microsoft Dynamics AX. When you select the aggregation parameters, Microsoft Dynamics AX registers sales orders for the POS sales and return transactions in the following ways:

  - When you perform sales transactions and return transactions in the same shift, Microsoft Dynamics AX aggregates the positive sales quantities and negative return quantities for items that have identical inventory dimensions.

  - When you perform sales transactions and return transactions in different shifts, Microsoft Dynamics AX registers the positive sales quantities and negative return quantities for items that have identical inventory dimensions separately.

## Example

You perform the following transactions at the POS:

  - Five sales transactions for two units of item A each, generating five sales receipts.

  - Two return transactions for two original receipts that contain one unit of item A each, generating two return receipts in the same shift.

  - Three return transactions for one unit of item A each, generating three receipts in a different shift.

  - One return transaction for one unit of item A without generating a receipt in a different shift.

The following table displays how the transactions are registered in Microsoft Dynamics AX depending on the parameters that you select in the **Retail parameters** form.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p></p></th>
<th><p><strong>Process as a return in the same shift</strong></p></th>
<th><p><strong>Voucher transactions</strong> in the <strong>Aggregation</strong> field group in the <strong>Posting</strong> area</p></th>
<th><p><strong>Sales and returns</strong> in the <strong>Aggregation</strong> field group in the <strong>Posting</strong> area</p></th>
<th><p>Transactions created in Microsoft Dynamics AX</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Scenario 1</strong></p></td>
<td><p>Cleared</p></td>
<td><p>Cleared</p></td>
<td><p>Cleared</p></td>
<td><ul>
<li><p>Five sales orders are created for the sales transactions. Each sales order contains one line for two units of item A.</p></li>
<li><p>Six sales orders are created for the return transactions. Each sales order contains one line for one unit of item A.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Scenario 2</strong></p></td>
<td><p>Cleared</p></td>
<td><p>Selected</p></td>
<td><p>Cleared</p></td>
<td><ul>
<li><p>For the first two transactions that were performed in the same shift, a single sales order is created, which contains three lines. The first line contains 10 units of item A and the second and third lines contain -1 unit of item A each.</p></li>
<li><p>For the remaining return transactions that were performed in a different shift, four sales orders that contain one line for -1 unit of item A each are created.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Scenario 3</strong></p></td>
<td><p>Cleared</p></td>
<td><p>Selected</p></td>
<td><p>Selected</p></td>
<td><ul>
<li><p>For the first two transactions that were performed in the same shift, a single sales order is created, which contains one line for eight units of item A (10 -2).</p></li>
<li><p>For the remaining return transactions that were performed in a different shift, four sales orders that contain one line for -1 unit of item A each are created.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Scenario 4</strong></p></td>
<td><p>Selected</p></td>
<td><p>Cleared</p></td>
<td><p>Cleared</p></td>
<td><ul>
<li><p>Five sales orders are created for the sales transaction. Each sales order contains one line for two units of item A.</p></li>
<li><p>Six sales orders are created for the return transactions. Each sales order contains one line for -1 unit of item A.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Scenario 5</strong></p></td>
<td><p>Selected</p></td>
<td><p>Selected</p></td>
<td><p>Cleared</p></td>
<td><p>One sales order is created for all of the sales and return transactions. The sales order contains seven lines: The first line contains 10 units of item A, and the remaining six lines contain -1 unit of item A each.</p></td>
</tr>
<tr class="even">
<td><p><strong>Scenario 6</strong></p></td>
<td><p>Selected</p></td>
<td><p>Selected</p></td>
<td><p>Selected</p></td>
<td><p>One sales order is created for all of the transactions. The sales order contains one line for four units of item A (10 - 2 - 3 - 1).</p></td>
</tr>
</tbody>
</table>


## Set up aggregation parameters

Use this procedure to set up the aggregation parameters that are used to aggregate POS sales and return transactions in Microsoft Dynamics AX.

1.  Click **Retail** \> **Setup** \> **Parameters** \> **Retail parameters**.

2.  Select the **Process as a return in the same shift** check box to process return transactions during a different shift in the same way that you process return transactions during the same shift.

3.  Click **Posting**, and then in the **Posting** area, in the **Aggregation** field group, select the **Voucher transactions** check box to aggregate voucher transactions.

4.  Select the **Sales and returns** check box to aggregate POS sales and return transactions.
    

    > [!NOTE]
    > <P>This check box is available only if you select the <STRONG>Voucher transactions</STRONG> check box.</P>



## See also

[(RUS) Set up Microsoft Dynamics AX to process returns during a different shift](rus-set-up-microsoft-dynamics-ax-to-process-returns-during-a-different-shift.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

