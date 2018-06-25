---
title: (USA) Applying U.S. sales tax and use tax rules
TOCTitle: (USA) Applying U.S. sales tax and use tax rules
ms:assetid: a261cfd2-5900-4a38-afa7-5a34360939b3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa571829(v=AX.60)
ms:contentKeyID: 36058799
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (USA) Applying U.S. sales tax and use tax rules [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In the U.S., you must pay use tax on purchases if sales tax is not applied. (We recommend that you review IRS rule changes for the applicable tax year for up-to-date information about U.S. tax rules.) To track use taxes as they accrue, set up an appropriate offset account, and then select the offset account in the **Use tax payable** field in the **Ledger posting groups** form.

When you select the **Apply U.S. taxation rules** check box on the **Sales tax** tab in the **General ledger parameters** form, any sales or use taxes that are posted in a ledger account that is used for expenditures is recorded.

## Example: recording use tax

In the **General ledger parameters** form, select the **Apply U.S. taxation rules** check box.

Assume that you order office supplies over the Internet. You receive an invoice for USD 500, which does not include the 6 percent sales tax that is applicable in the state where the goods will be used. When you enter the vendor invoice, enter a USD 500 credit for the vendor account and a USD 30 credit for the use tax payable account, for a total USD 530 debit for the Office supplies expense account.

The following table displays how the amounts are posted.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Ledger account</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Vendor account</p></td>
<td><p>–</p></td>
<td><p>500.00</p></td>
</tr>
<tr class="even">
<td><p>Use tax payable</p></td>
<td><p>–</p></td>
<td><p>30.00</p></td>
</tr>
<tr class="odd">
<td><p>Office supplies expense</p></td>
<td><p>530.00</p></td>
<td><p>–</p></td>
</tr>
</tbody>
</table>


## Fields that are not available when applying U.S. sales tax and use tax rules

If you select the **Apply U.S. taxation rules** check box in the **General ledger parameters** form, the following fields are not available:

  - **Pct. exempt from sales tax** in the **Values** form (**General ledger parameters** \> **Setup** \> **Sales tax** \> **Sales tax codes** \> **Values**), in which you specify values for sales tax codes.

  - **Sales tax receivable** in the **Ledger posting groups** form (**General ledger parameters** \> **Setup** \> **Sales tax** \> **Ledger posting groups**).

  - **Use tax expense** in the **Ledger posting groups** form.

  - **Reverse sales tax on cash discount** in the **General ledger parameters** form.

  - **Sales tax on overpayment or underpayment** in the **General ledger parameters** form.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

