---
title: Liquidate, extend, or cancel a letter of guarantee
TOCTitle: Liquidate, extend, or cancel a letter of guarantee
ms:assetid: fbcadb03-13c6-4a10-aa41-927a44b84e1e
ms:mtpsurl: https://technet.microsoft.com/library/Hh227572(v=AX.60)
ms:contentKeyID: 36060083
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Letter of gurantee
- Liquidate a letter of guarantee
audience: Application User
ms.search.region: Global
---

# Liquidate, extend, or cancel a letter of guarantee 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can request to cash out a letter of guarantee, extend its validity, or cancel the agreement. Use the **Create quotation**, **Sales quotation**, **Sales order**, **Purchase order**, or **Project details** forms to initiate requests for cashing out, extending the validity, or canceling the letter of guarantee.

After initiating the request, use the **Letter of guarantee** form in **Bank** to cash out, extend, or cancel a letter of guarantee.

## Request to cash out a letter of guarantee

You can request to cash out a letter of guarantee that has a status of **Given to beneficiary**.

Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**. Select a purchase order line and on the **Action Pane**, on the **Manage** tab, in the **Bank document** group, click **Letter of guarantee**.

–or–

Click **Sales and marketing** \> **Common** \> **Sales quotations** \> **All quotations**. Double-click a sales quotation line to open the **Sales quotation** form. On the **Action Pane**, on the **Quotation** tab, in the **Bank document** group, click **Letter of guarantee**.

–or–

Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**. Double-click a sales order line to open the **Sales order details** form. On the **Action Pane**, on the **Manage** tab, in the **Bank document** group, click **Letter of guarantee**.

–or–

Click **Project management and accounting** \> **Common** \> **Quotations** \> **Project quotations**. Double-click a project quotation line to open the **Project quotation details** form. On the **Action Pane**, on the **Quotation** tab, in the **Bank document** group, click **Letter of guarantee**.

–or–

Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Double-click a project line to open the **Project details** form. On the **Action Pane**, on the **Project** tab, click **Letter of guarantee**.

1.  Click **Liquidate** to open the **Liquidate letter of guarantee** drop dialog.

2.  Click **OK** to request that the letter of guarantee value be cashed out. The **Facility status** field of the request is updated to **Request liquidate**.

## Liquidate a letter of guarantee

To liquidate a letter of guarantee, the beneficiary must submit the original letter of guarantee and inform the bank of the principal’s default prior to the expiration date. The bank then pays the amount due to the account of the beneficiary, as agreed in the letter of guarantee.

1.  Click **Cash and bank management** \> **Common** \> **Letters of guarantee**.

2.  In the left pane, select the request with the status **Request liquidate** and click **Liquidate** to open the **Liquidate letter of guarantee** drop dialog.
    
    The **Value** field displays the total current value. If the value is increased or decreased, the updated value is displayed.
    
    The margin amount is calculated as the amount specified in the **Value** field multiplied by the percentage specified in the **Cash margin** field in the **Bank facility agreements** form and displayed as **Margin**. If you have specified a fixed amount instead of a percentage in the **Bank facility agreements** form, the fixed amount is displayed in this field.
    
    The **Expense** field displays the total of all incurred expenses as current expenses.

3.  Click **OK** to liquidate the letter of guarantee to the beneficiary. Journal entries are posted to the accounts specified in the **Bank documents posting profile** form using the daily journal specified in the **Transaction journal** field in the **Cash and bank management parameters** form. The status of the request is updated to **Liquidated**.
    
    Once liquidated, you cannot perform any further transactions on the letter of guarantee.

## Request to extend the validity of the letter of guarantee

You can request to extend the validity of a letter of guarantee that has a status of **Given to beneficiary**.

Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**. Select a purchase order line and on the **Action Pane**, on the **Manage** tab, in the **Bank document** group, click **Letter of guarantee**.

–or–

Click **Sales and marketing** \> **Common** \> **Sales quotations** \> **All quotations**. Double-click a sales quotation line to open the **Sales quotation details** form. On the **Action Pane**, on the **Quotation** tab, in the **Bank document** group, click **Letter of guarantee**.

–or–

Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**. Double-click a sales order line to open the **Sales order details** form. On the **Action Pane**, on the **Manage** tab, in the **Bank document** group, click **Letter of guarantee**.

–or–

Click **Project management and accounting** \> **Common** \> **Quotations** \> **Project quotations**. Double-click a project quotation line to open the **Project quotation details** form. On the **Action Pane**, on the **Quotation** tab, in the **Bank document** group, click **Letter of guarantee**.

–or–

Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Double-click a project line to open the **Project details** form. On the **Action Pane**, on the **Project** tab, click **Letter of guarantee**.

1.  Click **Extend letter of guarantee** to open the **Extend letter of guarantee expiration date** drop dialog.

2.  In the **New expiration date** field, enter the new expiration date for extending the letter of guarantee.

3.  Click **OK**. The **Facility status** field of the request is updated to **Request extend**.

## Extend a letter of guarantee

1.  Click **Cash and bank management** \> **Common** \> **Letters of guarantee**.

2.  On the left pane, select the request with the status **Request extend**, and click **Extend** to open the **Extend letter of guarantee expiration date** drop dialog. The **Expiration date** field displays the expiration date specified when the request to extend the letter of guarantee was made.

3.  In the **Expense** field, enter the extension commission charged by the bank. The expense amount is calculated as the amount specified in the **Value** field multiplied by the percentage specified in the **Extension commission** field in the **Bank facility agreements** form and displayed in this field. If you specified a fixed amount instead of a percentage in the **Bank facility agreements** form, the fixed amount is displayed in this field. You can modify this amount if required.

4.  Click **OK** to extend the validity of the letter of guarantee. Journal entries are posted to the accounts specified in the **Bank documents posting profile** form using the daily journal specified in the **Transaction journal** field in the **Cash and bank management parameters** form. The status of the request is updated to **Extended**.

## Request to cancel the letter of guarantee

You can request to cancel a letter of guarantee with a status of **Given to beneficiary**. A letter of guarantee can be canceled when the validity of the letter ends. To cancel a letter of guarantee, the beneficiary must submit the original letter of guarantee and request that the bank cancels it. Once it is canceled, you cannot perform any further transactions on the letter of guarantee.

Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**. Select a purchase order line and on the **Action pane**, on the **Manage** tab, in the **Bank document** group, click **Letter of guarantee**.

–or–

Click **Sales and marketing** \> **Common** \> **Sales quotations** \> **All quotations**. Double-click a sales quotation line to open the **Sales quotation details** form. On the **Action Pane**, on the **Quotation** tab, in the **Bank document** group, click **Letter of guarantee**.

–or–

Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**. Double-click a sales order line to open the **Sales order details** form. On the **Action Pane**, on the **Manage** tab, in the **Bank document** group, click **Letter of guarantee**.

–or–

Click **Project management and accounting** \> **Common** \> **Quotations** \> **Project quotations**. Double-click a project quotation line to open the **Project quotation details** form. On the **Action Pane**, on the **Quotation** tab, in the **Bank document** group, click **Letter of guarantee**.

–or–

Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Double-click a project line to open the **Project details** form. On the **Action Pane**, on the **Project** tab, click **Letter of guarantee**.

1.  Click **Cancel** to open the **Cancel letter of guarantee** dialog.

2.  In the **Cancellation reason** field, enter a reason for requesting cancellation of the letter of guarantee.

3.  Click **OK** to request cancellation of the letter of guarantee. The **Facility status** field of the request is updated to **Request cancel**.

## Cancel a letter of guarantee

When the purpose of the letter of guarantee no longer applies, you can end the agreement. After canceling an agreement, you can take no further action on the letter of guarantee. The bank returns the margin amount when it cancels a letter of guarantee.

1.  Click **Cash and bank management** \> **Common** \> **Letters of guarantee**.

2.  Click **Cancel** on the **Letter of guarantee** form to open the **Cancel letter of guarantee** dialog. The **Margin** field displays the payment amount reserved by the bank. This amount is refunded to the principal.

3.  Click **OK** to cancel the letter of guarantee. Journal entries are posted to the accounts specified in the **Bank documents posting profile** form using the daily journal specified in the **Transaction journal** field in the **Cash and bank management parameters** form. The status of the request is updated to **Cancelled**.

## See also

[Request and issue the letter of guarantee](request-and-issue-the-letter-of-guarantee.md)

[Increase or decrease the letter of guarantee value](increase-or-decrease-the-letter-of-guarantee-value.md)

[Letter of guarantee (form)](https://technet.microsoft.com/library/hh227662\(v=ax.60\))

  


