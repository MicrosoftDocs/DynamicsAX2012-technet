---
title: (IND) Post transactions that include excise duty from free text invoices
TOCTitle: (IND) Post transactions that include excise duty from free text invoices
ms:assetid: 793fb239-8382-467d-bb60-47f965e1bb44
ms:mtpsurl: https://technet.microsoft.com/library/JJ677945(v=AX.60)
ms:contentKeyID: 49385908
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Post transactions that include excise duty from free text invoices 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



When you post sales transactions that include excise duty from free text invoices, the excise amounts that are calculated in the **Free text invoice** form will be credited to the payable accounts as defined in the **Tax ledger posting group** form for the ECC number.

Refer to the table for information about the ledger accounts that will be credited with the excise amounts.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>When you select this excise record type</p></th>
<th><p>This ledger account type is credited</p></th>
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


The excise amounts that are calculated for the invoice line are credited to the payable accounts as defined in the tax ledger posting group for the ECC number.

The excise registers, RG23A (Part II), RG23C (Part II), and RG23D are updated when you post the free text invoice line according to the type of register you select in the **Excise record type** field on the **Tax information** tab.

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  Enter the details of the invoice on the **Overview** tab.

3.  Click the **Invoice** tab.

4.  Select the tax group for excise duty in the **Sales tax group** field and the item tax group for excise duty in the **Item sales tax group** field.
    

    > [!NOTE]
    > <P>Excise taxes are calculated only if the sales tax group and the item sales tax group have common tax codes of the tax type <STRONG>Excise</STRONG>.</P>



5.  Click the **Invoice lines** tab.

6.  Enter the tariff code for the invoice line in the **Excise tariff code** field.

7.  Enter the amount in the **Assessable value** field or the **Max. retail price** field if the excise duty is calculated on assessable value or maximum retail price.

8.  Click the **Tax information** tab.

9.  Under the **Company information** field group, you can view or change the name and current address of the company.

10. Select the Excise Control Code (ECC) number of the company in the **ECC number** field.

11. Select the type of excise record in the **Excise record type** field.

12. Post the free text invoice.

## See also

[(IND) Free text invoice (modified form)](https://technet.microsoft.com/library/jj664875\(v=ax.60\))

[(IND) Tax ledger posting groups (form)](https://technet.microsoft.com/library/jj664546\(v=ax.60\))

  


