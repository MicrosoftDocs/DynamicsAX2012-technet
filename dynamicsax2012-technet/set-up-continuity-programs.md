---
title: Set up continuity programs
TOCTitle: Set up continuity programs
ms:assetid: 8dc715f2-862e-4c0b-8521-66b29b7a6d03
ms:mtpsurl: https://technet.microsoft.com/library/Dn497801(v=AX.60)
ms:contentKeyID: 62200115
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.MCRContinuityItemChange
- Forms.MCRContinuitySchedule
- MsDynAx060.Forms.MCRContinuityItemChange
- MsDynAx060.Forms.MCRContinuitySchedule
- autoship
- auto-ship
- continuity program
- recurring order
- continuity order
audience: Application User
ms.search.region: Global
---

# Set up continuity programs 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to set up a continuity program for a call center. In a continuity program, which is also known as a recurring order program, customers receive regular product shipments according to a predefined schedule. Each shipment can contain a different product, as in the case of a book-of-the-month club, or the same product can be sent repeatedly.

Continuity programs let you maintain an ongoing relationship with the customer, and also provide an opportunity for up-selling and cross-selling.

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
<td><p><a href="create-call-center-catalogs.md">Create call center catalogs</a></p></td>
</tr>
</tbody>
</table>


## 1\. Set continuity parameters

The first step in setting up a continuity program is to set the continuity parameters in the **Call center parameters** form.

To set the continuity parameters, follow these steps.

1.  Click **Call center** \> **Setup** \> **Call center parameters**.

2.  In the left pane, click **General**, and then, on the **Continuity** FastTab, set the parameters. The following table describes some of the options.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Continuity days before delivery</strong></p></td>
    <td><p>The number of days before the delivery date that continuity orders can be processed.</p>
    <p>If the number of days before delivery is less than this number, the continuity order can't be processed.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Continuity on account bill days</strong></p></td>
    <td><p>The number of days before the due date of an &quot;on account&quot; continuity bill that the bill is generated.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Continuity repeat threshold</strong></p></td>
    <td><p>A threshold that determines whether repeated continuity events that are not billed up front are displayed when the sales order is created. If this number is less than the number of times that a continuity event should be repeated, the repetition is handled by a batch job.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Number of orders to create</strong></p></td>
    <td><p>The maximum number of continuity child orders to create. If this field is not set, there is no limit.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Revenue journal name</strong></p></td>
    <td><p>The journal name to use when money is transferred from parent revenue accounts to child revenue accounts. This field is used only for upfront billing that uses a payment schedule.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Continuity payment profile</strong></p></td>
    <td><p>The posting profile to use when a continuity payment is booked as a prepayment.</p></td>
    </tr>
    </tbody>
    </table>


## 2\. Create a continuity program

Next, create a continuity program that specifies details such as the payment schedule, the timing of the shipments, and whether billing is up front.

You must also add a list of products that are included in the continuity program. Each product receives an event ID number that is assigned sequentially, beginning with 1. The event IDs determine the order in which products are sent.

When customers receive a different product in each shipment, the products are sent in sequential order according to their event IDs, beginning with the current event. When customers receive the same product in each shipment, the list contains only one product that has one event ID, and the same event occurs repeatedly. You can specify how many times to repeat each event.

To create a continuity program, follow these steps.

1.  Click **Call center** \> **Journals** \> **Continuity** \> **Continuity programs**.

2.  On the **Action Pane**, click **New**.

3.  On the **Overview** tab, set the following fields.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Schedule ID</strong></p></td>
    <td><p>A unique name for the continuity program.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Payment schedule</strong></p></td>
    <td><p>The payment schedule to use to invoice continuity orders. For information about payment schedules, see <a href="https://technet.microsoft.com/library/aa572068(v=ax.60)">Payment schedules (form)</a>.</p>
    <p>Using a payment schedule is optional. You can also bill up front.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Order start</strong></p></td>
    <td><p>A value that indicates whether the continuity order starts with the first event or the current event.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Active</strong></p></td>
    <td><p>A selected check box indicates that the continuity program is currently active in the system. If this check box is not selected, the continuity program is not active and does not appear as an option in the sales order form.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Bill upfront</strong></p></td>
    <td><p>A selected check box indicates that the customer is billed for the whole continuity order when the first continuity item is shipped.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Prompt for start date</strong></p></td>
    <td><p>A selected check box indicates that the user is prompted to enter a start date for the continuity order when the order is created.</p>
    <p>If the user does not enter a start date, the order creation date is used as the start date.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Prompt for payment schedule</strong></p></td>
    <td><p>A selected check box indicates that the user is prompted to choose a payment schedule when the order is created.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Current event</strong></p></td>
    <td><p>The current event number, if the <strong>Order start</strong> field for the continuity program is set to <strong>Current event</strong>. This field cannot be modified.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Consolidate</strong></p></td>
    <td><p>A selected check box indicates that, if a continuity order is created after the start date, the system does not create a separate order for every event that was missed. Instead, the system consolidates all the missed events into one order.</p></td>
    </tr>
    </tbody>
    </table>


4.  On the **Setup** tab, in the **Days after order date** field, enter the number of days after the original continuity order is placed to schedule the first event (shipment).
    

    > [!NOTE]
    > <P>If the <STRONG>Prompt for start date</STRONG> check box is selected, and the user enters a start date into the order, this date is used as the basis for the <STRONG>Days after order date</STRONG> calculation.</P>



5.  In the list at the bottom of the **Setup** tab, add the events that make up the continuity program. Each event represents a shipment and is associated with a product that is sent in that shipment.
    
    Click **Add line** to add the first event and product. By default, the first event ID is **1**.

6.  In the **Item number** field, select a product. Enter quantity, unit, and price information.

7.  Fill in the other fields in the list. The following table describes some of the options.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Payment schedule</strong></p></td>
    <td><p>The payment schedule to use to invoice continuity orders.</p>
    <p>Using a payment schedule is optional. You can also bill up front.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Delivery mode</strong></p></td>
    <td><p>The delivery mode to use for the event.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Date interval code</strong></p></td>
    <td><p>The code for the date interval that determines the timing of an event. For more information, see <a href="https://technet.microsoft.com/library/aa558459(v=ax.60)">Date intervals (form)</a>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Days from last</strong></p></td>
    <td><p>The number of days that should pass between the last event and the current event.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Start order date</strong></p></td>
    <td><p>The date on which the continuity order starts.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Action code</strong></p></td>
    <td>The action that should be taken when this event is reached.
    <p>Select from the following options:</p>
    <ul>
    <li><p>No selection – Process this event, and then move to the next event.</p></li>
    <li><p><strong>Skip</strong> – Skip this event.</p></li>
    <li><p><strong>End</strong> – End the continuity order after this event.</p></li>
    </ul></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Times to repeat</strong></p></td>
    <td><p>The number of times that this event should be repeated before the system moves to the next event.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Probability %</strong></p></td>
    <td><p>The probability that you will receive a sales order for this product.</p></td>
    </tr>
    </tbody>
    </table>


8.  Continue to add events to the list as you require. If you are ready to use the continuity program, make sure that the **Active** check box is selected.

9.  Optional: You can also create a new continuity program by copying an existing program. In the **Continuity programs** form, select an existing continuity program. Then, on the **Action Pane**, click **Copy schedule**.

## 3\. Create a continuity product

Next, create a parent product that represents the continuity program that you created in procedure 2. If you add this product to a sales order, the **Continuity** form opens. You can then use this form to create the continuity order.

The parent product does not specify the individual products that the customer receives in each shipment. These products were already specified when you set up the continuity program in procedure 2.

To create a parent continuity product, follow these steps.

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  On the **Action Pane**, in the **New** group, click **Product**.

3.  Enter the product type, name, and number details, and then click **OK**.

4.  Double-click the product name to open the **Released product details** form. Then, on the **Action Pane**, in the **Maintain** group, click **Edit**.

5.  On the **Sell** FastTab, in the **Continuity schedule ID** field, select the continuity program to associate the product with.

## Next step

After you have set up a continuity program, you can create continuity sales orders. For more information, see [Work with continuity programs](work-with-continuity-programs.md).

After continuity sales orders have been created, you must perform several periodic tasks to keep the continuity program functioning correctly:

  - Update continuity current event periods.

  - Create continuity child orders.

  - Process continuity payments.

  - (If required) Extend continuity lines.

  - (If required) Run continuity update batch jobs.

  - (If required) Close continuity parent lines and orders.

All these tasks are described in [Work with continuity programs](work-with-continuity-programs.md).

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
<td><p>Retail headquarters configuration key</p>
<p>Call center configuration key</p>
<p>Continuity configuration key</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>Sales manager</p></td>
</tr>
</tbody>
</table>


## See also

[Create call center catalogs](create-call-center-catalogs.md)

[Work with continuity programs](work-with-continuity-programs.md)

  


