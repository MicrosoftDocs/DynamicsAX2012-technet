---
title: (RUS) Set up the calculation of assessed tax
TOCTitle: (RUS) Set up the calculation of assessed tax
ms:assetid: 6e281290-270f-453c-a39d-659f76404a5e
ms:mtpsurl: https://technet.microsoft.com/library/JJ678343(v=AX.60)
ms:contentKeyID: 49387573
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- calculation
- Russia
- assessed tax
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up the calculation of assessed tax 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You must set up the assessed tax parameters in **General ledger** and **Fixed assets** before you can calculate the property tax register. Use the following procedures to set up the calculation of assessed tax.

## Set up property tax codes

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax codes**.

2.  Create a new sales tax code. For more information, see [Set up and use sales tax codes](set-up-and-use-sales-tax-codes.md).

3.  In the **Sales tax code** field, enter a sales tax code for the assessed tax.

4.  In the **Type of tax** field, select **Assessed tax**.

5.  In the **Settlement period** field, select the settlement period.

6.  In the **Ledger posting group** field, select the ledger posting group.

7.  Click **Values** to open the **Values** form. For more information, see [Values of sales tax codes (form)](https://technet.microsoft.com/library/aa500790\(v=ax.60\)).

8.  In the **Value** field, enter the tax rate.

## Set up tax benefit codes for assessed tax

1.  Click **Fixed assets (Russia)** \> **Setup** \> **Tax reporting** \> **Tax allowances**.

2.  Create a new tax benefit code. For more information, see [(RUS) Set up tax benefit codes](rus-set-up-tax-benefit-codes.md).

3.  In the **Privilege** field, enter the benefit code for the assessed tax.

4.  In the **Benefit type** field, select the type of tax benefit.

5.  In the **Allowance value** field, enter the value of the tax benefit.

## Set up an accounting group for assessed tax postings

1.  Click **Fixed assets (Russia)** \> **Setup** \> **Tax reporting** \> **Group of posting of taxes**.

2.  Create a new ledger posting group. For more information, see [(RUS) Set up groups for posting fixed assets taxes](rus-set-up-groups-for-posting-fixed-assets-taxes.md).

3.  In the **Ledger posting group** field, select a group to post fixed asset (FA) taxes to the ledger accounts.

4.  In the **Account for FA taxes** field, select a ledger account for the assessed tax.

## Set up the budget revenue codes for assessed tax

1.  Click **Cash and bank management** \> **Setup** \> **Payment order** \> **Budget revenue classification**.

2.  Create a new budget revenue code. For more information, see [(RUS) Set up budget revenue codes for fixed asset taxes](rus-set-up-budget-revenue-codes-for-fixed-asset-taxes.md).

3.  In the **Budget revenue code** field, select the budget revenue code that corresponds to the selected tax code.

4.  Select the **SSGS** check box to indicate that the budget revenue code belongs to the Standard System of Gas Supply (SSGS).

## Set up tax correspondence for the assessed tax

1.  Click **Fixed assets (Russia)** \> **Setup** \> **Tax reporting** \> **Sales tax relations**.

2.  Create a new record. For more information, see [(RUS) Set up tax correspondence with budget revenue codes](rus-set-up-tax-correspondence-with-budget-revenue-codes.md).

3.  In the **Type of tax** field, select **Assessed tax**.

4.  In the **Code** field, select the sales tax code for the assessed tax.

5.  In the **Budget revenue code** field, select the budget revenue code that corresponds to the selected tax code.

## Set up the name for the assessed tax transaction journal

1.  Click **General ledger** \> **Setup** \> **Journals** \> **Journal names**.

2.  Create a new journal name for the assessed tax transactions. For more information, see [(RUS) Set up the name for fixed asset tax transactions journals](rus-set-up-the-name-for-fixed-asset-tax-transactions-journals.md).

3.  In the **Name** field, enter a name for the assessed tax transactions journal.

4.  In the **Journal type** field, select **Assessed tax**.

5.  In the **Voucher series** field, select a voucher series code for the journal.

## Set up Fixed assets parameters for assessed tax calculation

1.  Click **Fixed assets (Russia)** \> **Setup** \> **Parameters**.

2.  Click **Tax reporting**. In the **Assessed tax** field group, in the **Sales tax code** field, select the tax code for the assessed tax.

3.  In the **Compression** field, select the level of compression for the assessed tax transactions.

4.  Close the form.

5.  Click **Fixed assets** \> **Common** \> **Fixed assets** \> **Fixed assets**.

6.  Create a new asset. For more information, see [Fixed assets (form)](https://technet.microsoft.com/library/aa620341\(v=ax.60\)).

7.  In the **FA group** field, select the asset group for the asset.

8.  In the **Type** field, select **Tangible** if the fixed asset is real property.

9.  In the **Flag of ownership** field, select **Ownership**, **Oper. management**, **Rented**, or **Ownership outside Russia** to indicate whether the fixed asset is owned, leased, under operational management, or owned by someone who is outside Russia.

10. On the **Tax reporting** FastTab, in the **Sales tax code** field, select the assessed tax code. By default, this field displays the value that is specified in the **Fixed asset parameters** form.

11. In the **Exemption from tax** field, select the tax benefit code that indicates that the asset is exempt from tax.

12. In the **Asset kind** field, select the type of property from the following options:
    
      - **1** − SSGS real property asset.
    
      - **2** − Real property asset of a Russian company that is located within the territories of constituent entities of the Russian Federation.
    
      - **3** – All other asset types.
    

    > [!NOTE]
    > <P>The default value of this field is <STRONG>3</STRONG>. The assessed tax declaration and the method that is used to calculate the advance payment depend on the value in this field. If the fixed asset is outside the Russian Federation, regardless of the type that is specified in the <STRONG>Asset kind</STRONG> field, an additional printout of section 2 of the declaration is produced, in which the property is marked as type 4.</P>



13. Click **Distribution** \> **Distribution** to open the **Distribution** form.

14. In the **Location** field, select the location of the fixed asset.

15. In the **External owner** field, enter the name of the external owner of the asset.
    

    > [!NOTE]
    > <P>If you do not enter a value in this field, the asset share that is listed on this line is considered to be owned property.</P>



16. In the **Sales tax code** field, select a tax code only if the tax assessment for the asset is performed at a rate that differs from the default rate for the selected location, or if the tax code is connected to a different budget revenue code.

17. In the **Distribution share** field, enter the book value of the share of the real property as a fraction. The **/** field displays the distribution percentage.

## See also

[(RUS) Assessed tax (form)](https://technet.microsoft.com/library/jj856180\(v=ax.60\))

[(RUS) Budget revenue classification (form)](https://technet.microsoft.com/library/jj665363\(v=ax.60\))

[(RUS) Fixed asset parameters (form)](https://technet.microsoft.com/library/jj721462\(v=ax.60\))

[(RUS) Fixed assets (modified form)](https://technet.microsoft.com/library/jj923580\(v=ax.60\))

[(EEUR) Ground area categories (form)](https://technet.microsoft.com/library/jj710742\(v=ax.60\))

[(RUS) Distribution (form)](https://technet.microsoft.com/library/jj678526\(v=ax.60\))

  


