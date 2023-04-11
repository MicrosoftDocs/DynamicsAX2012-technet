---
title: (IND) Post purchase transactions of excise using general and payment journals
TOCTitle: (IND) Post purchase transactions of excise using general and payment journals
ms:assetid: f6db237e-6162-4256-9879-534819780328
ms:mtpsurl: https://technet.microsoft.com/library/JJ710964(v=AX.60)
ms:contentKeyID: 49386376
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Post purchase transactions of excise using general and payment journals 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



When you credit the vendor account and debit the ledger account, the excise amounts calculated are debited to the accounts as defined in the **Tax ledger posting groups** form for the ECC number.

The ledger accounts that are debited with the excise amounts depend on the excise record type you select in the **Excise record type** field in the **Journal voucher** form.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>When you select this excise record type</p></th>
<th><p>This ledger account type is debited</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>None</strong></p></td>
<td><p>Recoverable account</p></td>
</tr>
<tr class="even">
<td><p><strong>RG23D</strong></p></td>
<td><p>RG23D CENVAT credit account</p></td>
</tr>
<tr class="odd">
<td><p><strong>RG23A</strong></p></td>
<td><p>Recoverable account. RG23A deferred account if the claim percentage for CENVAT is defined.</p></td>
</tr>
<tr class="even">
<td><p><strong>RG23C</strong></p></td>
<td><p>Recoverable account. RG23C deferred account if the claim percentage for CENVAT is defined.</p></td>
</tr>
</tbody>
</table>


To update the excise register on the date the invoice is posted, you must select the **Delivery date** or **Invoice date** in the **Vendor calculation date type** field in the **General ledger parameters** form. If you select the **Document date** option, the excise register is updated on the document date. If the document date is not set, then the registers are updated on the date the invoice is posted on.


> [!NOTE]
> <P>The excise calculation rate that is applicable to an excise tax code is based on the value that you select in the <STRONG>Vendor calculation date type</STRONG> field in the <STRONG>General ledger parameters</STRONG> form.</P>



1.  Click **General ledger** \> **Journals** \> **General journal**. Select or create a journal, and then click **Lines**.
    
    −or−
    
    Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**. Select or create a journal, and then click **Lines**

2.  Enter the details for the voucher line on the **Overview** tab.

3.  Select the excise tariff code for the transaction in the **Excise tariff code** field in the lower pane.

4.  Click the **General** tab. Select the sales tax group in the **Sales tax group** field and the item sales tax group in the **Item sales tax group** field.
    

    > [!NOTE]
    > <P>Excise taxes are calculated only if the sales tax group and the item sales tax group have common tax codes of the tax type <STRONG>Excise</STRONG>.</P>



5.  View or modify the amount in the **Assessable value** field. Assessable value is one of the base values the excise duty can be calculated on. The amount entered in the journal line, either in the **Credit** or **Debit** field, is displayed by default.
    

    > [!NOTE]
    > <P>If a vendor is a part of the transaction, the taxes will be posted to the recoverable account before a settlement period is closed, regardless of whether the assessable value is positive or negative. If a customer is a part of the transaction, the taxes will be posted to the payable account before a settlement period is closed, regardless of whether the assessable value is positive or negative.</P>



6.  Enter the amount for the maximum retail price of the item in the **Max. retail price** field. The maximum retail price is one of the base values the excise duty can be calculated on.
    

    > [!NOTE]
    > <P>If the taxable basis is <STRONG>Assessable</STRONG> or <STRONG>Max. retail price</STRONG>, modify the value in the <STRONG>Assessable value</STRONG> and <STRONG>Max.retail price</STRONG> fields.</P>



7.  Click the **Tax information** tab. Under the **Company information** field group, you can view or change the name and current address of the company.

8.  Select the excise registration number (ECC) of the company in the **ECC number** field. The ledger accounts to post the excise tax amounts are identified based on the ECC number.

9.  Select the type of excise register in the **Excise record type** field.

10. Click the **Sales tax** to view the calculation of excise in the **Temporary sales tax transactions** form.

11. Click the **Formula designer** to view the formula defined for each excise tax component for an item sales tax group, for the calculation of excise.

12. Validate and post the journal. The excise register-Part II is updated with the excise amount.

## See also

[(IND) General ledger parameters (modified form)](https://technet.microsoft.com/library/jj677901\(v=ax.60\))

[(IND) Tax ledger posting groups (form)](https://technet.microsoft.com/library/jj664546\(v=ax.60\))

[(IND) Temporary sales tax transactions (modified form)](https://technet.microsoft.com/library/jj664487\(v=ax.60\))

[(IND) Formula designer (form)](https://technet.microsoft.com/library/jj677983\(v=ax.60\))

  


