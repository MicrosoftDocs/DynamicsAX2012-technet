---
title: Request and issue the letter of guarantee
TOCTitle: Request and issue the letter of guarantee
ms:assetid: 81059259-109c-4340-a607-56a0a0b53829
ms:mtpsurl: https://technet.microsoft.com/library/Hh209308(v=AX.60)
ms:contentKeyID: 36058355
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Extend letter of gurantee
- Letter of gurantee
audience: Application User
ms.search.region: Global
---

# Request and issue the letter of guarantee 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create letter of guarantee requests from a sales quotation, sales order, project quotation, project, or purchase order. When a request is created, you must submit it to the bank for approval. When you receive the bank’s approval, you can issue the letter of guarantee to the beneficiary.

Use the **Create quotation**, **Sales quotation**, **Sales order**, **Purchase order**, or **Project details** forms to request a letter of guarantee. After you make the request, use the **Letter of guarantee** form to submit the request to the bank for approval. Upon approval, you can use the **Letter of guarantee** form in **Bank** to issue the letter of guarantee to the beneficiary.

## Create the letter of guarantee request

Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**. Select a purchase order line and on the **Action Pane**, on the **Manage** tab, in the **Bank document** group, click **Letter of guarantee**.

–or–

Click **Sales and marketing** \> **Common** \> **Sales quotations** \> **All quotations**. Double-click a sales quotation line to open the **Sales quotation details** form. On the **Action Pane**, on the **Quotation** tab, in the **Bank document** group, click **Letter of guarantee**.

–or–

Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**. Double-click a sales order line to open the **Sales order details** form. On the **Action Pane**, on the **Manage** tab, in the **Bank document** group, click **Letter of guarantee**.

–or–

Click **Sales and marketing** \> **Common** \> **Sales quotations** \> **All quotations**. Double-click a project quotation line to open the **Project quotation details** form. On the **Action Pane**, on the **Quotation** tab, in the **Bank document** group, click **Letter of guarantee**.

–or–

Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Double-click a project line to open the **Project details** form. On the **Action Pane**, on the **Project** tab, click **Letter of guarantee**.

1.  In the **New** group, click **Request** to open the **Create letter of guarantee request** drop dialog.

2.  In the **Type** field, select the reason code for the letter of guarantee.

3.  In the **Value** field, enter the letter of guarantee value. In the **Currency** field, the currency of the letter of guarantee is updated.

4.  In the **Expiration date** field, select the date when the letter of guarantee will no longer be valid. The expiration date is defined in the letter of guarantee agreement and must be later than the current date.

5.  Click **OK** to create a letter of guarantee request. The **Facility status** field of the request is updated to **Requested**.

6.  Close the forms to save your changes.

## Submit the request to the bank

1.  Click **Cash and bank management** \> **Common** \> **Letters of guarantee**.

2.  On the left pane, select the request with the status **Request** and click **Submit to bank** to open the **Submit letter of guarantee to bank** drop dialog.

3.  In the **Bank account** field, select the bank account associated with the facility agreement.

4.  In the **Facility type** field, select the facility type for which the letter of guarantee is requested. The facility agreement number is updated in the **Facility agreement** field.

5.  Click **OK** to submit the request to the bank. The **Facility status** field of the request is updated to **Submitted to bank**.

## Receive the letter of guarantee from the bank

1.  Click **Cash and bank management** \> **Common** \> **Letters of guarantee**.

2.  On the left pane, select the request with the status **Submitted to bank** and click **Receive from bank** to open the **Receive letter of guarantee from bank** drop dialog.

3.  In the **Bank number** field, enter the bank account number as it appears in the letter of guarantee. The monetary value and expiration date of the letter of guarantee are updated in the **Value** and **Expiration date** fields.

4.  In the **Margin** field, enter the margin amount reserved by the bank. The margin amount is calculated as the value of the letter of guarantee multiplied by the percentage specified in the **Cash margin** field in the **Bank facility agreements** form and displayed in this field. If you have specified a fixed amount in the **Bank facility agreements** form, the amount is displayed here. You can modify the amount if required.

5.  In the **Expense** field, enter the miscellaneous charges incurred on the letter of guarantee. The expense amount is calculated as the value of the letter of guarantee multiplied by the percentage specified in the **Issuance commission** field in the **Bank facility agreements** form and displayed in this field. If you have specified a fixed amount in the **Bank facility agreements** form, the amount is displayed here. You can modify this amount if required.

6.  Click **OK** to receive the letter of guarantee from the bank. Journal entries are posted to the accounts specified in the **Bank documents posting profile** form using the daily journal specified in the **Transaction journal** field in the **Cash and bank management parameters** form. The **Facility status** field of the request is updated to **Received from bank**.

## Request to issue the letter of guarantee

Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**. Select a purchase order line and on the **Action Pane**, on the **Manage** tab, in the **Bank document** group, click **Letter of guarantee**.

–or–

Click **Sales and marketing** \> **Common** \> **Sales quotations** \> **All quotations**. Double-click a sales quotation line to open the **Sales quotation details** form. On the **Action Pane**, on the **Quotation** tab, in the **Bank document** group, click **Letter of guarantee**.

–or–

Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**. Double-click a sales order line to open the **Sales order details** form. On the **Action Pane**, on the **Manage** tab, in the **Bank document** group, click **Letter of guarantee**.

–or–

Click **Sales and marketing** \> **Common** \> **Sales quotations** \> **All quotations**. Double-click a project quotation line to open the **Project quotation details** form. On the **Action Pane**, on the **Quotation** tab, in the **Bank document** group, click **Letter of guarantee**.

–or–

Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Double-click a project line to open the **Project details** form. On the **Action Pane**, on the **Project** tab, click **Letter of guarantee**.

1.  Click **Give to beneficiary** to open the **Give letter of guarantee to beneficiary?** drop dialog.

2.  Click **OK** to create a request to issue the letter of guarantee. The **Facility status** field is updated to **Request give to beneficiary**.

## Issue the letter of guarantee to the beneficiary

1.  Click **Cash and bank management** \> **Common** \> **Letters of guarantee**.

2.  On the left pane, select the request with the status **Request give to beneficiary** and click **Give to beneficiary** to open the **Give letter of guarantee to beneficiary?** drop dialog.

3.  Click **OK** to issue the letter of guarantee to the beneficiary. The status of the request is updated to **Given to beneficiary**.

## See also

[Create a letter of guarantee request for a new project](create-a-letter-of-guarantee-request-for-a-new-project.md)

[Create a letter of guarantee request for a purchase order](create-a-letter-of-guarantee-request-for-a-purchase-order.md)

[Create a letter of guarantee request for a project quotation](create-a-letter-of-guarantee-request-for-a-project-quotation.md)

[Create a letter of guarantee request for a sales order](create-a-letter-of-guarantee-request-for-a-sales-order.md)

[Create a letter of guarantee request for a sales quotation](create-a-letter-of-guarantee-request-for-a-sales-quotation.md)

[Liquidate, extend, or cancel a letter of guarantee](liquidate-extend-or-cancel-a-letter-of-guarantee.md)

[Letter of guarantee (form)](https://technet.microsoft.com/library/hh227662\(v=ax.60\))

[Increase or decrease the letter of guarantee value](increase-or-decrease-the-letter-of-guarantee-value.md)

  


