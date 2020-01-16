---
title: (CZE) Set up sales tax codes for intra-community VAT
TOCTitle: (CZE) Set up sales tax codes for intra-community VAT
ms:assetid: d2eb668c-1df2-4efa-ba9f-afd7f5a54593
ms:mtpsurl: https://technet.microsoft.com/library/JJ677813(v=AX.60)
ms:contentKeyID: 49385013
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Czech Republic
---

# (CZE) Set up sales tax codes for intra-community VAT 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Before you can calculate and post intra-community value-added tax (VAT) for a purchase transaction, you must enable intra-community VAT. You must also set up sales tax codes and sales tax groups for payable VAT and receivable VAT.

To enable intra-community VAT, do the following:

  - Click **Accounts payable** \> **Setup** \> **Accounts payable parameters**. In the left pane, click **Ledger and sales tax**, and then, on the **Sales tax** FastTab, select the **Intra-community VAT** check box.

## Set up sales tax codes for intra-community VAT

To calculate intra-community VAT for purchase transactions, you must create two sales tax codes. One code must have a positive tax percentage, and the other code must have a negative tax percentage. Tax percentages are set up in the **Values** form. For more information about setting up tax percentages, see [Values of sales tax codes (form)](https://technet.microsoft.com/library/aa500790\(v=ax.60\)).

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax codes**.

2.  Click **New**, and then enter the sales tax code and a name for the positive tax percentage code.

3.  Enter a positive sales tax percentage and tax type.

4.  On the **General** FastTab, in the **References** field group, select a settlement period and a ledger posting group.

5.  Enter any additional information.

6.  Click **New**, and then enter the sales tax code and a name for the negative tax percentage code.

7.  Enter a negative sales tax percentage and tax type.

8.  On the **General** FastTab, select the **Negative sales tax percentage** check box, and then, in the **References** field group, select a settlement period and a ledger posting group.

9.  Enter any additional information.

## Set up sales tax groups for intra-community VAT

To calculate intra-community VAT for purchase transactions, you must create a sales tax group that contains a positive and a negative sales tax code.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax groups**.

2.  Click **New**, and then enter the name and a description of the sales tax group.

3.  On the **General** FastTab, enter information about the country/region, the sales tax group, rounding, and date validation.

4.  On the **Setup** FastTab, click **Add**, and then select the sales tax code that you created that has the positive sales tax percentage.

5.  Click **Add** again, and then select the corresponding sales tax code that has the negative sales tax percentage.

6.  Select the **Intra-community VAT** check box.

## See also

[(CZE) About intra-community VAT](cze-about-intra-community-vat.md)

[(CZE) About posting a purchase transaction that includes intra-community VAT](cze-about-posting-a-purchase-transaction-that-includes-intra-community-vat.md)

  


