---
title: Create, process, and release a wave manually
TOCTitle: Create, process, and release a wave manually
ms:assetid: 78826625-73dd-4ca9-b93d-b9924fecea43
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn553173(v=AX.60)
ms:contentKeyID: 62200099
ms.date: 04/29/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.InventLocation
- Forms.WHSWaveTableCreateNew
- Forms.WHSWaveTemplateTable
- MsDynAx060.Forms.InventLocation
- MsDynAx060.Forms.WHSWaveTableCreateNew
- MsDynAx060.Forms.WHSWaveTemplateTable
audience: Application User
ms.search.region: Global
---

# Create, process, and release a wave manually 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Warehouse management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



This topic describes how to manually create, process, and release a wave to create picking work for a load, shipment, production order, or kanban order. You can create waves for sales orders, production orders, and kanban orders, as follows:

  - Sales orders – Use shipping waves to include lines from sales orders. When a sales order is released to the warehouse, the sales order lines can be included in the wave.

  - Production orders – Use production waves to include lines from the bill of materials (BOM) for the product.

  - Kanban orders – Kanban waves include picking list lines from kanban orders.

For sales orders and kanban orders, inventory must be reserved before the order is released to the warehouse. Otherwise, the items or allocation lines cannot be processed in a wave. However, production orders are slightly more flexible. For production orders, you can specify the following:

  - Allow production orders to be released to the warehouse although all materials cannot be reserved. If you select this option, you must manually repeat the release to warehouse process when the additional materials become available. For example, this is useful if you have the materials that you need to start a production, and can wait until the additional materials become available.

  - Require that all materials are reserved before an order can be released to the warehouse.

You can specify the default value in the **Release to warehouse** field in **Production control parameters**. However, you can change the setting for a specific production order at any time.


> [!NOTE]
> <P>You can also automate all or part of the wave processing, and include containerization. For more information, see <A href="create-a-wave-template.md">Create a wave template</A> and <A href="set-up-containerization.md">Set up containerization</A>.</P>



The following diagram shows the process flow for manually creating, processing, and releasing a shipping wave.

The numbers correspond to the procedures later in this topic.

![Process for creating a wave](images/Dn553173.Waveprocess(WAXWave)(AX.60).png "Process for creating a wave")

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
<td><p><strong>Wave templates</strong></p></td>
<td><p>A wave template must be available for the type of wave to create. This means either a shipping wave, production wave, or kanban wave. Additionally, settings for automation must not be enabled on the wave template. Wave templates determine how to process waves for shipments, production, or kanbans. For more information, see <a href="create-a-wave-template.md">Create a wave template</a>.</p></td>
</tr>
</tbody>
</table>


## 1\. Create a wave manually

To manually create a wave, follow these steps:

1.  Depending on the type of wave to create, click one of the following:
    
    1.  Click **Warehouse management** \> **Common** \> **Waves** \> **Shipment waves** \> **All waves**. On the **Action Pane**, click **Wave**.
    
    2.  Click **Warehouse management** \> **Common** \> **Waves** \> **Production waves** \> **All production waves**. On the **Action Pane**, click **Production wave**.
    
    3.  Click **Warehouse management** \> **Common** \> **Waves** \> **Kanban waves** \> **All kanban waves**. On the **Action Pane**, click **Create wave**.

2.  In the **Description** field, enter a short description of the wave. This should indicate what you are processing in the wave.

3.  In the **Wave template name** field, select the wave template for the type of wave to create. The wave template contains the wave methods that will perform actions such as creating work for the wave. For example, the wave template for shipping waves can contain methods for creating loads, allocating lines to waves, replenishment, and creating picking work for the wave.

4.  Optional: If you want to use wave attributes as additional query criteria for the wave, select the attributes in the **Wave attributes** fields.

## 2\. Add loads or shipments, bill of material lines, or kanban picking list to a wave

If you are creating a wave manually, you must add the lines for a load, shipment, production order, or kanban order. This requires that a sales order, production order, or kanban order has been released to the warehouse.

To specify what to include in a wave, follow these steps:

1.  Depending on the type of wave to add lines to, do the following:
    
      - Click **Warehouse management** \> **Common** \> **Waves** \> **Shipment waves** \> **All waves**. On the **Action Pane**, click **Wave**.
    
      - Click **Warehouse management** \> **Common** \> **Waves** \> **Production waves** \> **All production waves**. On the **Action Pane**, click **Production wave**.
    
      - Click **Warehouse management** \> **Common** \> **Waves** \> **Kanban waves** \> **All kanban waves**. On the **Action Pane**, click **Create wave**.

2.  Select the wave. On the **Action Pane**, click one of the following:
    
      - **Maintain shipments**
    
      - **Maintain productions**
    
      - **Maintain kanban job picking lists**

3.  In the upper part of the window, select the line to add to the wave, and then click **Add to wave**. The line is moved to the **Wave lines** FastTab.
    
    Repeat this step for each line to add. To add all lines, click **Add all**.
    

    > [!TIP]
    > <P>For shipment waves, you can quickly find a particular order by selecting a custom filter in the <STRONG>Wave filter code</STRONG> field. Wave filter codes contain query criteria for shipments, which are created in the <STRONG>Wave filters</STRONG> form. This field is not available for production waves or kanban waves.</P>
    > <P>A green check mark in the <STRONG>On wave</STRONG> column indicates that the shipment has been added to the wave.</P>



## 3\. Process the wave to create the picking work

You can process a wave only when the status is **Created**. After you process a wave, the status of the wave is **Held**.


> [!NOTE]
> <P>If needed, you can add lines to the wave after it has been processed.</P>



To process a wave, follow these steps:

1.  Depending on the type of wave to process, do the following:
    
      - Click **Warehouse management** \> **Common** \> **Waves** \> **Shipment waves** \> **All waves**. On the **Action Pane**, click **Wave**.
    
      - Click **Warehouse management** \> **Common** \> **Waves** \> **Production waves** \> **All production waves**. On the **Action Pane**, click **Production wave**.
    
      - Click **Warehouse management** \> **Common** \> **Waves** \> **Kanban waves** \> **All kanban waves**. On the **Action Pane**, click **Create wave**.

2.  Select the wave to process. On the **Action Pane**, click **Process**.

## 4\. Release the wave to the warehouse to start picking and packing

You must process a wave before you can release it. When you release the wave, the picking work is available in the warehouse. You can cancel a wave after it is released, and add more lines, but you cannot change the lines.

To release a wave, follow these steps:

1.  Depending on the type of wave to release, do the following:
    
      - Click **Warehouse management** \> **Common** \> **Waves** \> **Shipment waves** \> **All waves**. On the **Action Pane**, click **Wave**.
    
      - Click **Warehouse management** \> **Common** \> **Waves** \> **Production waves** \> **All production waves**. On the **Action Pane**, click **Production wave**.
    
      - Click **Warehouse management** \> **Common** \> **Waves** \> **Kanban waves** \> **All kanban waves**. On the **Action Pane**, click **Create wave**.

2.  Select the wave to release. On the **Action Pane**, click **Release wave**.

## Optional: Cancel a wave

If needed, you can cancel a wave that has been processed.

To cancel a wave and the picking work that was created, follow these steps:

1.  Depending on the type of wave to cancel, click the following:
    
      - Click **Warehouse management** \> **Common** \> **Waves** \> **Shipment waves** \> **All waves**.
    
      - Click **Warehouse management** \> **Common** \> **Waves** \> **Production waves** \> **All production waves**.
    
      - Click **Warehouse management** \> **Common** \> **Waves** \> **Kanban waves** \> **All kanban waves**.

2.  Select the wave to cancel. On the **Action Pane**, on the **Work** tab, click **Cancel**.

## Related tasks

[Create a wave template](create-a-wave-template.md)

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

  


