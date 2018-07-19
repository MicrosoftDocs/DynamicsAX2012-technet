---
title: (IND) Create item sales tax groups
TOCTitle: (IND) Create item sales tax groups
ms:assetid: 18bdeb64-374c-4c06-80ec-c6536d3badd8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664518(v=AX.60)
ms:contentKeyID: 49385597
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Create item sales tax groups 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

A combination of sales tax groups and item sales tax groups are required to calculate sales tax on a sale or purchase order. The item sales tax group includes all the sales tax codes that apply when you sell a specific item. Complete the following procedures to create item sales tax groups and use the formula designer to set up sales tax calculations for item sales tax groups.

## Create an item sales tax group

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Item sales tax groups**.

2.  Click **New**.

3.  Enter a name and a description for the item sales tax group.

4.  Select a reporting type for the item sales tax code, which determines where the transaction line amount is included on the European Union (EU) sales list.

5.  If the item sales tax group includes a sales tax code for service tax, select the accounting basis to use to calculate the service tax.

6.  Expand the **Setup** FastTab and repeat the remaining steps for each sales tax code in the item sales tax group.

7.  Click **Add**.

8.  Select the sales tax code to include in the item sales tax group.

9.  To apply a percentage of the tax amount to the cost of inventory, select the **Load on inventory** check box and enter the percentage of tax amount that must be applied to the inventory cost in the **Load on inventory %** field.

10. In the **Abatement %** field, enter the percentage of the line amount to be deducted from the taxable basis before tax is calculated.

## Use the formula designer to set up the tax calculation of sales tax codes in the item sales tax group

After you include all of the sales tax codes in the item sales tax group, you can use the **Formula designer** to set up the hierarchical calculation of those sales tax codes.

To use the formula designer, add arguments to the **Arguments available** grid on the **Calculation** tab. Each argument consists of the following items:

  - **ID** – The sequential order for the formula argument.

  - **Tax code** – The sales tax code that the calculation expression is for.

  - **Taxable basis** – The basis of calculation for the sales tax. Select one of the following options:
    
      - **Line amount** – Calculate the tax amount based on the transaction line amount for the selected tax code.
    
      - **Excl. line amount** – Exclude the transaction line amount when you calculate the tax amount.
    
      - **Max. retail price** – Calculate the tax amount based on the maximum retail price of the item line.
    
      - **Assessable value** – Calculate the tax amount based on the assessable value of the transaction.

  - **Price incl. tax** check box – Indicates if the basis for calculating tax includes the amount of tax. This check box is selected automatically when the taxable basis is the maximum retail price.

  - **Calculation expression** – The mathematical expression to use when the sales tax code is calculated. Double-click a tax code or a charges code to add it to the **Calculation expression** field in the **Arguments available** grid. Use the mathematical operator buttons to add an operator to the expression.

## See also

[(IND) Item sales tax groups (modified form)](https://technet.microsoft.com/en-us/library/jj710918\(v=ax.60\))

[(IND) Formula designer (form)](https://technet.microsoft.com/en-us/library/jj677983\(v=ax.60\))

  


