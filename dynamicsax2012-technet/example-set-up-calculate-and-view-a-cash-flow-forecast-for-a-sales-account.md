---
title: 'Example: Set up, calculate, and view a cash flow forecast for a sales account'
TOCTitle: 'Example: Set up, calculate, and view a cash flow forecast for a sales account'
ms:assetid: 6805ef6f-2650-47cd-a2d4-9a3516abe8bb
ms:mtpsurl: https://technet.microsoft.com/library/Hh242599(v=AX.60)
ms:contentKeyID: 36057949
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Example: Set up, calculate, and view a cash flow forecast for a sales account 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Set up cash flow forecasts** form to set up main accounts or budget accounts that are used in cash flow forecasts. In the cash flow forecast, future transactions are estimated based on information that is already registered, such as invoices that are not yet paid, expected sales tax payments, and budget register entries.

This example describes how to set up, calculate, and view a cash flow forecast for a sales account.

1.  Click **General ledger** \> **Setup** \> **Chart of accounts** \> **Chart of accounts**. Select a chart of accounts. Select a main account that has a main account type of **Asset** and then click **Edit** on the **Main accounts** tab. Select **Companies** in the **Select the level of main account to display** field and select a legal entity. On the **Setup** tab, click **Cash flow forecast**.

2.  In the **Percent** field, enter 100.

3.  In the **Terms of payment** field, select the terms of payment.

4.  In the **Main account** field, select the cash account to which the sales account is linked for the cash flow forecast.

5.  Close the **Set up cash flow forecasts** form.

6.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

7.  Create a sales order of 1,000 for a customer whose **Terms of payment** field value is the same as in step 3.

8.  Calculate the cash flow forecast. (Click **General ledger** \> **Periodic** \> **Currency requirement** \> **Calculate cash flow forecasts**.) For more information, see [Calculate, view, and print a cash flow forecast](calculate-view-and-print-a-cash-flow-forecast.md).

9.  Click **General ledger** \> **Common** \> **Main accounts**.

10. Select the cash account that you selected in step 4.

11. On the **Action Pane**, in the **Related information** group, click **Cash flow forecasts**.

  


