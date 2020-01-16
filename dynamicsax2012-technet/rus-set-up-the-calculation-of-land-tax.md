---
title: (RUS) Set up the calculation of land tax
TOCTitle: (RUS) Set up the calculation of land tax
ms:assetid: 18882685-d837-4a92-9a76-98996f81ee1c
ms:mtpsurl: https://technet.microsoft.com/library/JJ711439(v=AX.60)
ms:contentKeyID: 49387258
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Russia
- land tax
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up the calculation of land tax 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You must set up the land tax parameters in the **General ledger** and **Fixed assets** modules before you calculate the land tax registers. Use the following procedures to set up the calculation of land tax.

In the **Sales tax jurisdictions** form, enter the tax jurisdiction references to complete the tax authority details in the declaration. In the **Sales tax authorities** form, enter the vendor code for the tax authorities that you are submitting the tax returns to. You must also specify the Russian Classification of Objects of Administrative Division (RCOAD) code for the vendor in the **Vendors** form.

## Set up land tax codes

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax codes**.

2.  Create a new sales tax code. For more information, see [Set up and use sales tax codes](set-up-and-use-sales-tax-codes.md).

3.  In the **Sales tax code** field, enter a sales tax code for the land tax.

4.  In the **Type of tax** field, select **Land tax**.

5.  In the **Settlement period** field, select the settlement period.

6.  In the **Ledger posting group** field, select the ledger posting group.

7.  Click **Values** to open the **Values** form. For more information, see [Values of sales tax codes (form)](https://technet.microsoft.com/library/aa500790\(v=ax.60\)).

8.  In the **Value** field, enter the tax rate.

## Set up tax benefit codes for land tax

1.  Click **Fixed assets (Russia)** \> **Setup** \> **Tax reporting** \> **Tax allowances**.

2.  Create a new tax benefit code. For more information, see [(RUS) Set up tax benefit codes](rus-set-up-tax-benefit-codes.md).

3.  In the **Privilege** field, enter the benefit code for the land tax.

4.  In the **Benefit type** field, select the type of tax benefit.

5.  In the **Allowance value** field, enter the value of the tax benefit.

## Set up an accounting group for land tax postings

1.  Click **Fixed assets (Russia)** \> **Setup** \> **Tax reporting** \> **Group of posting of taxes**.

2.  Create a new ledger posting group. For more information, see [(RUS) Set up groups for posting fixed assets taxes](rus-set-up-groups-for-posting-fixed-assets-taxes.md).

3.  In the **Ledger posting group** field, select a group for posting fixed asset (FA) taxes to the ledger accounts.

4.  In the **Account for FA taxes** field, select a ledger account for the land tax.

## Set up the budget revenue codes for land tax

1.  Click **Cash and bank management** \> **Setup** \> **Payment order** \> **Budget revenue classification**.

2.  Create a new budget revenue code. For more information, see [(RUS) Set up budget revenue codes for fixed asset taxes](rus-set-up-budget-revenue-codes-for-fixed-asset-taxes.md).

3.  In the **Budget revenue code** field, enter the budget revenue code for land tax.

## Set up tax correspondence for the land tax

1.  Click **Fixed assets (Russia)** \> **Setup** \> **Tax reporting** \> **Sales tax relations**.

2.  Create a new record. For more information, see [(RUS) Set up tax correspondence with budget revenue codes](rus-set-up-tax-correspondence-with-budget-revenue-codes.md).

3.  In the **Type of tax** field, select **Land tax**.

4.  In the **Code** field, select the sales tax code for the land tax.

5.  In the **Budget revenue code** field, select the budget revenue code that corresponds to the selected tax code.

## Set up the name for the land tax transaction journal

1.  Click **General ledger** \> **Setup** \> **Journals** \> **Journal names**.

2.  Create a new journal name for the land tax transactions. For more information, see [(RUS) Set up the name for fixed asset tax transactions journals](rus-set-up-the-name-for-fixed-asset-tax-transactions-journals.md).

3.  In the **Name** field, enter a name for the land tax transactions journal.

4.  In the **Journal type** field, select **Land tax**.

5.  In the **Voucher series** field, select a voucher series code for the journal.

## Set up category codes for the ground area

1.  Click **Organization administration** \> **Setup** \> **Ground area categories**.

2.  Create a new ground area category.

3.  In the **Category** field, enter a category code for the ground area.

4.  In the **Description** field, enter a description for the category code.

## Set up the asset distribution

1.  Click **Fixed assets** \> **Common** \> **Fixed assets** \> **Fixed assets**. Click **Distribution** \> **Distribution**.

2.  In the **Location** field, select the location of the fixed asset.

3.  In the **External owner** field, enter the name of the external owner of the asset.
    

    > [!NOTE]
    > <P>If you do not enter a value in this field, the asset share that is listed on this line is considered to be owned property.</P>



4.  In the **Sales tax code** field, select a tax code only if the tax assessment for the asset is performed at a rate other than the default rate for the selected location, or if the tax code is connected to a different budget revenue code.

5.  In the **Cadastral cost** field, enter the cadastral cost of the ground area.

6.  In the **Owned share** field, enter the ownership share of the ground area as a proper fraction.
    

    > [!NOTE]
    > <P>The <STRONG>Cadastral cost</STRONG> and <STRONG>Owned share</STRONG> fields are available only if you select <STRONG>Ground area</STRONG> in the <STRONG>Type</STRONG> field in the <STRONG>Fixed assets</STRONG>.</P>



## Set up Fixed assets module parameters

1.  Click **Fixed assets (Russia)** \> **Setup** \> **Parameters**.

2.  Click **Tax reporting**. In the **Land tax** field group, in the **Sales tax code** field, select the tax code for the land tax.

3.  In the **Compression** field, select the level of compression for land tax transactions.

4.  Click **Fixed assets** \> **Common** \> **Fixed assets** \> **Fixed assets**.

5.  Create a new asset. For more information, see [Fixed assets (form)](https://technet.microsoft.com/library/aa620341\(v=ax.60\)).

6.  In the **FA group** field, select the asset group for the asset.

7.  In the **Acquisition date** field, select the date of the acquisition of the asset.

8.  In the **Acquisition cost** field, enter the amount that it cost to acquire the asset.

9.  In the **Type** field, select **Ground area**.

10. On the **Technical information** FastTab, in the **Category** field, select the category code for the plot of land.

11. In the **Cadastral number** field, enter the cadastral number for the plot of land.

12. In the **Start date of building** field, select the starting date of the construction of the building.

13. On the **Tax reporting** FastTab, in the **Tax base** field, enter the cadastral land value.

14. In the **Owned share** field, enter the ownership share of the ground area as a proper fraction.

15. In the **Sales tax code** field, select the sales tax code for the land tax.

16. In the **Land tax exemption (art.387)** field, select the exemption type benefit code.

17. In the **Land tax exemption (art.395)** field, select the exemption type benefit code, if necessary.

18. In the **Land tax allowance as non-taxable share** field, select the non-taxable type benefit code, if necessary.

19. In the **Non-taxable area share** field, indicate the part of the land that is tax exempt, if necessary.

20. Click **History** \> **Tax allowances** to view the history of the tax benefit changes.

## See also

[(RUS) Budget revenue classification (form)](https://technet.microsoft.com/library/jj665363\(v=ax.60\))

[(RUS) Fixed asset parameters (form)](https://technet.microsoft.com/library/jj721462\(v=ax.60\))

[(RUS) Fixed assets (modified form)](https://technet.microsoft.com/library/jj923580\(v=ax.60\))

[(RUS) Distribution (form)](https://technet.microsoft.com/library/jj678526\(v=ax.60\))

[(EEUR) Ground area categories (form)](https://technet.microsoft.com/library/jj710742\(v=ax.60\))

  


