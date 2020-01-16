---
title: Set up the picking workbench
TOCTitle: Set up the picking workbench
ms:assetid: dc395a94-c120-4223-b662-df02d36a90f3
ms:mtpsurl: https://technet.microsoft.com/library/Dn715985(v=AX.60)
ms:contentKeyID: 62200169
author: Khairunj
ms.date: 05/01/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up the picking workbench 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to configure a picking workbench and workbench profiles. You can use a picking workbench to organize paper-based picking operations for a warehouse. The picking workbench is where the picking and packing of items is arranged, which helps streamline the picking process. You can also enable boxing logic if you want Microsoft Dynamics AX to suggest an appropriate box size for the items to be packed in.

Each picking session is created for a single warehouse. Based on specified parameters, a set of open sales order lines will be picked, and added to a picking list to handle the capacity and priorities of the warehouse operations. Workbench profiles let you specify and save a standard set of parameters to apply when you create picking lists for a picking session. You can customize the number of picking lists per batch, and the maximum number of lines per picking list. Picking lists are grouped in picking batches and a worker will be assigned one batch of picking lists. Items can be selected for picking according to user-defined specifications.

For more information, see [Release items to warehouse by using the picking workbench](release-items-to-warehouse-by-using-the-picking-workbench.md).

## Configure the picking workbench setup for a warehouse

Configure the picking workbench if you want to specify how many sales orders you want to limit to a picking session, how many picking lines there should be in a batch, and how you want to split the delivery of items in the picking workbench.

To configure the picking workbench setup for a warehouse, follow these steps:

1.  Click **Inventory management** \> **Setup** \> **Inventory breakdown** \> **Warehouses**.

2.  Choose a warehouse from the **Warehouse** column.

3.  On the **Picking workbench** FastTab, in the **Pick lists per batch** field, enter the maximum number of picking lists that can be included in a batch. If this field is left blank or zero, there will be no limit on how many picking lists can be contained in a pick wave.
    

    > [!NOTE]
    > <P>You can limit the maximum number of sales orders and lines that can be included for a picking session by specifying the maximum number to be selected in the orders and lines fields on the <STRONG>Criteria</STRONG> FastTab.</P>



4.  In the **Maximum lines per picking list** field, enter the maximum number of picking lines that can be included in a picking list. If this field is left blank or zero, there will be no limit on how many picking lines can be contained in a picking list.
    

    > [!NOTE]
    > <P>The maximum lines per picking list could be less than what is on the order. Items can be selected for picking according to user-defined specifications. For example, if a courier collects items to be shipped at 14:00, then you can specify that the corresponding picking list will be distributed at noon. Alternatively, if items that shipped by air have a higher priority, you can prioritize picking lists that only contain those items.</P>



5.  Optional: Select the **Split by ship alone** check box if you want to split the picking batches for items that have been marked as ship alone on the **Released products** form. An item that is already packaged for shipping, such as a television, will be put on a separate picking list.

6.  Optional: Select the **Split by delivery mode** check box to split the picking list for items that are in a different delivery mode. Split by delivery mode will group items together that have the same mode of delivery, such as by sea or by air. If you don’t want this behavior to be controlled by Warehouse Management, then go to **Accounts receivable**, and under **Setup**, select **Accounts receivable parameters**. On the **Accounts receivable parameters** form, select **Summary update**. In the **Split based on** group, make sure that the **Delivery information** check box for the **Picking list** is selected.


> [!NOTE]
> <P>You can also split the picking process by using boxing logic. If you use boxing logic, picking routes will be split according to the proposed box sizes. For more information, see <A href="set-up-boxing-logic.md">Set up boxing logic</A>.</P>



## Configure workbench profiles

Workbench profiles enable you to create templates for search criteria that can be used to start a picking session in the picking workbench. When you create a profile, you specify the values that you want to use in the picking session. You can change these values before generating picking batches.

To create a new workbench profile, follow these steps:

1.  Click **Inventory management** \> **Setup** \> **Picking workbench** \> **Workbench profiles**.

2.  Click **New** to create a new record.

3.  Enter a description for the profile template.

4.  On the **General** tab, under **Group criteria**, in the **Select** field, choose how you want to group criteria on the template.

## Related tasks

[Release items to warehouse by using the picking workbench](release-items-to-warehouse-by-using-the-picking-workbench.md), [Set up boxing logic](set-up-boxing-logic.md).

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
<td><p>The main functionality of the picking workbench requires the <strong>Trade</strong> configuration key only. If you also enable the <strong>Call center</strong> configuration key, the <strong>Expedite</strong> and <strong>Payment method</strong> criteria options will also be enabled.</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>The following roles have access to the picking workbench:</p>
<ul>
<li><p>Buying agent (full control)</p></li>
<li><p>Sales clerk (full control)</p></li>
<li><p>Shipping clerk (full control)</p></li>
<li><p>Warehouse manager (view access only)</p></li>
<li><p>Warehouse worker (view access only)</p></li>
</ul></td>
</tr>
</tbody>
</table>


## See also

[About release sales order picking/release transfer order picking](about-release-sales-order-picking-release-transfer-order-picking.md)

  


