---
title: (RUS) Set up the calculation of transport tax
TOCTitle: (RUS) Set up the calculation of transport tax
ms:assetid: 3e62ebbe-9a62-4d17-903d-e54062b68568
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ665308(v=AX.60)
ms:contentKeyID: 49387399
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- calculation
- Russia
- transport tax
---

# (RUS) Set up the calculation of transport tax 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You must set up the transport tax parameters in **General ledger** and **Fixed assets** before you can calculate the transport tax registers. Use the following procedures to set up the calculation of transport tax.

## Set up transport tax codes

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax codes**.

2.  Create a new sales tax code. For more information, see [Set up and use sales tax codes](set-up-and-use-sales-tax-codes.md).

3.  In the **Sales tax code** field, enter a sales tax code for the property tax.

4.  In the **Type of tax** field, select **Transport tax**.

5.  In the **Settlement period** field, select the settlement period.

6.  In the **Ledger posting group** field, select the ledger posting group.

7.  Click **Values** to open the **Values** form. For more information, see [Values of sales tax codes (form)](https://technet.microsoft.com/en-us/library/aa500790\(v=ax.60\)).

8.  In the **Value** field, enter the tax rate.

## Set up tax benefit codes for transport tax

1.  Click **Fixed assets (Russia)** \> **Setup** \> **Tax reporting** \> **Tax allowances**.

2.  Create a new tax benefit code. For more information, see [(RUS) Set up tax benefit codes](rus-set-up-tax-benefit-codes.md).

3.  In the **Privilege** field, enter the benefit code for the transport tax.

4.  In the **Benefit type** field, select the type of tax benefit.

5.  In the **Allowance value** field, enter the value of the tax benefit.

## Set up an accounting group for transport tax postings

1.  Click **Fixed assets (Russia)** \> **Setup** \> **Tax reporting** \> **Group of posting of taxes**.

2.  Create a new ledger posting group. For more information, see [(RUS) Set up groups for posting fixed assets taxes](rus-set-up-groups-for-posting-fixed-assets-taxes.md).

3.  In the **Ledger posting group** field, select a group for posting fixed asset (FA) taxes to the ledger accounts.

4.  In the **Account for FA taxes** field, select a ledger account for the transport tax.

## Set up the budget revenue codes for transport tax

1.  Click **Cash and bank management** \> **Setup** \> **Payment order** \> **Budget revenue classification**.

2.  Create a new budget revenue code. For more information, see [(RUS) Set up budget revenue codes for fixed asset taxes](rus-set-up-budget-revenue-codes-for-fixed-asset-taxes.md).

3.  In the **Budget revenue code** field, enter the budget revenue code for transport tax.

## Set up tax correspondence for the transport tax

1.  Click **Fixed assets (Russia)** \> **Setup** \> **Tax reporting** \> **Sales tax relations**.

2.  Create a new record. For more information, see [(RUS) Set up tax correspondence with budget revenue codes](rus-set-up-tax-correspondence-with-budget-revenue-codes.md).

3.  In the **Type of tax** field, select **Transport tax**.

4.  In the **Code** field, select the sales tax code for the transport tax.

5.  In the **Budget revenue code** field, select the budget revenue code that corresponds to the selected tax code.

## Set up the name for the transport tax transaction journal

1.  Click **General ledger** \> **Setup** \> **Journals** \> **Journal names**.

2.  Create a new journal name for the transport tax transactions. For more information, see [(RUS) Set up the name for fixed asset tax transactions journals](rus-set-up-the-name-for-fixed-asset-tax-transactions-journals.md).

3.  In the **Name** field, enter a name for the transport tax transactions journal.

4.  In the **Journal type** field, select **Transport tax**.

5.  In the **Voucher series** field, select a voucher series code for the journal.

## Set up Fixed assets parameters

1.  Click **Fixed assets (Russia)** \> **Setup** \> **Parameters**.

2.  Click **Tax reporting**. In the **Transport tax** field group, in the **Sales tax code** field, select the tax code for transport tax.

3.  In the **Compression** field, select the level of transaction compression for transport tax transactions.

4.  Click **Fixed assets** \> **Common** \> **Fixed assets** \> **Fixed assets**.

5.  Create a new asset. For more information, see [Fixed assets (form)](https://technet.microsoft.com/en-us/library/aa620341\(v=ax.60\)).

6.  In the **FA group** field, select the asset group for the asset.

7.  In the **Type** field, select **Vehicle**.

8.  On the **Tax reporting** FastTab, in the **Sales tax code** field, select the transport tax code. By default, this field displays the value that is specified in the **Fixed asset parameters** form.

9.  In the **Exemption from tax** field, select the tax benefit code that indicates that the asset is exempt from tax.

10. In the **Tax base** field, enter the tax base.

11. In the **Unit** field, select the unit of measure of the selected tax base.

## See also

[(RUS) Assessed tax (form)](https://technet.microsoft.com/en-us/library/jj856180\(v=ax.60\))

[(RUS) Budget revenue classification (form)](https://technet.microsoft.com/en-us/library/jj665363\(v=ax.60\))

[(RUS) Fixed asset parameters (form)](https://technet.microsoft.com/en-us/library/jj721462\(v=ax.60\))

[(RUS) Fixed assets (modified form)](https://technet.microsoft.com/en-us/library/jj923580\(v=ax.60\))

[(RUS) Tax value depending on the FA life-time (form)](https://technet.microsoft.com/en-us/library/jj839679\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

