---
title: Update-type events
TOCTitle: Update-type events
ms:assetid: b95b53e3-db9b-4f0b-8c49-55a5c88a3d39
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa498848(v=AX.60)
ms:contentKeyID: 46687566
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Update-type events 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Update events are part of the rules that trigger alerts when data is changed in the application. The following table explains the options that are available for update events.

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
<td><p><strong>has changed</strong></p></td>
<td><p>The current value of the selected field changes.</p></td>
</tr>
<tr class="even">
<td><p><strong>is set to:</strong></p></td>
<td><p>The current value of the selected field is set to a specific value.</p>
<p>The value can be set either when the record is created or when you change the value from another value.</p></td>
</tr>
<tr class="odd">
<td><p><strong>has been postponed</strong></p></td>
<td><p>The current value of the selected field changes to a later date. For example, a postponement from August 10 to August 25 triggers an alert.</p></td>
</tr>
<tr class="even">
<td><p><strong>has been postponed until at the earliest:</strong></p></td>
<td><p>The current value of the selected field changes to a later date.</p>
<p>The date is an absolute date and is specified in the alert rule.</p>
<p>For example, a postponement from August 10 to August 25 or a later date triggers an alert, but a postponement from August 10 to August 24 does not.</p></td>
</tr>
<tr class="odd">
<td><p><strong>is set to an earlier date</strong></p></td>
<td><p>The current value of the selected field changes to a date that is earlier than the date that was originally specified in the field. For example, a change from August 25 to August 10 triggers an alert.</p></td>
</tr>
<tr class="even">
<td><p><strong>is set to a date earlier than:</strong></p></td>
<td><p>The current value of the selected field changes to a date that is earlier than both the date that was originally specified in the field and the date that is specified in the alert rule.</p>
<p>For example, the date that is specified in the alert rule is August 15. In this case, a change from August 25 to August 10 triggers an alert, but a change from August 25 to August 20 does not.</p></td>
</tr>
<tr class="odd">
<td><p><strong>has decreased below:</strong></p></td>
<td><p>The current value of the selected field changes to a value that is less than an absolute limit that you specify.</p></td>
</tr>
<tr class="even">
<td><p><strong>has increased above:</strong></p></td>
<td><p>The current value of the selected field changes to a value that is more than an absolute limit that you specify.</p></td>
</tr>
</tbody>
</table>


## Later dates

Later dates are a relative concept for update-type events. You can set up an alert rule that triggers an alert if a date in the past changes to a later date.

The following scenarios are examples of later date events.

  - A postponement from August 10 to August 25 triggers an alert, even though the current date is September 20.

  - A change from August 25 to August 10 triggers an alert, even though the current date is August 15.

## Example: Has changed

You work in a company that uses contract workers extensively. When a contract worker is hired, the start date of his or her employment is activated. Then, when the worker stops working for the company, the HR department enters the date of termination. If the same worker is employed again, the start date is reactivated. You want to be alerted when people leave the company or start to work there again. Therefore, you create a rule that triggers an alert when the employment dates of any worker change.

1.  Click **Human resources** \> **Common** \> **Workers** \> **Workers**.

2.  Select a worker. On the **Action Pane**, on the tab, in the group, click **Edit**.

3.  In the **Worker** form, click the **Employment** link, and then expand the **Employment details** tab.

4.  Right-click the **Employment start date** field, and then select **Create alert rule**.

5.  In the **Create alert rule** form, follow these steps to create the rule:
    
      - Under **Send email alerts for job status changes**, in the **Field** list, select **Employment start date**.
    
      - Under **Send email alerts for job status changes**, in the **Event** list, select **has changed**.
    
      - Under **Alert me for**, select **All records in %1**. An alert is triggered for any employee whose status changes.
    
      - Under **Alert me until**, select **No end date**. Alerts continue to be triggered indefinitely. The rule never becomes inactive.
    
      - Under **Alert me with**, verify or adjust the title of the alert. Optionally, you can write a message that is sent when the alert is triggered.

6.  Click **OK** to activate the rule.

7.  Repeat steps 3 through 5 for the **Employment end date** field.

## Example: Is set to

You work in the sales department of a company where the number of customer returns has become a major problem. You want to be alerted about all instances of returned goods, so that you can immediately start to investigate why the goods are returned. Therefore, you create a rule that triggers an alert if the **Status** field of any sales order is changed to **Canceled**.

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Select a sales order. On the **Action Pane**, click **Edit**.

3.  On the **Action Pane**, on the **Sales order** tab, in the **Show** group, click **Header View**.

4.  Expand the **General** tab. Right-click the **Status** field, and then select **Create alert rule**.

5.  In the **Create alert rule** form, follow these steps to create the rule:
    
      - Under **Send email alerts for job status changes**, in the **Field** list, select **Status**.
    
      - Under **Send email alerts for job status changes**, in the **Event** list, select **is set to:**, and then select **Canceled**.
    
      - Under **Alert me for**, select **All records in %1**. An alert is triggered for any sales order for which the **Status** field changes to **Canceled**.
    
      - Under **Alert me until**, select **No end date**. Alerts continue to be triggered indefinitely. The rule never becomes inactive.
    
      - Under **Alert me with**, accept or modify the title of the alert. Optionally, you can write a message that is sent when the alert is triggered.

6.  Click **OK** to activate the rule.

## Example: Has been postponed

Sometimes, the delivery of purchased parts that are required in your company's production is delayed. You want to be alerted when the delivery of a purchase order is delayed, so that you can check whether the delay affects the fulfillment of sales orders that depend on the purchased items. Therefore, you create a rule that triggers an alert if the value in the **Delivery date** field of any purchase order is changed to a later date.

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Select a purchase order. On the **Action Pane**, click **Edit**.

3.  On the **Action Pane**, on the **Purchase order** tab, in the **Show** group, click **Header View**.

4.  Expand the **Delivery** tab. Right-click the **Delivery date** field, and then select **Create alert rule**.

5.  In the **Create alert rule** form, follow these steps to create the rule:
    
      - Under **Send email alerts for job status changes**, in the **Field** list, select **Delivery date**.
    
      - Under **Send email alerts for job status changes**, in the **Event** list, select **has been postponed**.
    
      - Under **Alert me for**, select **All records in %1**. An alert is triggered for any purchase order for which the value in the **Delivery date** field is changed to a later date.
    
      - Under **Alert me until**, select **No end date**. Alerts continue to be triggered indefinitely. The rule never becomes inactive.
    
      - Under **Alert me with**, accept or modify the title of the alert. Optionally, you can write a message that is sent when the alert is triggered.

6.  Click **OK** to activate the rule.

## Example: Has been postponed until at the earliest

Sometimes, the delivery of purchased parts that are required in your company's production is delayed. Usually, a postponement is not a problem. However, a postponement that extends beyond the date that is specified in the rule might affect the fulfillment of related sales orders. You want to be alerted if a delivery is delayed. Therefore, you create a rule that triggers an alert if the value in the **Delivery date** field of any purchase order is changed to a specific date or a date that is later than that date.

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Select a purchase order. On the **Action Pane**, click **Edit**.

3.  On the **Action Pane**, on the **Purchase order** tab, in the **Show** group, click **Header View**.

4.  Expand the **Delivery** tab. Right-click the **Delivery date** field, and then select **Create alert rule**.

5.  In the **Create alert rule** form, follow these steps to create the rule:
    
      - Under **Send email alerts for job status changes**, in the **Field** list, select **Delivery date**.
    
      - Under **Send email alerts for job status changes**, in the **Event** list, select **has been postponed until at the earliest:**. Then click the calendar button to select a date.
    
      - Under **Alert me for**, select **All records in %1**. An alert is triggered for any purchase order for which the value in the **Delivery date** field is changed to the specified date or a later date.
    
      - Under **Alert me until**, select **No end date**. Alerts continue to be triggered indefinitely. The rule never becomes inactive.
    
      - Under **Alert me with**, accept or modify the title of the alert. Optionally, you can write a message that is sent when the alert is triggered.

6.  Click **OK** to activate the rule.

## Example: Is set to an earlier date

Sometimes, the suppliers of your company can deliver purchased parts sooner than originally planned. Any reduction in the delivery time of purchased parts can help reduce the time that is required to produce the end product. Therefore, your company's delivery times can be reduced.

You want to be alerted about any early deliveries, so that you can start to reschedule the production immediately. Therefore, you create a rule that triggers an alert if the value in the **Delivery date** field of any purchase order is changed to a date that is earlier than the original delivery date.

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Select a purchase order. On the **Action Pane**, click **Edit**.

3.  On the **Action Pane**, on the **Purchase order** tab, in the **Show** group, click **Header View**.

4.  Expand the **Delivery** tab. Right-click the **Delivery date** field, and then select **Create alert rule**.

5.  In the **Create alert rule** form, follow these steps to create the rule:
    
      - Under **Send email alerts for job status changes**, in the **Field** list, select **Delivery date**.
    
      - Under **Send email alerts for job status changes**, in the **Event** list, select **is set to an earlier date**.
    
      - Under **Alert me for**, select **All records in %1**. An alert is triggered for any purchase order for which the value in the **Delivery date** field is changed to an earlier date.
    
      - Under **Alert me until**, select **No end date**. Alerts continue to be triggered indefinitely. The rule never becomes inactive.
    
      - Under **Alert me with**, accept or modify the title of the alert. Optionally, you can write a message that is sent when the alert is triggered.

6.  Click **OK** to activate the rule.

## Example: Is set to a date earlier than

Sometimes, the suppliers of your company can deliver purchased parts sooner than originally planned. Usually, a reduction in the delivery time of purchased parts is an advantage. However, if the delivery date is changed to a date that is very close to the current date, you might want to be alerted, so that you can take action if the inventory capacity that is required for the delivery is unavailable. Therefore, you create a rule that triggers an alert if the value in the **Delivery date** field of any purchase order is changed to a specific date or an earlier date.

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Select a purchase order. On the **Action Pane**, click **Edit**.

3.  On the **Action Pane**, on the **Purchase order** tab, in the **Show** group, click **Header View**.

4.  Expand the **Delivery** tab. Right-click the **Delivery date** field, and then select **Create alert rule**.

5.  In the **Create alert rule** form, follow these steps to create the rule:
    
      - Under **Send email alerts for job status changes**, in the **Field** list, select **Delivery date**.
    
      - Under **Send email alerts for job status changes**, in the **Event** list, select **is set to a date earlier than:**. Then click the calendar button to select a date.
    
      - Under **Alert me for**, select **All records in %1**. An alert is triggered for any purchase order for which the value in the **Delivery date** field is changed to the specified date or an earlier date.
    
      - Under **Alert me until**, select **No end date**. Alerts continue to be triggered indefinitely. The rule never becomes inactive.
    
      - Under **Alert me with**, accept or modify the title of the alert. Optionally, you can write a message that is sent when the alert is triggered.

6.  Click **OK** to activate the rule.

## Example: Has decreased below

You work in a company where the credit limits of customers are adjusted regularly. To avoid wasting time on orders that cannot be fulfilled because of the customer’s credit limit, you want to be alerted when the credit limit of any customer becomes less than a specific amount. Therefore, you create a rule that triggers an alert if the amount in the **Credit limit** field of any customer becomes less than 10,000.

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**. In the **All customers** list, double-click a customer record to open it.

2.  In the **Customers** form, expand the **Credit and collections** tab. Right-click the **Credit limit** field, and then select **Create alert rule**.

3.  In the **Create alert rule** form, follow these steps to create the rule:
    
      - Under **Send email alerts for job status changes**, in the **Field** list, select **Credit limit**.
    
      - Under **Send email alerts for job status changes**, in the **Event** list, select **has decreased below:**. Then enter the lowest credit limit amount that is allowed before an alert is triggered.
    
      - Under **Alert me for**, select **All records in %1**. An alert is triggered for any customer whose credit limit is changed to an amount that is less than the specified amount.
    
      - Under **Alert me until**, select **No end date**. Alerts continue to be triggered indefinitely. The rule never becomes inactive.
    
      - Under **Alert me with**, accept or modify the title of the alert. Optionally, you can write a message that is sent when the alert is triggered.

4.  Click **OK** to activate the rule.

## Example: Has increased above

Many account managers work for you, and you want to monitor the discounts that the account managers offer on sales orders. You want to be alerted if the total discount percentage of a sales order exceeds a specific limit. Therefore, you create a rule that triggers an alert if the total discount percentage of a sales order exceeds 20.

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Double-click a sales order to open it.

3.  On the **Action Pane**, on the **Sales order** tab, in the **Show** group, click **Header View**.

4.  Expand the **Price and discount** tab. Right-click the **Total discount %** field, and then select **Create alert rule**.

5.  In the **Create alert rule** form, follow these steps to create the rule:
    
      - Under **Send email alerts for job status changes**, in the **Field** list, select **Total discount %**.
    
      - Under **Send email alerts for job status changes**, in the **Event** list, select **has increased above:**. Then enter the highest discount percentage that is allowed before an alert is triggered.
    
      - Under **Alert me for**, select **All records in Sales orders**.
    
      - Under **Alert me until**, select **No end date**. Alerts continue to be triggered indefinitely. The rule never becomes inactive.
    
      - Under **Alert me with**, accept or modify the title of the alert. Optionally, you can write a message that is sent when the alert is triggered.

6.  Click **OK** to activate the rule.

## Example: Later dates

Your company engages in large construction projects, and your customers are invoiced according to an on-account payment plan that is set up before your company starts an assignment. Sometimes, projects are delayed, so that project managers have to adjust the invoice dates that are stated in the payment plan.

For example, a project that was originally planned to start on June 1 is started on July 3. On July 3, the project manager adjusts the date of the first payment rate from June 1 to July 1. You want to be alerted about any postponements of this kind, so that you can maintain an overview of the payment plans. Therefore, you use the **has been postponed** option to trigger an alert any time that project invoice dates are postponed.

You are now alerted about all postponements, even if the dates that were adjusted are in the past. Therefore, you create a rule that triggers an alert only if the value in the **Project date** field in the **On-account** form in **Project** is changed to an earlier date.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**.

2.  On the **Action Pane**, on the **Manage** tab, in the **Bill** group, click **On-account transactions**.

3.  In the **Prepayment journal voucher** form, on the **Overview** tab, select a project.

4.  On the **General** tab, right-click the **Project date** field, and then select **Create alert rule**.

5.  In the **Create alert rule** form, follow these steps to create the rule:
    
      - Under **Send email alerts for job status changes**, in the **Field** list, select **Project date**.
    
      - Under **Send email alerts for job status changes**, in the **Event** list, select **has been postponed**.
    
      - Under **Alert me for**, select **All records in %1**.
    
      - Under **Alert me until**, select **No end date**. Alerts continue to be triggered indefinitely. The rule never becomes inactive.
    
      - Under **Alert me with**, accept or modify the title of the alert. Optionally, you can write a message that is sent when the alert is triggered.

6.  Click **OK** to activate the rule.

## See also

[Due date-type events](due-date-type-events.md)

[Create-type and delete-type events](create-type-and-delete-type-events.md)

  


