---
title: Set up notification and cancellation for delayed orders
TOCTitle: Set up notification and cancellation for delayed orders
ms:assetid: fce7d023-2dc0-47d7-9ff3-bbefc76df123
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn497861(v=AX.60)
ms:contentKeyID: 62200194
ms.date: 05/01/2014
mtps_version: v=AX.60
f1_keywords:
- delay
- backorder
- delayed
- automatic cancelation
- automatic cancellation
- automatic notification
audience: Application User
ms.search.region: Global
---

# Set up notification and cancellation for delayed orders 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

When a customer's order cannot be shipped on time, a company can automatically send notification email messages to the customer to explain the order status and give the customer the opportunity to cancel the order. If the delay extends beyond a specified threshold, the order can be canceled automatically. This topic describes how to set up automatic notification and cancellation for delayed orders.

Up to three email messages can be sent at specified time intervals:

1.  First cancellation notice – The customer can decide to cancel the order.

2.  Second cancellation notice – The customer can decide to cancel the order.

3.  Final cancellation notice – The system cancels the order, and the customer is informed of the cancellation.

You can exempt individual customers and products from the automatic notification and cancellation process.

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Required setup steps</p></td>
<td><p>Set up email parameters for your company. For more information, see <a href="configure-email-functionality-in-microsoft-dynamics-ax.md">Configure email functionality in Microsoft Dynamics AX</a>.</p></td>
</tr>
</tbody>
</table>


## 1\. Set up email notification types

You must set up a notification type for each of the three cancellation notices (first, second, and final) and modify the text in the notification templates to meet your company's requirements.

To set up email notification types and modify email templates, follow these steps.

1.  Click **Retail** \> **Setup** \> **Parameters** \> **Retail Email notification profile**.

2.  On the **Action Pane**, click **New**.

3.  Enter a name and description for the notification profile, and select the **Active** check box if you're ready to make the profile active.

4.  In the **Email notification type** list, add the following notification types:
    
      - **First automatic cancellation notice**
    
      - **Second automatic cancellation notice**
    
      - **Final automatic cancellation notice**

5.  Select the **Active** check box next to each notification type that you're ready to make active.

6.  Right-click one of the entries in the **E-mail ID** column, and then select **View details** to open the **E-mail templates** form.

7.  Find the email ID for the first automatic cancellation notice, and make sure that the information in the **Sender name** and **Sender e-mail** fields is correct.

8.  Click **E-mail message** to open the **E-mail editor** form. You can modify the text in the email template as you require. Close the form, and click **Yes** to save your changes.

9.  Repeat steps 6 and 7 to make any required changes to the information for the second and final notices.

## 2\. Set automatic notification and cancellation parameters

Next, you must enable automatic notification and cancellation in the call center parameters, and specify the timing of the notifications.

To set the automatic notification and cancellation parameters, follow these steps.

1.  Click **Call center** \> **Setup** \> **Call center parameters**.

2.  On the **Automatic notification and cancellation** FastTab, select the **Automatic notification and cancellation processing** check box to enable automatic notification and cancellation.

3.  In the **First notice days from start**, **Second notice days from start**, and **Cancellation notice days from start** fields, enter the number of days that should pass between the order date and the date that each type of notification is sent to the customer.

## 3\. Optional: Set up exemptions for customers and products

You can exempt individual customers and products from the automatic notification and cancellation process.

To set up an exemption for a customer, follow these steps.

1.  Click **Call center** \> **Common** \> **All customers**.

2.  Double-click a customer record to open it, and then, on the **Action Pane**, click **Edit**.

3.  On the **Miscellaneous details** FastTab, under **Automatic notification and cancelation processing**, select the **Automatic notification and cancellation exempt** check box.

To set up an exemption for a product, follow these steps.

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  Double-click a product record to open it, and then, on the **Action Pane**, click **Edit**.

3.  On the **Sell** FastTab, under **Automatic notification and cancelation processing**, select the **Automatic notification and cancellation exempt** check box.

## 4\. Optional: Set up exemption from event tracking

If logging of order events is enabled, the system logs an event every time that an automatic notification email message is sent. If you don't want to track this type of event, you can set up an exemption.

To exempt automatic notification and cancellation from event logging, follow these steps.

1.  Click **Sales and marketing** \> **Setup** \> **Events** \> **Order events**.

2.  For each user, on the **Automatic notification and cancellation** FastTab, select the **Exempt** check box.

For more information about order events, see [Set up order events](set-up-order-events.md).

## 5\. Run a batch job for automatic notification and cancellation

You must run a batch job to process automatic notification and cancellation events. When this batch job is run, notification email messages are sent to customers whose orders are past the threshold for first, second, or final notification. In the case of final notifications, the system also cancels the sales orders.

To run a batch job for automatic notification and cancellation, follow these steps.

1.  Click **Call center** \> **Periodic** \> **Process automatic notification and cancelation events**.

2.  On the **General** tab, set the start and end dates for the batch job.

3.  On the **Batch** tab, set the parameters for the batch job.

4.  Click **OK** to run the batch job. You receive a message that states which notifications were sent and which sales orders were canceled, if any were canceled.

## Related tasks

[Configure email functionality in Microsoft Dynamics AX](configure-email-functionality-in-microsoft-dynamics-ax.md)

[Set up order events](set-up-order-events.md)

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Configuration keys</strong></p></td>
<td><p><strong>Retail Headquarters</strong> configuration key</p>
<p><strong>Call center</strong> configuration key</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>System administrator (to set email parameters and create email notification types)</p>
<p>Sales manager (to set call center parameters, configure order events, and run automatic notification and cancellation batch jobs)</p></td>
</tr>
</tbody>
</table>

  


