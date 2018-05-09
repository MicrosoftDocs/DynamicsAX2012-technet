---
title: (IND) Post sales transactions with multiple taxes and charges
TOCTitle: (IND) Post sales transactions with multiple taxes and charges
ms:assetid: 77d34a86-b7c3-4baf-8672-1508c88723e6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677916(v=AX.60)
ms:contentKeyID: 49385870
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) Post sales transactions with multiple taxes and charges 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



You can post a purchase transaction or sales transactions with multiple taxes and charges. Indirect taxes, such as sales tax, service tax, VAT, and customs are levied, along with excise for a particular transaction.

The following are examples of combinations of multiple taxes:

  - Excise + VAT

  - Excise + Sales tax

The combination of the multiple taxes that are levied is in accordance with the Indian legal requirement. However, in Microsoft Dynamics AX, you can post multiple taxes with all combinations.

**Example**

The following is an example of a sales transaction when multiple taxes, excise, and VAT are levied.

A sales order line is created for an item. Two taxes, excise and VAT, are levied on the item. The sales order line amount is INR 10,000. Miscellaneous charge code is set up for freight for INR 1000 with the account combination of Ledger (Debit) – Ledger (Credit) in the **Misc. charges code** form, and attached to the sales order line. The record type selected on the **Tax information** tab is RG23A.

The formula for the calculation of excise is defined in the **Formula designer** form as shown in the following table.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Tax code/component</p></th>
<th><p>Taxable basis</p></th>
<th><p>Calculation expression</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>BED</p></td>
<td><p>Assessable value</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>AED</p></td>
<td><p>Assessable value</p></td>
<td><p>+[BED]</p></td>
</tr>
<tr class="odd">
<td><p>SED</p></td>
<td><p>Assessable value</p></td>
<td><p>+[BED]</p></td>
</tr>
<tr class="even">
<td><p>E-Cess</p></td>
<td><p>Excl. line amount</p></td>
<td><p>+[SED]</p></td>
</tr>
<tr class="odd">
<td><p>SHE-cess</p></td>
<td><p>Excl. line amount</p></td>
<td><p>+[SED]</p></td>
</tr>
<tr class="even">
<td><p>VAT</p></td>
<td><p>Line amount</p></td>
<td><p>+[BED]+ [AED] + [SED] + [E-cess] + [SHE cess]</p></td>
</tr>
</tbody>
</table>


The excise rate percentage for BED is 10 percent, AED is 5 percent, SED is 2 percent, E-Cess is 1 percent, SHE-cess is 1 percent, and VAT is 4 percent. The sales order is posted.

According to the example, the following types of excise and VAT are calculated.

Net amount + Miscellaneous charges = Assessable value

10,000 + 1000 = 11,000.00

BED = (11,000 \* 10%) = 1100.00

AED = \[(11,000 + 1100) \* 5%\] = 605.00

SED = \[(11,000 + 1100) \* 2%\] = 242.00

E-cess = (242.00 \* 1%) = 2.42

SHE-cess = (242.00 \* 1%) = 2.42

VAT = \[(10,000 + 1100 + 605 + 242 + 2.42 + 2.42) \* 4%\] = INR 478.07

The amount origin and the tax amounts calculated are displayed in the **Temporary sales tax transactions** form.

When the sales order is posted, the payable accounts of the tax components are credited with the related excise taxes and the VAT payable account is credited with the VAT amount. The RG23A Part I register is updated.

## See also

[(IND) Formula designer (form)](https://technet.microsoft.com/en-us/library/jj677983\(v=ax.60\))

[(IND) Temporary sales tax transactions (modified form)](https://technet.microsoft.com/en-us/library/jj664487\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

