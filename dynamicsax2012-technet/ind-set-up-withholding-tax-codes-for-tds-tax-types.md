---
title: (IND) Set up withholding tax codes for TDS tax types
TOCTitle: (IND) Set up withholding tax codes for TDS tax types
ms:assetid: 59f2fac8-33c1-49e2-8cb8-7b9b460a65cd
ms:mtpsurl: https://technet.microsoft.com/library/JJ677837(v=AX.60)
ms:contentKeyID: 49385801
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Set up withholding tax codes for TDS tax types 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

## Create a withholding tax code for TDS tax

1.  Click **General ledger** \> **Setup** \> **Withholding tax** \> **Withholding tax codes**.

2.  Click **New** to create a withholding tax code for TDS.

3.  In the **Withholding tax code** field, enter **TDS**. In the **Withholding tax name** field, enter the name of the TDS tax code.

4.  On the **General** FastTab, in the **Currency** field, select the currency in which the tax is displayed. TDS tax must be paid in this currency.

5.  In the **Main account** field, select the main account to which to post the TDS amount that is deducted in sales transactions.

6.  On the **Calculation** FastTab, select whether the TDS tax is calculated based on the net amount or the gross amount.

7.  In the **Round-off** field, enter the round-off method, in the format x.xx. In the **Rounding form** field, specify how amounts should be rounded.
    
    For example, if you enter 0.10 in the **Round-off** field, an amount of 9345.43 is rounded to 9345.40 or 9345.50, depending on the option that is selected in the **Rounding form** field.

8.  Click **Close**, or complete the other procedures in this topic to set up more requirements for the TDS tax code.

## Set up tax values for a withholding tax code

1.  Click **General ledger** \> **Setup** \> **Withholding tax** \> **Withholding tax codes**.

2.  Select the tax code for which to set up tax values, and then click **Values**.

3.  In the **Withholding tax values** form, in the **From date** and **To date** fields, enter the starting date and ending date for the TDS values.

4.  Enter the minimum and maximum amounts to which to apply the TDS tax.

5.  In the **Value** field, enter the percentage to use to calculate the TDS tax.

6.  In the **Exclude %** field, enter the percentage amount to exclude before the TDS tax is calculated, and then click **Close**.

## Set up tax limits for a withholding tax code

1.  Click **General ledger** \> **Setup** \> **Withholding tax** \> **Withholding tax codes**.

2.  Select the tax code for which to set up tax limits, and then click **Limits**.

3.  In the **Withholding tax limits** form, in the **From date** and **To date** fields, enter the starting date and ending date for the TDS limits.

4.  Enter the minimum and maximum amounts to which to apply the TDS tax, and then click **Close**.

## See also

[Withholding tax codes (form)](https://technet.microsoft.com/library/aa585361\(v=ax.60\))

[Withholding tax values (form)](https://technet.microsoft.com/library/aa615586\(v=ax.60\))

[Withholding tax limits (form)](https://technet.microsoft.com/library/aa592034\(v=ax.60\))

[(IND) Withholding tax codes (modified form)](https://technet.microsoft.com/library/jj664629\(v=ax.60\))

[(IND) Setting up Tax Deducted at Source (TDS)](ind-setting-up-tax-deducted-at-source-tds.md)

  


