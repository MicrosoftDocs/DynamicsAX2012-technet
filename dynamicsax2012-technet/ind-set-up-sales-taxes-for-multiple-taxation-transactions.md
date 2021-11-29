---
title: (IND) Set up sales taxes for multiple taxation transactions
TOCTitle: (IND) Set up sales taxes for multiple taxation transactions
ms:assetid: 8dcb33c1-89b4-4b86-99f3-e86bd2e08a68
ms:mtpsurl: https://technet.microsoft.com/library/JJ678042(v=AX.60)
ms:contentKeyID: 49386003
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- sales taxes
- (IND)
- India
- multiple tax
- multiple taxation transactions
audience: Application User
ms.search.region: India
---

# (IND) Set up sales taxes for multiple taxation transactions 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

To post a purchase transaction or sales transaction that has multiple taxes, you must activate the tax features of the tax types, such as excise and customs, in the **General ledger parameters** form. Then, you can set up a combination of sales taxes to use for a transaction that has multiple taxes.

## Activate sales taxes

Use the **General ledger parameters** form to activate sales taxes for India.

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

2.  Click **Sales tax**.

3.  In the **Apply India taxes** field group, select all the check boxes to activate the tax features for India.
    
    When multiple taxes are levied on a purchase transaction or sales transaction, the combination of taxes might differ. The combinations of sales tax and other taxes are as follows:
    
      - Excise + Central sales tax
    
      - Service tax + Central sales tax

## Set up a combination of taxes

Use the **Legal entities** and **Manage addresses** forms to set up a combination of sales taxes.

1.  Click **Organization administration** \> **Setup** \> **Organization** \> **Legal entities**.

2.  Select a legal entity.

3.  Click the **Tax registration** FastTab, and then enter the tax registration number for sales tax.

4.  Click the **Tax information** FastTab, and then enter information about the permanent account number (PAN) and withholding tax.

5.  Click **Taxes** to open the **Manage addresses** form, and then click the **Tax information** FastTab.

6.  Click **Add** to open the **Manage tax information** form, and then enter the following types of taxes:
    
      - Excise tax
    
      - Customs tax
    
      - Service tax
    
      - Sales tax
    
      - Value-added tax (VAT)
    
      - Withholding tax

## Example

You create a purchase order for a vendor. The purchase order has an amount of 9,000.00 and a maximum retail price, or credit, of 6,000.00. The maximum retail price was originally 9,000.00 but was changed to 6,000.00. The purchase order was updated with the changed amount.

The purchase order has both excise tax and sales tax.

The following table shows the tax details and the formula that is used to calculate each tax component.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Sales tax group or item sales tax group</p></th>
<th><p>Tax component</p></th>
<th><p>Percentage</p></th>
<th><p>Formula</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>MRP amount</p></td>
<td><p>BED (Basic Excise Duty)</p></td>
<td><p>10</p></td>
<td><p>Maximum retail price</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p>AED (Additional Excise Duty)</p></td>
<td><p>10</p></td>
<td><p>Maximum retail price</p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p>Excise surcharge</p></td>
<td><p>5</p></td>
<td><p>Maximum retail price + BED + AED</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p>PE Cess (Primary Education Cess)</p></td>
<td><p>1</p></td>
<td><p>Excluding line amount + Excise surcharge</p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p>SHE Cess (Secondary and Higher Education Cess)</p></td>
<td><p>1</p></td>
<td><p>Excluding line amount + Excise surcharge</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p>LST (Local Sales Tax)</p></td>
<td><p>4</p></td>
<td><p>Maximum retail price amount + BED + AED + Excise surcharge + PE Cess + SHE Cess</p></td>
</tr>
</tbody>
</table>


The base amount is calculated by using the following formula:

Original amount = Maximum retail price - (BED + AED + Excise surcharge + PE Cess + SHE Cess + LST)

Therefore, the basis that is used to calculate tax is 4,574.40.

The tax amount for each tax component is calculated as follows:

  - BED: 4,574.40 \* .10 = 457.44

  - AED: 4,574.40 \* .10 = 457.44

  - Excise surcharge = (4,574.40 + 457.44 + 457.44) \* .05 = 274.46

  - PE Cess: 274.46 \* .01 = 2.74

  - SHE Cess: 274.46 \* .01 = 2.74

  - LST: 4,574.40 + 457.44 + 457.44 + 274.46 + 2.74 + 2.74 = 5,769.22 \* .04 = 230.77

Therefore, the total tax is 1,425.60.


> [!NOTE]
> <P>In the <STRONG>Formula designer</STRONG> form, the <STRONG>Price incl. tax</STRONG> check box must be selected for each taxable basis. The taxable basis is the maximum retail price excluding the line amount.</P>



## See also

[(IND) General ledger parameters (modified form)](https://technet.microsoft.com/library/jj677901\(v=ax.60\))

[(IND) Legal entities (modified form)](https://technet.microsoft.com/library/jj664569\(v=ax.60\))

[(IND) Manage tax information (form)](https://technet.microsoft.com/library/jj664802\(v=ax.60\))

  


