---
title: Due date-type events
TOCTitle: Due date-type events
ms:assetid: e80d6489-fcd8-4174-a347-f5a9b1b3080c
ms:mtpsurl: https://technet.microsoft.com/library/Aa573196(v=AX.60)
ms:contentKeyID: 46687571
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Due date-type events 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Due date events are part of the rules that trigger alerts when a due date changes. The following table explains the options that are available for due date events.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Option</p></th>
<th><p>When an alert is triggered</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>is due in</strong></p></td>
<td><p>This many days before the date that is stated in your business data. For example, a purchase order has a delivery date of October 16, and the <strong>is due in</strong> option is set to two weeks. Therefore, the rule triggers an alert on October 2.</p></td>
</tr>
<tr class="even">
<td><p><strong>is due</strong></p></td>
<td><p>On the date that is specified in your business data.</p></td>
</tr>
<tr class="odd">
<td><p><strong>was due this amount of time ago</strong></p></td>
<td><p>This many days after the date that is stated in your business data.</p></td>
</tr>
</tbody>
</table>


You are also alerted if your business data changes in such a way that the due date interval becomes less than the number of days that you originally entered as the due date interval. For example, you have created a rule that alerts you two weeks before the delivery date of any purchase order. If a purchase order is created that has a delivery date that is only one week away, you receive an alert when the purchase order is created, because the purchase order is in the two-week period that you defined.


> [!NOTE]
> <P>Generally, a due date alert rule triggers only one alert, and this occurs when the due date arrives. However, if the due date is changed after an alert is triggered, a new alert is triggered on the new due date.</P>



## Example: Is due in

For a project that you manage, it is very important that you receive deliveries on time. Purchases are handled through the purchasing department of your company, but you want to follow up on deliveries for your project two weeks before the actual delivery date.

Therefore, you create a rule that triggers an alert when the delivery date of purchase orders for your project is two weeks away. You also specify that the alerts are limited to deliveries for your project.

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Select a record. On the **Action Pane**, click **Edit**.

3.  In the **Purchase order** form, expand the **Purchase order header** tab. Right-click the **Delivery date** field, and then select **Create alert rule**.

4.  In the **Create alert rule** form, follow these steps to create the rule:
    
      - Under **Send email alerts for job status changes**, in the **Field** list, select **Delivery date**.
    
      - Under **Send email alerts for job status changes**, in the **Event** list, select **is due in**, and then select **2 weeks**.
    
      - Under **Alert me for**, select **Only records that match the selected filter**, and then click **Select** to open the **Inquiry** dialog box. In the **Inquiry** dialog box, specify purchase orders for a specific project.
    
      - Under **Alert me until**, select **No end date**. Alerts continue to be triggered indefinitely. The rule never becomes inactive.
    
      - Under **Alert me with**, accept or modify the title of the alert. Optionally, you can write a message that is sent when the alert is triggered.

5.  Click **OK** to activate the rule.

## Example: Is due

You want to monitor the quotations that are issued from your company. On the expiration date of the quotations, you want to remember to check the details.

Therefore, you create a rule that triggers an alert on the expiration date of each project quotation.

1.  Click **Project management and accounting** \> **Common** \> **Quotations** \> **Project quotations**.

2.  Select a record. On the **Action Pane**, click **Edit**.

3.  On the **Action Pane**, in the **Show** group, click **Header View**.

4.  Expand the **General** tab. Right-click the **Expiration date** field, and then select **Create alert rule**.

5.  In the **Create alert rule** form, follow these steps to create the rule:
    
      - Under **Send email alerts for job status changes**, in the **Field** list, select **Expiration date**.
    
      - Under **Send email alerts for job status changes**, in the **Event** list, select **is due**.
    
      - Under **Alert me for**, select **All records in %1** to be alerted about the expiration date of all project quotations.
    
      - Under **Alert me until**, select **No end date**. Alerts continue to be triggered indefinitely. The rule never becomes inactive.
    
      - Under **Alert me with**, accept or modify the title of the alert. Optionally, you can write a message that is sent when the alert is triggered.

6.  Click **OK** to activate the rule.

## Example: Was due this amount of time ago

Your company receives multiple orders from one customer, and the total amount for the sales orders is large. You want to make sure that the customer pays the invoices, and you want to be alerted four days after the confirmed receipt date of the orders.

Therefore, you create a rule that triggers an alert four days after the confirmed receipt date. You also specify that you want to be alerted only about orders that are actually invoiced.

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Select an open order. On the **Action Pane**, click **Edit**.

3.  On the **Action Pane**, in the **Show** group, click **Header View**.

4.  Expand the **Delivery** tab. Right-click the **Confirmed receipt date** field, and then select **Create alert rule**.

5.  In the **Create alert rule** form, follow these steps to create the rule:
    
      - Under **Send email alerts for job status changes**, in the **Field** list, select **Confirmed receipt date**.
    
      - Under **Send email alerts for job status changes**, in the **Event** list, select **was due this amount of time ago**, and then select **4 calendar days**.
    
      - Under **Alert me for**, select **Only records in %1 that match the selected filter**, and then click **Select** to open the **Inquiry** dialog box. In the **Inquiry** dialog box, specify sales orders that are for the customer, and that have the status **Invoiced**.
    
      - Under **Alert me until**, select **No end date**. Alerts continue to be triggered indefinitely. The rule never becomes inactive.
    
      - Under **Alert me with**, accept or modify the title of the alert. Optionally, you can write a message that is sent when the alert is triggered.

6.  Click **OK** to activate the rule.

## See also

[Update-type events](update-type-events.md)

[Create-type and delete-type events](create-type-and-delete-type-events.md)

[Add additional tables to advanced queries](add-additional-tables-to-advanced-queries.md)

  


