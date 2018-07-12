---
title: (IND) Post sales transactions of excise using general and payment journals
TOCTitle: (IND) Post sales transactions of excise using general and payment journals
ms:assetid: 1c67898c-6465-4886-aa3c-ba6d7d377271
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664532(v=AX.60)
ms:contentKeyID: 49385611
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Post sales transactions of excise using general and payment journals 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When you debit a customer account and credit the ledger account, the excise amounts that are calculated are credited to the accounts that are defined in the **Tax ledger posting groups** form for the Excise Control Code (ECC) number.

The ledger accounts that are credited with the excise amounts depend on the excise record type that you select in the **Excise record type** field in the **General journal lines** form.

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


To update the excise register on the date that the invoice is posted, you must select **Invoice date** in the **Customer calculation date type** field in the **General ledger parameters** form.

The excise calculation rate that is applicable to an excise tax code is based on the value that you select in the **Customer calculation date type** field in the **General ledger parameters** form.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Journals** \> **General journal**.
    
    −or−
    
    Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Press CTRL+N to create a new journal and click **Lines**.

3.  Enter the details for the voucher line on the **Overview** tab.
    

    > [!NOTE]
    > <P>For more information see "General journal lines (form)" in the Applications and Business Processes Help.</P>



4.  Select the excise tariff code for the transaction in the **Excise tariff code** field on the **Overview** tab in the **General journal lines** form.
    

    > [!NOTE]
    > <P>Select the <STRONG>Excise tariff code</STRONG> field on the <STRONG>Tax information</STRONG> tab in the <STRONG>Customer payment journal lines</STRONG> form.</P>



5.  Click the **General** tab. Select the sales tax group in the **Sales tax group** field and the item sales tax group in the **Item sales tax group** field.
    

    > [!NOTE]
    > <P>Excise taxes are calculated only if the sales tax group and the item sales tax group have common tax codes of the tax type Excise.</P>



6.  View or modify the amount in the **Assessable value** field. Assessable value is one of the base values that the excise duty can be calculated on. The amount entered in the journal line, either in the **Credit** field or in the **Debit** field, is displayed by default.
    

    > [!NOTE]
    > <P>If a customer account is a part of the transaction, the taxes will be posted to the payable account before a settlement period is closed, regardless of whether the assessable value is positive or negative.</P>



7.  Enter the amount for the maximum retail price of the item in the **Max. retail price** field. The maximum retail price is one of the base values that the excise duty can be calculated on.
    

    > [!NOTE]
    > <P>If the taxable basis is <STRONG>Assessable</STRONG> or <STRONG>Max.retail price</STRONG>, modify the values in the <STRONG>Assessable value</STRONG> and <STRONG>Max.retail price</STRONG> fields.</P>



8.  Click the **Tax information** tab to view or change the name and current address of the company.

9.  Select the ECC number of the company in the **ECC number** field. The ledger accounts to post the excise tax amounts to are identified, based on the ECC number.

10. Select the type of excise register in the **Excise record type** field.

11. Click **Sales tax** to view the calculation of excise in the **Temporary sales tax transactions** form.

12. Click **Formula designer** in the **Temporary sales tax transactions** form to view the formula defined for the calculation of excise for each excise tax component for an item sales tax group.

13. Validate and post the journal. The Excise Register-Part II is updated with the excise amount.

## See also

[(IND) Journal voucher - Customer payment journal (modified form)](https://technet.microsoft.com/en-us/library/jj664751\(v=ax.60\))

  


