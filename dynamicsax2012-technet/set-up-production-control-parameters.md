---
title: Set up production control parameters
TOCTitle: Set up production control parameters
ms:assetid: fd58436b-b540-4149-9843-121e702fb35b
ms:mtpsurl: https://technet.microsoft.com/library/Aa500116(v=AX.60)
ms:contentKeyID: 37820244
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- parameter
- parameters
- production
- production control
- production order
audience: Application User
ms.search.region: Global
---

# Set up production control parameters 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Define production parameters to reflect your production environment. You can specify how you want to work with creation, estimation, scheduling, consumption feedback, and cost accounting for production orders. Production parameters must be defined before you can create or run your production. You can set up production control parameters per company, or you can set site-specific parameters by using the following forms:

  - Click **Production control** \> **Setup** \> **Production control parameters**. In the **Parameter usage** field, specify whether the parameter settings are by company or by site.
    
    \-or-

  - Click **Production control** \> **Setup** \> **Production control parameters by site**. On the **Overview** tab, select or add the site that you want to set site-specific parameters for.

## Set up general parameters

To set up general parameters, follow these steps:

1.  Click **Production control** \> **Setup** \> **Production control parameters**.

2.  On the **General** tab, in the **Profit-setting** field, select the profit setting code to use when you estimate the sales price of a production order.

3.  In the **Reservation** field, specify how you want to reserve and mark the items on a production order for on-hand inventory.

4.  In the **Ledger posting** field, select how the production order should be posted to the ledger when you do cost accounting. Items and work in progress are considered in the accounting.

5.  In the **Maximum job lead time** field, enter the maximum job throughput, in days.

6.  Select the following check boxes as appropriate.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Check box</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Route network</strong></p></td>
    <td><p>Include complex route networks.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Mandatory date</strong></p></td>
    <td><p>Require that a validity period be specified for a route. When the period expires, the route is no longer valid.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Block removal of approval</strong></p></td>
    <td><p>Specify that after a route has been approved, you cannot revert its status.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Block editing</strong></p></td>
    <td><p>Specify that after a route is created, you cannot change it.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Post picking list in ledger</strong></p></td>
    <td><p>Post journal lines in the ledger.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Post report as finished in ledger</strong></p></td>
    <td><p>Post reporting as finished in the ledger.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Post excl. transaction type</strong></p></td>
    <td><p>Exclude the transaction type from production posting.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Planned order</strong></p></td>
    <td><p>Include capacity reservations derived from planned orders when the available capacity is calculated during production scheduling.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Project</strong></p></td>
    <td><p>Include capacity reservations derived from projects when the available capacity is calculated during production scheduling.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Price calculation</strong></p></td>
    <td><p>Run the price calculation during the estimation of production orders.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Delete capacity reservations</strong></p></td>
    <td><p>Delete capacity reservations when the production is reported as finished.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Use estimated cost price</strong></p></td>
    <td><p>Include the estimated cost price when you determine physical value.</p></td>
    </tr>
    </tbody>
    </table>


## Set up parameters for journals

Use the journal parameters to define the kind of information that appears in production journals. You can set up parameters that direct Microsoft Dynamics AX to update the journals at each step of the production process.

To set up parameters for journals, follow these steps:

1.  Click **Production control** \> **Setup** \> **Production control parameters**.

2.  On the **Journals** tab, in the **Picking list** field, accept the default journal, or select an alternative journal to record deliveries from inventory.

3.  In the **Route card** field, select the journal name that you want to use for route cards.

4.  In the **Job card** field, select the journal name that you want to use for job cards.

5.  In the **Report as finished** field, accept the default journal, or select another journal for posting information when the production order is reported as finished.

6.  Select the following check boxes as appropriate.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Check box</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Mandatory cost category for quantity</strong></p></td>
    <td><p>Include the quantity cost category in the route and job card journals.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Automatic BOM consumption</strong></p></td>
    <td><p>Indicate that the system calculates and posts bill of materials (BOM) consumption in the picking list when you update a production order.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Automatic report as finished</strong></p></td>
    <td><p>Enable feedback for the last operation in the production to be automatically reported as finished.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Update capacity plan</strong></p></td>
    <td><p>Indicate that the capacity plan is updated when journals are posted.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Pick negative</strong></p></td>
    <td><p>Enable negative picking in the physical inventory during posting.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Physical reduction</strong></p></td>
    <td><p>Indicate that the material consumption is reduced to the on-hand quantity when inventory is insufficient.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Inv.-manage planned order qty.</strong></p></td>
    <td><p>Indicate that the planned order quantity should manage and appreciate the attached inventory transactions.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Accept error</strong></p></td>
    <td><p>Accept missing feedback for operations resource and item consumption.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Automatic BOM consumption</strong></p></td>
    <td><p>Indicate that the picking list for BOM consumption is updated for the current production.</p></td>
    </tr>
    </tbody>
    </table>


## Set up parameters for standard updates

You can set parameters to control how Microsoft Dynamics AX posts scrap and capacity requirements during updates.

To set up parameters for standard updates, follow these steps:

1.  Click **Production control** \> **Setup** \> **Production control parameters**.

2.  On the **Standard update** tab, in the **Scrap method** field, select the method that you want to use to post scrap to the ledger when you calculate the consumption of items and operations resources. If you selected **Scrap account**, you must select the account to use in the **Scrap account** field. In cost accounting, this is for the error quantity reported. You can change the selection before you perform cost accounting. Cost accounting is performed when production orders are completed.

3.  To use limited capacity requirements as default values in operations and job scheduling, select the **Finite capacity** check box.

4.  To use limited material requirements as default values in operations and job scheduling, select the **Finite material** check box.

5.  To use limited property requirements as default values in operations and job scheduling, select the **Finite property** check box.

## Set up parameters for automatic updates

Select how you want Microsoft Dynamics AX to conduct automatic updates. Updates are automatically executed when the update that you run is further along in the production flow than the status of the production order.

To set up parameters for automatic updates, follow these steps:

1.  Click **Production control** \> **Setup** \> **Production control parameters**.

2.  On the **Automatic update** tab, in the **Scheduling method** field, select the scheduling method to use when automatic scheduling is enabled and Microsoft Dynamics AX schedules production.

3.  In the **Automatic BOM consumption** field, select the method for posting material consumption in the picking list journal.

4.  In the **Automatic route consumption** field, select the method for posting route consumption in the route card journal.

5.  In the **Automatic BOM consumption** field, select whether to automatically post material consumption in the picking list journal.

6.  In the **Automatic route consumption** field, select whether to post route consumption in the route card journal.

7.  To group purchases according to the vendor when auto-creating on estimation, select the **Group by vendor** check box.

8.  To group purchases by both vendor and buyer group when auto-creating on estimation, select the **Group by buyer group** check box.
    

    > [!NOTE]
    > <P>Grouping by buyer can only be implemented when the <STRONG>Group by vendor</STRONG> check box is selected.</P>



9.  In the **Automatic BOM consumption** field, select whether to post material consumption automatically in the picking list journal when a purchase order is received from the vendor.

10. In the **Automatic route consumption** field, select whether to post route consumption in the route card journal when a purchase order is received from the vendor.

11. To show information about the vendor operation when the purchase order is received, select the **Show info** check box.

## Set up status combinations

You can specify the combinations of production order status and scheduling status that you want to enable for production orders. The matrix on the **Status** tab in the **Production control parameters** form lists each production order status in sequence from top to bottom, and lists the actions from left to right in each row. The selections in the rows determine the actions that are enabled for a production order for each status. For example, you can specify that a production order must be estimated before it can be scheduled.

When you perform one of the selected actions for the first time, the system will perform each action that is selected in the row, starting from left to right, if the action has not already been performed. For example, for a production order with the status **Created**, if the **Estimated** check box and the **Started** check box are selected, when you start the production order, but have not already estimated it, the system will estimate the order before starting it.

To set up status combinations, follow these steps:

1.  Click **Production control** \> **Setup** \> **Production control parameters**.

2.  On the **Status** tab, select the check boxes in the rows and columns to specify the combinations. To select all of the combinations, click the **Select all** button.

## Set up inventory dimensions

Inventory dimensions help you track inventory postings. You can specify the overview that you want to view the dimensions in.

To set up inventory dimensions, follow these steps:

1.  Click **Production control** \> **Setup** \> **Production control parameters**.

2.  On the **Inventory dimensions** tab, select an inventory dimension from the list.

3.  Select check boxes to include the dimension in the relevant production order, lines, and journal overviews.

## Set up number sequences

To set up number sequences for production, follow this step:

  - On the **Number sequences** tab, set up appropriate production number sequences for each reference.

## See also

[About production journals](about-production-journals.md)

[About inventory dimensions and dimension groups](about-inventory-dimensions-and-dimension-groups.md)

  


