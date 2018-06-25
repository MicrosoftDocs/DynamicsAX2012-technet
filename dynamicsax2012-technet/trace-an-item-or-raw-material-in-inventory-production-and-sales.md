---
title: Trace an item or raw material in inventory, production, and sales
TOCTitle: Trace an item or raw material in inventory, production, and sales
ms:assetid: 4b75fcbe-7b63-4c44-b6fd-2ae2a936a962
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn313036(v=AX.60)
ms:contentKeyID: 54936280
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- trace
- recall
- tracing
- track
- Forms.InventTrackingDimTracing
- MsDynAx060.Forms.InventTrackingDimTracing
---

# Trace an item or raw material in inventory, production, and sales [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes how to trace an item or raw material upstream or downstream in the supply chain. Depending on the item or raw material and how your organization sets up its products, you can trace a combination of the item number and tracking dimension. You can also add more trace criteria, such as storage dimensions and a specific period of time.

After you trace the item or raw material as described in step 1, you can perform the next steps in any order.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 6 for AX 2012 R2.</P>



## 1\. Trace an item or raw material

To trace an item or raw material, follow these steps:

1.  Click **Inventory management** \> **Inquiries** \> **Tracing** \> **Item tracing**.

2.  On the **Trace criteria** FastTab, enter the following information:
    
    1.  In the **Item number** field, select the item to trace.
    
    2.  In the **Batch number**, **Serial number**, or **Vendor batch number** fields, select a tracking dimension that includes the item.
    
    3.  In the **Forward or backward** field, specify the direction to trace.
    
    4.  Provide any optional trace criteria.
    
    5.  On the **Action Pane**, click **Trace**.

## 2\. Identify sales orders to recall

To find sales orders that include the item or raw material and that have been shipped to customers, follow these steps:

1.  Click **Inventory management** \> **Inquiries** \> **Tracing** \> **Item tracing**.

2.  Enter the item number, tracking dimension, and any optional trace criteria to use.

3.  In the **Forward or backward** field, select **Backward**.

4.  To trace the item, on the **Action Pane**, click **Trace**.

5.  After the trace is finished, complete any of the following tasks:
    
      - To view a list of sales orders that have been shipped, click **Shipped sales orders**.
    
      - To print a report that shows all sales orders for the item or raw material, or a finished product that used them, click **Shipped to customers**. The report also contains contact information for each customer.
        

        > [!NOTE]
        > <P>When you trace backward, the report lists only the sales invoice lines for the item and the customers who received it. If you trace a raw material that is used as an ingredient, the report also describes all of the relations from the ingredient to the product. The additional information can be especially useful for customer service purposes.</P>



## 3\. Identify sales orders to stop from shipping

To find sales orders that haven’t yet shipped and that must be stopped, follow these steps:

1.  Click **Inventory management** \> **Inquiries** \> **Tracing** \> **Item tracing**.

2.  Enter the item number, tracking dimension, and any optional trace criteria to use.

3.  In the **Forward or backward** field, select **Forward**.

4.  To trace the item, on the **Action Pane**, click **Trace**.

5.  After the trace is finished, complete any of the following tasks:
    
      - To find the sales orders that have to be stopped, click **Not shipped sales orders**. These are the sales orders that are not shipped as of the current date, regardless of whether a date range was specified in the trace criteria.
    
      - To display a list of the customers who purchased the item, click **Customers**.

## 4\. Identify production orders to stop or prevent from starting

To identify the production orders that will use or are using an item or raw material, follow these steps:

1.  Click **Inventory management** \> **Inquiries** \> **Tracing** \> **Item tracing**.

2.  Enter the item number, tracking dimension, and any other relevant trace criteria.

3.  In the **Forward or backward** field, select **Backward**.

4.  On the **Action Pane**, click **Trace**.

5.  After the trace is finished, complete any of the following tasks:
    
      - To identify the production orders that you can prevent from starting, click **Pending orders**. These are the orders that are pending as of the current date, regardless of whether a date range was specified in the trace criteria.
    
      - To identify the production orders that you can stop, click **Production orders**. These are the orders that are at least partially reported as finished.
        

        > [!NOTE]
        > <P>The same production order does not appear in both summaries.</P>



## 5\. Determine the amount of the item or raw material that is still in inventory

To determine the amount of an item or raw material that you currently have in inventory, follow these steps:

1.  Click **Inventory management** \> **Inquiries** \> **Tracing** \> **Item tracing**.

2.  Enter the item number, tracking dimension, and any other relevant trace criteria.

3.  In the **Forward or backward** field, select **Backward**.

4.  On the **Action Pane**, click **Trace**.

5.  When the trace is finished, click the **Details** FastTab. The first node in the tree displays the quantity, in the inventory unit, of the traced item or raw material that is currently on hand.


> [!TIP]
> <P>To view the on-hand inventory for a document or transaction in the tree, on the <STRONG>Details</STRONG> FastTab, select the node, and then click <STRONG>On-hand inventory</STRONG>.</P>



## 6\. Identify the vendor who provided an item or raw material

To identify the vendor that the item or raw material was purchased from, follow these steps:

1.  Click **Inventory management** \> **Inquiries** \> **Tracing** \> **Item tracing**.

2.  Enter the item number, tracking dimension, and any other relevant trace criteria.

3.  In the **Forward or backward** field, select **Forward** or **Backward**.

4.  On the **Action Pane**, click **Trace**.

5.  Click **Vendors** to view the list of vendors who provided the item or raw material.

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
<td><p>LogisticsBasic</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>The following are examples of the security roles that are required to perform inquiries into the status of an inventory item and related items:</p>
<ul>
<li><p>Quality control clerk</p></li>
<li><p>Sales manager</p></li>
<li><p>Purchase manager</p></li>
<li><p>Production manager</p></li>
</ul></td>
</tr>
</tbody>
</table>


## See also

[About tracing items and raw materials in inventory, production, and sales](about-tracing-items-and-raw-materials-in-inventory-production-and-sales.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

