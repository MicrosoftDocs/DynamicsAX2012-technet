---
title: (IND) Post excise tax transactions from the customer payment journal
TOCTitle: (IND) Post excise tax transactions from the customer payment journal
ms:assetid: cf2d40b0-9954-4b14-a927-b1124587488a
ms:mtpsurl: https://technet.microsoft.com/library/JJ664899(v=AX.60)
ms:contentKeyID: 49386228
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Post excise tax transactions from the customer payment journal 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When you post sales transactions that include excise duty from the customer payment journal, the excise amounts that are calculated for the invoice line are credited to the payable accounts as defined in the **Tax ledger posting group** form for the ECC number.

Refer to the following table for more information about the ledger accounts that will be credited with the excise amount.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>When you select this excise record type:</p></th>
<th><p>This ledger account type is credited:</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>None</p></td>
<td><p>Payable account</p></td>
</tr>
<tr class="even">
<td><p>RG23D</p></td>
<td><p>RG23D CENVAT credit transfer account</p></td>
</tr>
<tr class="odd">
<td><p>RG23A</p></td>
<td><p>Payable account</p></td>
</tr>
<tr class="even">
<td><p>RG23C</p></td>
<td><p>Payable account</p></td>
</tr>
</tbody>
</table>


The excise registers, RG23A (Part II), RG23C (Part II), and RG23D, are updated when you post the customer payment journal line.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Press CTRL+N to create a new journal and enter the required details.

3.  Click **Lines** to open the **Journal voucher** form and enter the required details.

4.  Enter the details of the invoice on the **Overview** tab.

5.  Click the **General** tab.

6.  Select the tax group for excise duty in the **Sales tax group** field and the item tax group for excise duty in the **Item sales tax group** field.
    

    > [!NOTE]
    > <P>Excise taxes are calculated only if the sales tax group and the item sales tax group have common tax codes of the tax type <STRONG>Excise</STRONG>.</P>



7.  Enter the amount that the excise duty is calculated on in the **Assessable value** field and the **Max. retail price** field.

8.  Click the **Tax information** tab.

9.  Under the **Company information** field group, you can view or change the name and current address of the company.

10. Select the Excise Control Code (ECC) number of the company in the **ECC number** field.

11. Post the payment journal line.

## See also

[(IND) Journal voucher - Customer payment journal (modified form)](https://technet.microsoft.com/library/jj664751\(v=ax.60\))

  


