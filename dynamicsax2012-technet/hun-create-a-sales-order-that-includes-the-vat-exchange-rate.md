---
title: (HUN) Create a sales order that includes the VAT exchange rate
TOCTitle: (HUN) Create a sales order that includes the VAT exchange rate
ms:assetid: b6daee02-d1fa-441d-94dc-96613b0e549c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664358(v=AX.60)
ms:contentKeyID: 49385446
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (HUN) Create a sales order that includes the VAT exchange rate [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Tax-related financial documents must contain monetary amounts in local currency. These financial documents include the following:

  - Invoices

  - Free text invoices

  - Project invoices

  - Credit notes

  - Corrective invoices

  - Purchase orders

Companies are not required to calculate value-added tax (VAT) amounts based on the National Bank currency rates. Instead, you can create exchange rates to use to calculate VAT in other currencies. The exchange rates that you use to calculate VAT can differ from the exchange rates that you use for general accounting.

Use this procedure to create and post a sales order in which you specify the VAT exchange rate.

**Prerequisites**

Before you can use an exchange rate for calculating VAT that differs from the exchange rate that you use for general accounting, you must perform the following steps.

1.  Set up exchange rate types for calculating VAT. For more information, see [(HUN) Currency exchange rate types (form)](https://technet.microsoft.com/en-us/library/jj664400\(v=ax.60\)).

2.  Click **General ledger** \> **Setup** \> **General ledger parameters**.
    
      - In the **Sales tax** area, on the **Tax options** FastTab, in the **Bank** field group, select the **Bank exchange rate** check box.
    
      - Select exchange rate types in the **Sales tax receivable exchange rate type** and **Sales tax payable exchange rate type** fields.

3.  Set up exchange rates for sales tax. For more information, see [(HUN) Set up exchange rates for calculating VAT](hun-set-up-exchange-rates-for-calculating-vat.md).

4.  Set up accounts for posting sales tax differences. For more information, see [(HUN) Ledger posting groups (modified form)](https://technet.microsoft.com/en-us/library/jj664253\(v=ax.60\)).

## Create and post a sales order that includes the VAT exchange rate

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**. On the **Action Pane**, on the **Sales order** tab, in the **New** group, click **Sales order**.

2.  In the **Create sales order** form, select a customer, enter any additional information, and click **OK**.

3.  In the **Sales order** form, on the **Sales order lines** FastTab, enter the details for the sales order line. For more information, see [Sales orders (form)](https://technet.microsoft.com/en-us/library/aa585863\(v=ax.60\)).

4.  On the **Action Pane**, on the **Sell** tab, in the **Tax** group, click **Sales tax**.

5.  In the **Temporary sales tax transactions** form, in the **Date of VAT register** field, select the VAT register date, and then, in the **Sales tax exchange rate** field, modify the sales tax exchange rate.

6.  Close the **Temporary sales tax transactions** form.

7.  In the **Sales order** form, continue entering sales order lines or, if the order is complete, continue processing the sales order according to your organization’s established procedures.

When you create and post the sales invoice, any differences in amounts that are caused by the difference between the exchange rates that you use in general accounting and the exchange rates that you use to calculate VAT are automatically posted to specified accounts. You can specify these accounts in the **Ledger posting groups** form.

## See also

[(HUN) Temporary sales tax transactions (modified form)](https://technet.microsoft.com/en-us/library/jj664221\(v=ax.60\))

[(HUN) Set up exchange rates for calculating VAT](hun-set-up-exchange-rates-for-calculating-vat.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

