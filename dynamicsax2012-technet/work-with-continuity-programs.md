---
title: Work with continuity programs
TOCTitle: Work with continuity programs
ms:assetid: 77c18054-97da-4299-9a57-cf8d357ad467
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn497790(v=AX.60)
ms:contentKeyID: 62200098
ms.date: 11/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.MCRContinuityData
- Forms.MCRContinuityItemChange
- Forms.MCRContinuitySchedule
- MsDynAx060.Forms.MCRContinuityItemChange
- MsDynAx060.Forms.MCRContinuityData
- MsDynAx060.Forms.MCRContinuitySchedule
- autoship
- auto-ship
- continuity program
- recurring order
- continuity order
---

# Work with continuity programs [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to work with continuity programs in a call center. In a continuity program, which is also known as a recurring order program, customers do not have to place a new order for each shipment. Instead, the customers receive regular product shipments according to a predefined schedule.

After you have set up a continuity program as described in [Set up continuity programs](set-up-continuity-programs.md), you can create a continuity order for a customer. You might also have to perform these additional maintenance tasks:

  - Update the continuity current event period – Set up a batch job that tells the system what the current event period is.

  - Create continuity child orders – Create child orders from the parent continuity order.

  - Process continuity payments – Process billing and notifications for payments that are associated with continuity sales orders.

  - (If required) Extend continuity lines – Extend the number of times that a continuity event can be repeated. The repetition of shipments can then extend beyond the limit that was set in the **Continuity repeat threshold** field in the call center parameters.

  - (If required) Perform a continuity update – Synchronize changes between the continuity program and the continuity parent sales orders.

  - Close continuity parent lines and orders – Close continuity orders.

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
<td><p><a href="set-up-continuity-programs.md">Set up continuity programs</a></p></td>
</tr>
</tbody>
</table>


## 1\. Create a continuity order

You create a continuity order by creating a new sales order and adding a sales order line for the continuity parent product. The **Continuity** form then opens, where you can specify the details of the continuity portion of the order.

Continuity products and non-continuity products can be combined in the same order.

To create a continuity order, follow these steps.

1.  Click **Call center** \> **Common** \> **All sales orders**. On the **Action Pane**, in the **New** group, click **Sales order**. Enter the customer information, and then click **OK** to create a new sales order.

2.  On the **Sales order lines** FastTab, add a new line, and enter the item number of the continuity parent product. Enter quantity, site, and warehouse information for the product.

3.  Press CTRL+S to save the record. The **Continuity** form opens.

4.  In the **Payment method** field, select the method of payment to use for the continuity order and enter the payment amount. You can click **Payment schedule** to set up a payment schedule, and you can click **Add credit card** to store credit card information for the order.
    

    > [!NOTE]
    > <P>If you intend to use credit card payment for each shipment that is part of the continuity program, you must also set parameters in the <STRONG>Credit card authorizations</STRONG> section of the <STRONG>Call center parameters</STRONG> form. For more information, see <A href="set-up-payment-methods-call-center.md">Set up payment methods (Call center)</A>.</P>



5.  Close the **Continuity** form.

6.  If you want to add additional products to the order that are not part of the continuity program, click **Add line**. When you have finished adding products, press CTRL+S.

7.  On the **Action Pane**, in the **Maintain** group, click **Complete**.

8.  In the **Sales order summary** form, on the **Action Pane**, click **Payments**, and then fill in payment information for any non-continuity products that are included in the order.

9.  Close the **Customer payments** form, and then, in the **Sales order summary** form, click **Submit**.

## 2\. Update the continuity current event period

Continuity programs should be updated periodically, so that they show which event is the current event. For example, if the current month is March, and event 3 is scheduled to occur in March, the continuity program should display event 3 as the current event. You perform this update by running a batch job.

To update the continuity current event period, follow these steps.

1.  Click **Call center** \> **Periodic** \> **Continuity** \> **Update continuity current event period**.

2.  Select the **Batch processing** check box, and optionally select a batch group.

3.  Click **Recurrence**, and then specify the settings for the batch job. Click **OK**, and then click **OK** again to run the batch job.

## 3\. Create continuity child orders

After a sales order has been created that contains a continuity product, a child order must be created for each continuity event. In other words, a child order must be created for each shipment that is sent out. You can set up a batch job to complete this process.

To create continuity child orders, follow these steps.

1.  Click **Call center** \> **Periodic** \> **Continuity** \> **Create continuity child orders**.

2.  In the **Criteria** area, set criteria to specify which continuity orders to create child orders for.

3.  Click **OK** to run the process. You receive a message that contains this information:
    
      - The number of child orders that were created
    
      - The number of child orders that were not created because of an expired credit card
    
      - A message that states that the batch job has finished running

4.  You can confirm that child orders were created for a particular sales order:
    
    1.  Click **Call center** \> **Common** \> **All sales orders**.
    
    2.  Double-click the sales order to open it. Select the sales order line for the continuity product.
    
    3.  On the **Sales order lines** FastTab, click **Inventory**.
    
    4.  In the **View** section, click **Continuity schedule**.
    
    5.  In the **Continuity** form, in the list, scroll to the right until you see the **Continuity sales order** field. The child sales order is displayed in this field.
        

        > [!NOTE]
        > <P>(BRA) The fiscal document type that is selected in the sales order is updated in the fiscal document type of the child order when a child order is created.</P>



5.  Optional: Set up a batch job to create continuity child orders by filling in the fields on the **Batch** tab in the **Create continuity child orders** form.

## 4\. Process continuity payments

To process continuity payments, follow these steps.

1.  Click **Call center** \> **Periodic** \> **Continuity** \> **Process continuity payments**.

2.  In the **Criteria** area, set criteria to specify which continuity payments to process. You can process payments for a specified date, a specified continuity item, or both.

3.  Click **OK** to process the payments.

4.  Optional: Set up a batch job to process payments by filling in the fields on the **Batch** tab in the **Process continuity payments** form.

## 5\. (If required) Extend continuity lines

If the number of times that a continuity event should be repeated exceeds the **Continuity repeat threshold** value that is defined in the call center parameters, you must extend continuity lines, or events.

To extend continuity lines, follow these steps.

1.  Click **Call center** \> **Periodic** \> **Continuity** \> **Extend continuity lines**.

2.  Select the **Batch processing** check box, and optionally select a batch group.

3.  Click **Recurrence**, and then specify the settings for the batch job. Click **OK**, and then click **OK** again to run the batch job.

## 6\. (If required) Perform a continuity update

You can make changes to a continuity program after it has been created. For example, you can change the billing options, the start date, or the included products. If changes are made to a continuity program for which you have created orders, the parent sales orders that are associated with that continuity program must be updated with the new information.

To perform a continuity update, follow these steps.

1.  Click **Call center** \> **Journals** \> **Continuity** \> **Continuity programs**. Modify an existing continuity program as you require, and then close the **Continuity programs** form.

2.  Click **Call center** \> **Periodic** \> **Continuity** \> **Continuity update batch**.

3.  In the **Criteria** area, select a continuity schedule.

4.  Click **OK** to run the update. You receive a message that lists all the parent sales orders that have been updated or created because of the changes to the continuity program.

5.  Optional: Set up a batch job to perform continuity updates by filling in the fields on the **Batch** tab in the **Continuity update batch** form.

You can also update individual lines in existing continuity orders if you have to change the start date or substitute products on those lines. To update continuity order lines, follow these steps.

1.  Click **Call center** \> **Journals** \> **Continuity** \> **Continuity updates**.

2.  Under **Order selection**, enter the criteria to use to select orders.

3.  On the **Action Pane**, click **Find**. The form displays a list of all the continuity sales orders that meet the selected criteria.

4.  Select one or more sales orders, and then follow one of these steps:
    
      - Under **Update start date**, enter the new start date or the number of days to add to the existing start date. On the **Action Pane**, click **Update date**, and then click **OK**.
    
      - Under **Substitution**, enter information about the products to substitute in the orders. On the **Action Pane**, click **Substitute**, and then click **OK**.

5.  Click **Call center** \> **Periodic** \> **Continuity** \> **Continuity update batch**.

6.  In the **Criteria** area, select a continuity schedule.

7.  Click **OK** to run the update. You receive a message that lists all the parent sales orders that have been updated.

## 7\. Close continuity parent lines and orders

A batch job sets the status of parent continuity orders and continuity order lines to **Invoiced** when all the child continuity orders have been invoiced.

To close continuity parent lines and orders, follow these steps.

1.  Click **Call center** \> **Periodic** \> **Continuity** \> **Close continuity parent lines and orders**.

2.  Select the **Batch processing** check box, and optionally select a batch group.

3.  Click **Recurrence**, and then specify the settings for the batch job. Click **OK**, and then click **OK** again to run the batch job.

## Related tasks

[Set up continuity programs](set-up-continuity-programs.md)

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
<p><strong>Call center</strong> configuration key</p>
<p><strong>Continuity</strong> configuration key</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>Sales clerk (if you create a sales order that has an associated continuity order)</p>
<p>Sales manager (if you maintain the continuity program)</p></td>
</tr>
</tbody>
</table>


## See also

[Creating sales orders for a call center](creating-sales-orders-for-a-call-center.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

