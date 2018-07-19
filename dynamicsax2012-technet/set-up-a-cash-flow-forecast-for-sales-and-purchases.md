---
title: Set up a cash flow forecast for sales and purchases
TOCTitle: Set up a cash flow forecast for sales and purchases
ms:assetid: acaf3c6d-e030-4d18-975a-7bd31be9c21a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa498576(v=AX.60)
ms:contentKeyID: 36058921
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up a cash flow forecast for sales and purchases 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can complete the required setup for the sales and purchase cash flow forecast, or you can create a more extensive setup. You can also budget sales and purchases by customer and vendor group.

## Required setup

Complete the following steps to set up a cash flow forecast that includes sales and purchases.

1.  Click **Accounts receivable** \> **Setup** \> **Customer posting profiles**.

2.  On the **Setup** tab, in the **Settle account** field, select the account to use as the liquidity ledger account for customer payments.

3.  Click **Accounts payable** \> **Setup** \> **Vendor posting profiles**.

4.  On the **Setup** tab, in the **Settle account** field, select the account to use as the liquidity ledger account for payments to vendors.

The cash flow forecasts (future transactions) are calculated based on the delivery dates of sales or purchase lines. If the delivery date has passed, the cash flow forecasts are calculated by the system date.

## Additional setup

You can calculate the forecast for sales and purchases using additional setup options in both Accounts receivable and Accounts payable.

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  Click **Ledger and sales tax** and select values as appropriate for the cash flow forecast.

3.  In the **Period between delivery and invoicing** field, select a value that represents the interval between the sales order delivery date and the expected invoicing of the order.

4.  In the **Invoicing period** field, select a value that represents the interval between future sales transactions and the invoice date (for example, Net + 1 days terms of payment). This value is applied to budget lines, open sales orders, and free text invoices.

5.  In the **Terms of payment** field, select default terms of payment for sales. This value is used for cash flow calculations except when the terms of payment are specified on the sales order, customer account, or customer group.

6.  In the **Settle period** field, select the value that represents the expected delay between the due date and the date of payment.

7.  In the **Settle account** field, select the liquidity account that is the default account to which customer payments are posted.

8.  In the **Allocation key** field, select the value that reduces the effect of the budget in the cash flow forecast as sales orders are created.

9.  Complete steps 2 through 8 for the **Accounts payable parameters** form. (Click **Accounts payable** \> **Setup** \> **Accounts payable parameters**.)

## Create a cash flow forecast for a customer group or vendor group

The cash flow forecast can also consider different customer or vendor groups.

1.  To set up cash flow parameters for customer groups, use the **Customer groups** form. (Click **Accounts receivable** \> **Setup** \> **Customers** \> **Customer groups**.)

2.  In the **Terms of payment** field, select the terms of payment that are used for customer accounts in the customer group.
    
    If terms of payment are specified for the sales order or the customer account, these terms have higher priority than the terms of payment for the customer group.

3.  In the **Settle period** field, select the value that represents the expected delay between the payment due date and the date on which you expect the payment to be completed.

4.  To set up cash flow parameters for vendor groups, use the **Vendor groups** form. (Click **Accounts payable** \> **Setup** \> **Vendors** \> **Vendor groups**.) Repeat steps 2 and 3.

  


