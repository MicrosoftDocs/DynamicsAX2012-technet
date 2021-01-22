---
title: Create or modify an outbound load
TOCTitle: Create or modify an outbound load
ms:assetid: be0ee355-8a38-42a6-9c1f-09067393b20b
ms:mtpsurl: https://technet.microsoft.com/library/Dn770235(v=AX.60)
ms:contentKeyID: 62583048
author: Khairunj
ms.author: daxcpft
ms.date: 11/13/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create or modify an outbound load 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Transportation management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



This topic explains how to create or modify an outbound load. An outbound load is a single shipment or group of shipments shipped from a warehouse location to a customer or intermediate location. You can create an outbound load from a sales order or transfer order automatically or manually.

You can split a sales line or transfer line to create multiple loads. For example, a sales line has 50 items. If the shipping carrier can only handle 25 items, the sales line can be split into two separate lines with 25 items each. To ship the items in the shipping carrier, the warehouse manager creates two new loads for the split sales lines.

You can modify an outbound load by adding a new sales line or transfer line. For example, if the shipping route of a sales line is the same as that of an existing load, you can add the sales line to the existing load.


> [!NOTE]
> <P>If you are running Microsoft Dynamics AX 2012 R3 Cumulative Update 8, you can use the <STRONG>Load building workbench</STRONG> to create proposed loads based on load building strategies. Load building strategies contain logic that will find sales order lines that match the criteria that you specify in the strategy, and propose loads according to the criteria. You can then examine the contents of the loads and make adjustments, and then build loads based on the proposed loads. Additionally, you can schedule a batch job to automate the process of building loads based on load building strategies. For more information, see <A href="automate-the-process-of-building-loads.md">Automate the process of building loads</A>.</P>



## This task is part of a bigger process

The following illustration shows how the creation of an outbound load relates to other tasks for the planning and process of outbound loads. For more information, see [Business process: Planning and processing outbound loads for shipping](business-process-planning-and-processing-outbound-loads-for-shipping.md).

![Business process flow for outbound loads](images/Dn770230.Planningandprocessingoutboundloads(AX.60).jpg "Business process flow for outbound loads")

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
<th><p>Prerequisites</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Related setup tasks</p></td>
<td><ul>
<li><p>In the <strong>Released product details</strong> form, create an item, and then select the <strong>Use transportation management processes</strong> check box. For more information, see <a href="create-items.md">Create items</a> and <a href="key-tasks-release-products.md">Key tasks: Release products</a>.</p></li>
<li><p>In the <strong>Warehouses</strong> form, create a warehouse, and then select the <strong>Use warehouse management processes</strong> check box. For more information, see <a href="create-warehouses.md">Create warehouses</a>.</p></li>
<li><p>Create a load template. For more information, see <a href="set-up-a-load-template.md">Set up a load template</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Create an outbound load automatically using a sales line or transfer line

To create an outbound load automatically by using a sales line or transfer line, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Warehouse management parameters**.
    
    –or–
    
    Click **Transportation management** \> **Setup** \> **Transportation management parameters**.

2.  Click **Loads**, and then select the **Automatically create at sales order entry** and **Automatically create at transfer order entry** check boxes.

3.  Create a sales line or transfer line to automatically create an outbound load. For more information, see [Create or edit a sales order](create-or-edit-a-sales-order.md) or [Set up transfer order lines](set-up-transfer-order-lines.md).

## Create an outbound load manually using a sales line or transfer line

To create an outbound load manually by using a sales line or transfer line, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Warehouse management parameters**.
    
    –or–
    
    Click **Transportation management** \> **Setup** \> **Transportation management parameters**.

2.  Click **Loads**, and then clear the **Automatically create at sales order entry** and **Automatically create at transfer order entry** check boxes.

3.  Create a sales line or transfer line, and then reserve items for the sales line or transfer line to make sure that items are available to create a load. For more information about reservations, see [Reserve inventory manually for a sales order](reserve-inventory-manually-for-a-sales-order.md) and [Reserve inventory automatically for a sales order](reserve-inventory-automatically-for-a-sales-order.md).
    

    > [!TIP]
    > <P>Select the <STRONG>Reserve inventory at load posting</STRONG> check box in the <STRONG>Warehouses</STRONG> form to automatically reserve items when you release them from the warehouse.</P>



4.  Click **Transportation management** \> **Inquiries** \> **Load planning workbench**.
    
    –or–
    
    Click **Warehouse management** \> **Common** \> **Load planning workbench**.

5.  On the **Sales lines** or **Transfer lines** tab, select a sales line or transfer line for which you want to create an outbound load.

6.  Click **To new load** to open the **Load template assignment** form.

7.  In the **Load template assignment** form, select a load template identifier (ID) to define a trailer type for the load.

8.  Click **OK** to create the load. In the **Load planning workbench** form, you can view the details for the newly added load on the **Load lines** tab.
    

    > [!NOTE]
    > <P>On the <STRONG>Demand</STRONG> tab, click <STRONG>Entire order to new load</STRONG> to create a new load with details from the sales order or transfer order.</P>



## Optional: Split a sales line or transfer line to create multiple loads

To split a sales line or transfer line to create multiple loads, follow these steps:

1.  In the **Load planning workbench** form, on the **Sales lines** or **Transfer lines** tab, select a line, and then click **To new load**.

2.  In the **Load template assignment** form, select a load template ID, and reduce the quantity of items to split the sales line or transfer line.

3.  Click **OK** to create a load with the reduced quantity. In the **Load planning workbench** form, on the **Sales lines** or **Transfer lines** tab, you can view a new sales line or transfer line with the remaining quantity.

4.  Optional: To add the split sales lines or transfer lines to a new load, repeat steps in either of the “Create an outbound load using a sales line or transfer line” procedures earlier in this topic.

## Optional: Add a sales line or transfer line to an existing load

To add a new sales line or transfer line to an existing load, follow these steps:

1.  In the **Load planning workbench** form, on the **Sales lines** or **Transfer lines** tab, select a line to add to an existing load.

2.  On the **Loads** FastTab, select a load ID, and then click **To existing load** to open the **Load template assignment** form. The load template ID is displayed by default.

3.  Click **OK** to add the selected line to an existing load.

4.  In the **Load planning workbench** form, click the **Line details** FastTab. On the **Load lines** tab, you can view two lines for the selected load ID, where the first line is the new sales line or transfer line.
    

    > [!NOTE]
    > <P>On the <STRONG>Demand</STRONG> tab, click <STRONG>Entire order to existing load</STRONG> to add details from the sales order or transfer order to the selected load.</P>



## Applying load building strategies

In Microsoft Dynamics AX 2012 R3 Cumulative Update 8, a framework has been added to make it easier to apply predefined strategies to the process of building loads. Load building strategies let you specify rules that control how loads are built. For example, this is useful if you want to maximize efficiency by avoiding half full loads, or if you frequently use the same shipping carrier and all the considerations for the loads, such as size or weight restrictions, are known.

A load building strategy named **Volume-based load building strategy** is provided in AX 2012 R3 CU8. This strategy lets you use the maximum values specified for height and weight in the load template, or override the settings by entering new values. In addition, you can add your own load-building strategies by creating a new class in the Application Object Tree (AOT), and then defining custom parameters. For more information, see [Automate the process of building loads](automate-the-process-of-building-loads.md).

## Next step

[Consolidate multiple shipments into a load](consolidate-multiple-shipments-into-a-load.md)

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
<td><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>. Expand the <strong>Trade</strong> license key, and then select the <strong>Warehouse and Transportation management</strong> configuration key.</p></td>
</tr>
</tbody>
</table>

  


