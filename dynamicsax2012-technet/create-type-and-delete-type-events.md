---
title: Create-type and delete-type events
TOCTitle: Create-type and delete-type events
ms:assetid: 94a3de7a-f92e-4fa1-855f-b91ff3bfa1a8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa498410(v=AX.60)
ms:contentKeyID: 46687558
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Create-type and delete-type events [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Create events and delete events are part of rules that trigger an alert when a record is either created or deleted in the application. The following table explains the options that are available.

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
<td><p><strong>Record has been created</strong></p></td>
<td><p>A new record has been created in the application.</p></td>
</tr>
<tr class="even">
<td><p><strong>Record has been deleted</strong></p></td>
<td><p>A record has been deleted in the application.</p></td>
</tr>
</tbody>
</table>


## Example: Record has been created

Every time that a new item is added to your company's inventory, you want to enter specific customer data about the item, so that the invoices that are printed for some of your customers use the customers’ own item numbers. You want to be alerted when a new item is created. Therefore, you create a rule that triggers an alert when a record is created in the **Released products** form.

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  In the **Released products** form, right-click any item, and then select **Create alert rule**.

3.  In the **Create alert rule** form, follow these steps to create the rule:
    
      - Under **Send email alerts for job status changes**, in the **Field** list, select **All fields**.
    
      - Under **Send email alerts for job status changes**, in the **Event** list, select **Record has been created**.
    
      - Under **Alert me for**, select **All records in %1**. An alert is triggered for any item that is created in the **Released products** form.
    
      - Under **Alert me until**, select **No end date**. Alerts continue to be triggered indefinitely. The rule never becomes inactive.
    
      - Under **Alert me with**, verify or adjust the title of the alert. Optionally, you can write a message that is sent when the alert is triggered.

4.  Click **OK** to activate the rule.

## Example: Record has been deleted

You want to make sure that no customers are deleted in the **Customers** form without your knowledge. Therefore, you create a rule that triggers an alert when a record is deleted in the **Customers** form.

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Double-click any customer record. In the **Customers** form, right-click any field, and then select **Create alert rule**.

3.  In the **Create alert rule** form, follow these steps to create the rule:
    
      - Under **Send email alerts for job status changes**, in the **Field** list, select **All fields**.
    
      - Under **Send email alerts for job status changes**, in the **Event** list, select **Record has been deleted**.
    
      - Under **Alert me for**, select **All records in %1**. An alert is triggered for any record that is deleted.
    
      - Under **Alert me until**, select **No end date**. Alerts continue to be triggered indefinitely. The rule never becomes inactive.
    
      - Under **Alert me with**, verify or adjust the title of the alert. Optionally, you can write a message that is sent when the alert is triggered.

4.  Click **OK** to activate the rule.

## See also

[Update-type events](update-type-events.md)

[Due date-type events](due-date-type-events.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

