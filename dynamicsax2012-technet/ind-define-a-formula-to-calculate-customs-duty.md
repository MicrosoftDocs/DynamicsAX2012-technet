---
title: (IND) Define a formula to calculate customs duty
TOCTitle: (IND) Define a formula to calculate customs duty
ms:assetid: 85691546-e2d7-463c-9acc-c6ad1a2c0185
ms:mtpsurl: https://technet.microsoft.com/library/JJ677982(v=AX.60)
ms:contentKeyID: 49385946
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Define a formula to calculate customs duty 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You must define the formula to calculate customs duty for the item sales tax group.

The formula for customs tax codes are defined by using tax codes and miscellaneous charge codes. You must select the taxable basis for the calculation of customs duty for each tax code.

For example, suppose that you create a purchase order for items with a maximum retail price of INR 6,000. The taxable basis for the calculation of basic customs duty is the maximum retail price. The percentage of tax for each tax component is shown in the following table. The **Price incl. tax** check box in the **Formula designer** form is selected for the BCD, ACD, SUR, E-CESS, and SHE-CESS tax codes.

<table style="width:100%;">
<colgroup>
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Tax code</p></th>
<th><p>Tax component</p></th>
<th><p>Percentage</p></th>
<th><p>Taxable basis</p></th>
<th><p>Calculation expression</p></th>
<th><p>Customs duty</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>BCD</p></td>
<td><p>BCD</p></td>
<td><p>10</p></td>
<td><p>Max. retail price</p></td>
<td><p></p></td>
<td><p>475.74(4757.37*10%)</p></td>
</tr>
<tr class="even">
<td><p>ACD</p></td>
<td><p>ACD</p></td>
<td><p>10</p></td>
<td><p>Max. retail price</p></td>
<td><p></p></td>
<td><p>475.74 (4757.37*10%)</p></td>
</tr>
<tr class="odd">
<td><p>SUR</p></td>
<td><p>SUR</p></td>
<td><p>5</p></td>
<td><p>Max. retail price</p></td>
<td><p>+[BCD+ ACD]</p></td>
<td><p>285.45 (4757.37 +475.74+475.74 = (5708.85*5% = 285.45)</p></td>
</tr>
<tr class="even">
<td><p>E-CESS</p></td>
<td><p>E-CESS</p></td>
<td><p>1</p></td>
<td><p>Excl. line amount</p></td>
<td><p>+[SUR]</p></td>
<td><p>2.85 (285.45*1%)</p></td>
</tr>
<tr class="odd">
<td><p>SHE-CESS</p></td>
<td><p>SHE-CESS</p></td>
<td><p>1</p></td>
<td><p>Excl. line amount</p></td>
<td><p>+[SUR]</p></td>
<td><p>2.85 (285.45*1%)</p></td>
</tr>
</tbody>
</table>


If the basis is maximum retail price, customs duty is calculated automatically using the following formula:

6000 = Basis + BCD + ACD + SUR +E-CESS + SHE-CESS

Basis = X

6000 = X + 0.10X + 0.10X + 0.06X + 0.0006X + 0.0006X

6000 = 1.2612X

X = 6000/1.2612

Price excluding tax = 4,757.37

E-CESS and SHE-CESS is calculated on the basis of the surcharge amount and the line amount is not considered in the calculation of customs duty.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



## To define a formula for calculating customs duty

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Item sales tax groups**.
    

    > [!NOTE]
    > <P>For more information, see "Item sales tax groups (form)" in the Applications and Business Processes Help.</P>



2.  Click **Formula designer** to set up a formula for taxes in the **Formula designer** form.

3.  Press CTRL+N on the **Calculation** tab to define the calculation expression for a specific customs tax code. The automatically generated priority ID for customs duty calculation is displayed in the **ID** field.

4.  Select the tax code to define the formula for in the **Tax code** field.
    

    > [!NOTE]
    > <P>You cannot define a formula when you calculate customs duty using amount per unit.</P>



5.  Select the basis to calculate tax from the following options in the **Taxable basis** field:
    
      - **Line amount** – Customs duty is calculated on the transaction line amount by using the calculation expression defined for the customs tax code.
    
      - **Excl. line amount** – Customs duty is calculated by using the calculation expression defined for the customs tax code.
    
      - **Max. retail price** – Customs duty is calculated on the maximum retail price of the item line by using the calculation expression defined for the customs tax code.
    
      - **Assessable value** – Customs duty is calculated on the assessable value calculated for an item by using the calculation expression defined for the customs tax code.

6.  Select the **Price incl. tax** check box if the taxable basis includes the tax amount.
    

    > [!NOTE]
    > <P>This check box is selected automatically for custom tax codes with the maximum retail price as the taxable basis. You must select the <STRONG>Price incl. tax</STRONG> check box for the tax codes that have a taxable basis as excluding the line amount, and their customs duty calculation is dependent on the other tax codes with maximum retail price as taxable basis.</P>



7.  Click the **+** button, **–** button, **\*** button, or **/** button to insert the calculation expression for the customs tax code in the **Calculation expression** field.
    

    > [!NOTE]
    > <P>When the <STRONG>Price incl. tax</STRONG> check box is selected for a record, the calculation of tax that is based on the calculation expression should be in the reverse order.</P>



8.  Use one of the following methods to add a custom tax code or a miscellaneous charge code to the **Calculation expression** field:
    
      - Click the **Taxes** tab or the **Misc. charges code** tab, right-click and select **Add tax code** or **Add misc. charges code**.
    
      - Double-click a code on the **Taxes** tab or **Misc. charges code** tab.
    
      - Move a code from the **Taxes** tab or **Misc. charges code** tab.
    

    > [!NOTE]
    > <P>You must insert a calculation expression before each custom tax code.</P>



## See also

[(IND) Attach sales tax codes to sales tax groups](ind-attach-sales-tax-codes-to-sales-tax-groups.md)

[(IND) Attach tax codes to item tax groups for customs](ind-attach-tax-codes-to-item-tax-groups-for-customs.md)

[(IND) Item sales tax groups (modified form)](https://technet.microsoft.com/library/jj710918\(v=ax.60\))

[(IND) Formula designer (form)](https://technet.microsoft.com/library/jj677983\(v=ax.60\))

  


