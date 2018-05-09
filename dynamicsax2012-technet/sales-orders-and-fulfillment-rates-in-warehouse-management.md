---
title: Sales orders and fulfillment rates in Warehouse management
TOCTitle: Sales orders and fulfillment rates in Warehouse management
ms:assetid: 2a2e70a4-e472-4a36-8c2d-c8ba56e13e18
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn887220(v=AX.60)
ms:contentKeyID: 63378889
ms.date: 06/08/2015
mtps_version: v=AX.60
---

# Sales orders and fulfillment rates in Warehouse management 



> [!NOTE]
> <P>This topic applies to features in the <STRONG>Warehouse management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



This topic describes features that are available only if you are running Microsoft Dynamics AX 2012 R3 Cumulative Update 8. This topic describes how to set up the following:

  - A company policy for sales order fulfillment.

  - A policy for sales order fulfillment for a specific customer.

  - A batch job to release sales orders to the warehouse.

  - A batch job to release transfer orders to the warehouse.

## Set up a default company policy for sales order fulfillment

You need to set up a default company policy for sales order fulfillment rates. The policy controls the percentage of the total price or the quantity of an order that must be reserved physical before a sales order can be released to the warehouse. You can also set up a policy for specific customers. Customer-specific policies override the default policy.

To set up a policy for sales order fulfillment, follow these steps:

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  On the **Warehouse management** tab, enter the following information.
    
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
    <td><p><strong>Fulfillment rate</strong></p></td>
    <td><p>Enter the percentage of the total price of the order, or the total quantity of the order, that must be available.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Value type</strong></p></td>
    <td><p>Specify whether the fulfillment policy is based on the total price or the quantity of the sales order.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Fulfillment violation messages</strong></p></td>
    <td><p>Select the severity of the message that is displayed when the fulfillment rate is violated. The options are as follows:</p>
    <ul>
    <li><p><strong>Accept</strong> – No message is displayed, and a shipment and load lines are created.</p></li>
    <li><p><strong>Warning</strong> – A warning message is displayed, and the user can release the sales order to the warehouse. A shipment and load lines are created, and the inventory is physically reserved.</p></li>
    <li><p><strong>Error</strong> – An error message is displayed, and the user cannot release the sales order to the warehouse.</p></li>
    </ul></td>
    </tr>
    </tbody>
    </table>


## Set up a fulfillment rate policy for sales orders for a specific customer

If you set up a fulfillment rate policy for sales orders for a specific customer, the policy will override the default policy for the company.

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**. Select the customer, and then click **Edit**.

2.  On the **Warehouse management** FastTab, enter the following information.
    
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
    <td><p><strong>Fulfillment rate</strong></p></td>
    <td><p>Enter the percentage of the total price of the order, or the total quantity of the order, that must be available.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Value type</strong></p></td>
    <td><p>Specify whether the fulfillment policy is based on the total price or the quantity of the sales order. If you select <strong>None</strong>, the default fulfillment rate policy is used.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Fulfillment violation messages</strong></p></td>
    <td><p>Select the severity of the message that is displayed when the fulfillment rate is violated. The options are as follows:</p>
    <ul>
    <li><p><strong>Use company policy</strong> – Use the default fulfillment rate policy that is defined in the <strong>Accounts receivable parameters</strong> form.</p></li>
    <li><p><strong>Accept</strong> – No message is displayed, and a shipment and load lines are created.</p></li>
    <li><p><strong>Warning</strong> – A warning message is displayed, and the user can release the sales order to the warehouse. A shipment and load lines are created, and the inventory is physically reserved.</p></li>
    <li><p><strong>Error</strong> – An error message is displayed, and the user cannot release the sales order to the warehouse.</p></li>
    </ul></td>
    </tr>
    </tbody>
    </table>


## Set up a batch job to automatically release sales orders

You can set up a batch job to automatically release sales orders to the warehouse. The fulfillment rate policy for sales orders is applied when the orders are released.


> [!NOTE]
> <P>If you want the batch job to reserve inventory for sales orders, in the <STRONG>Warehouses</STRONG> form, on the <STRONG>Warehouse management</STRONG> FastTab, select the <STRONG>Reserve when orders are released by a batch job</STRONG> check box. If you do not select this check box, you’ll have to reserve the quantities manually.</P>
> <P>If you’re using Microsoft Dynamics AX 2012 R3 Cumulative Update 9, the batch job can consolidate multiple sales orders for the same customer into a single shipment. To enable this process, in the <STRONG>Warehouses</STRONG> form, on the <STRONG>Warehouse management</STRONG> FastTab, select the <STRONG>Consolidate shipment at release to warehouse</STRONG> option.</P>



When you set up the batch job, you can specify whether to allow the following:

  - Allow partial reservations, and the quantity to release.

  - Allow sales orders that were partially released to be released again, so that the remaining quantity is delivered.

  - Keep the reservations, even though the release to warehouse process failed. For example, the process can fail if the sales order did not meet the required fulfillment rate, or the order and one of the lines is missing a delivery address.

To set up a batch job to automatically release sales orders, follow these steps:

1.  Click **Warehouse management** \> **Periodic** \> **Automatic release of sales orders**.

2.  In the **Quantity to release** field, select whether the total quantity of the order, or only the quantity that is physically reserved, is assigned to the shipment and load lines.

3.  Optional: To allow sales orders that have been partially released to be released again, select the **Allow release of partially released orders** check box.
    

    > [!NOTE]
    > <P>If any items on an order are picked by using processes such as simple picking or picking list pending, then you must select this check box. Otherwise, you cannot release the orders again.</P>



4.  Optional: To preserve item reservations even though the release to warehouse process failed, select the **Keep reservations on fulfillment rate failure** check box. If you do not select this check box, and the release to warehouse process fails, all reservations for the sales order are canceled.

5.  Click **Select** to enter selection criteria for the batch job.

6.  Optional: If you want to run the batch job according to a schedule, click the **Batch** tab, and then enter the scheduling information.

## Set up a batch job to automatically release transfer orders

You can set up a batch job to automatically release transfer orders to the warehouse. You can specify selection criteria, and the order in which transfer orders are released. The rules are the same for the manual and automated processes. For example, you can only release transfer orders to the warehouse if they are fully reserved. For more information, see [About transfer orders](about-transfer-orders.md).

To set up a batch job to automatically release transfer orders, follow these steps:

1.  Click **Warehouse management** \> **Periodic** \> **Automatic release of sales orders**.

2.  Click **Select** to enter criteria for the batch job.
    

    > [!TIP]
    > <P>For the ship date criteria, you can use query ranges, for example, currentdate() +1.</P>



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
<td><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>. Expand the <strong>Trade</strong> license key, and select the <strong>Warehouse and Transportation management</strong> configuration key.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

