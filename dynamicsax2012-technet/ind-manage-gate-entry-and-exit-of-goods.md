---
title: (IND) Manage gate entry and exit of goods
TOCTitle: (IND) Manage gate entry and exit of goods
ms:assetid: 5346537b-e655-47d8-9e59-c7bbc06fac32
ms:mtpsurl: https://technet.microsoft.com/library/Dn876577(v=AX.60)
ms:contentKeyID: 63378993
author: Khairunj
ms.date: 11/13/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.InventSiteGate_IN
- Forms.InventSiteInwardGateEntryListPage_IN
- Forms.InventSiteOutwardGateEntryListPage_IN
- gate exit
- gate management
- gate exit record
- gate entry record
- gate entry
- site gate
audience: Application User
ms.search.region: India
---

# (IND) Manage gate entry and exit of goods 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

You can record a gate entry for goods that are entering and exiting an organization. You can then assign the gate entry to a purchase order, sales order, transfer order, or return order.

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
<td><p><strong>Version</strong></p></td>
<td><p>Microsoft Dynamics AX 2012 R3 with cumulative update 8 (CU8)</p></td>
</tr>
<tr class="even">
<td><p><strong>Country/region</strong></p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: India</p></td>
</tr>
<tr class="odd">
<td><p><strong>Related setup tasks</strong></p></td>
<td><ol>
<li><p>In the <strong>General ledger parameters</strong> form, in the <strong>Sales tax</strong> area, in the <strong>Apply India taxes</strong> field group, select the <strong>Excise</strong> check box and the <strong>Customs</strong> check box. For more information, see <a href="https://technet.microsoft.com/library/jj677901(v=ax.60)">(IND) General ledger parameters (modified form)</a>.</p></li>
<li><p>In the <strong>Inventory and warehouse management parameters</strong> form, in the <strong>Gate management</strong> field group, select the <strong>Enable gate management</strong> check box.</p></li>
<li><p>In the <strong>Released product details</strong> form, on the <strong>General</strong> FastTab in the <strong>Excise</strong> field group, select the <strong>Excise record type</strong> for the product. For more information, see <a href="https://technet.microsoft.com/library/aa615563(v=ax.60)">Released product details (form)</a>.</p></li>
<li><p>Select the <strong>DSA</strong> check box to update the DSA register for product transactions. The <strong>Excise record type</strong> is set to <strong>None</strong> to enable the <strong>DSA</strong> check box.</p></li>
<li><p>Create a purchase order. For more information, see <a href="ind-create-a-purchase-order-and-post-charges.md">(IND) Create a purchase order and post charges</a>.</p></li>
<li><p>Create a sales return order. For more information, see <a href="create-or-edit-a-return-order.md">Create or edit a return order</a>.</p></li>
<li><p>Create a transfer order. For more information, see <a href="https://technet.microsoft.com/library/aa634530(v=ax.60)">Transfer orders (form)</a>.</p></li>
<li><p>On the <strong>Sites</strong> form, on the <strong>Number sequence</strong> FastTab, specify the number sequence for <strong>Gate inward</strong> and <strong>Gate outward</strong>. For more information, see <a href="create-sites.md">Create sites</a>.</p></li>
</ol></td>
</tr>
</tbody>
</table>


## Create gates for a site

You can create gates for a site and then indicate whether the gate is an entry gate or an exit gate. Many gates can be created for a site and multiple gates can be defined as entry gates or exit gates.

To create entry and exit gates for a site, follow these steps:

1.  Click **Inventory management** \> **Setup** \> **Inventory breakdown** \> **Inventory site gate**.

2.  Click **New**.

3.  Specify whether the gate is an entry gate or an exit gate in the **Gate type** field.

4.  Select the site location for the gate in the **Site** field.

5.  Enter the gate ID in the **Gate** field.

6.  Close the form.

## Create a gate entry record

You can record details about goods that are entering an organization. A gate entry record involves the following tasks:

  - Record a material receipt

  - Measure quantities of material received

  - Weigh the empty vehicle after unloading the material

  - Record the exit of the vehicle

  - Prepare a receipt document for the gate entry

To create a gate entry record, follow these steps:

1.  Click **Inventory management** \> **Periodic** \> **Gate management** \> **All inward gate entries**.

2.  Click **New** \> **Inward gate entry**.

3.  On the **Inward gate entry header** FastTab, select the factory gate and the warehouse.

4.  Select the reference document type and reference party that is based on the reference document type.
    

    > [!NOTE]
    > <P>The reference party is not applicable when the <STRONG>Reference document type</STRONG> field is set as <STRONG>Others</STRONG>.</P>



5.  Enter the transport details such as the lorry receipt, railway receipt number, or an air way bill number (LR/RR/AWB), the vehicle number, and the transporter name.

6.  Select the LR/RR/AWB date and the challan date.

7.  Enter challan number, the origin from which the goods are transported, the driver name, and a description of the goods being sent to the organization.

8.  On the **Inward gate entry lines** FastTab, specify the details about the goods, quantity of goods ordered, and received quantity of items in the challan.

9.  Click **Confirm vehicle entry** The **Status** field is updated and the vehicle entry time and date are recorded.
    

    > [!NOTE]
    > <P>The <STRONG>Confirm measurement</STRONG> and <STRONG>Confirm tare check</STRONG> buttons are disabled when the <STRONG>Reference document type</STRONG> field is set to <STRONG>Others</STRONG>, or the <STRONG>Skip measurement</STRONG> check box is selected.</P>



10. Optional: On the **Action pane**, click **Print** \> **Show gate entry** to print the gate entry slip. The gate entry details are updated in the related reference documents, such as the posted purchase product receipt, posted sales return order packing slip, or the posted transfer order.

11. On the **Line details** FastTab, on the **Measurement** tab, enter the manufacturer assigned number for the goods, the instrument that is used to measure the goods, the quantity of received goods, and the unit of measurement.

12. Click **Confirm measurement**.

13. On the **Line details** FastTab, on the **Tare check** tab, enter the tare weight of the goods and the unit of measurement.

14. Click **Confirm tare check** and then click **Confirm vehicle exit**. The vehicle exit date and time are saved. The reference documents such as the product receipt, sales return order packing slip, and transfer receipt are updated with the gate entry and measurement details.

## Create a gate exit record

You can record details about the goods that exit an organization. A gate exit record involves the following tasks:

  - Record entry of vehicle

  - Record tare weight on empty vehicle

  - Measure the quantity of items dispatched

  - Generate a challan on dispatch

  - Record vehicle exit

To create a gate exit record, follow these steps:

1.  Click **Inventory management** \> **Periodic** \> **Gate management** \> **All outward gate entries**.

2.  Click **New** \> **Outward gate entry**.

3.  On the **Outward gate entry header** FastTab, select the factory gate and warehouse.

4.  Select the reference document type and reference party that is based on the reference document type.
    

    > [!NOTE]
    > <P>The reference party is not applicable when the <STRONG>Reference document type</STRONG> field is set to <STRONG>Others</STRONG>.</P>



5.  Enter the transport details such as the lorry receipt, railway receipt number, or air way bill number (LR/RR/AWB), the vehicle number, and the transporter name.

6.  Select the LR/RR/AWB date and challan date.

7.  Enter challan number, the origin from which the goods are transported, the driver name, and a description for goods that are sent to the organization.

8.  On the **Outward gate entry lines** FastTab, specify the details about the goods, unit of goods, quantity of goods being sent, and quantity of items in the challan.

9.  Click **Confirm vehicle entry** The **Status** field is updated and the vehicle entry time and date are recorded.
    

    > [!NOTE]
    > <P>The <STRONG>Confirm measurement</STRONG> and <STRONG>Confirm tare check</STRONG> buttons are disabled when the <STRONG>Skip measurement</STRONG> check box is selected.</P>
    > <P>The <STRONG>Confirm measurement</STRONG> button is disabled when the <STRONG>Reference document type</STRONG> field is set as <STRONG>Others</STRONG>.</P>



10. Optional: On the **Action pane**, click **Print** \> **Show gate entry** to print the gate entry slip. The gate exit details are updated in the related reference documents such as the posted purchase return order, posted sales order, posted stock transfer order, or a returnable gate pass.

11. On the **Line details** FastTab, on the **Tare check** tab, enter the tare weight of goods and unit of measurement.

12. Click **Confirm tare check**.

13. On the **Line details** FastTab, on the **Measurement** tab, enter the manufacturer assigned number for the goods, the instrument that is used to measure the goods, the quantity of goods being sent, and unit of measurement.

14. Click **Confirm measurement** and then click **Confirm vehicle exit**. The vehicle gate arrival date and time, and the vehicle exit date and time are saved. The product receipt, sales return order packing slip, or transfer receipt are updated with gate entry and measurement details.

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
<td><p><strong>Security roles</strong></p></td>
<td><p>To perform this task, you must have the following roles:</p>
<ul>
<li><p>Receiving clerk</p></li>
<li><p>Materials manager</p></li>
<li><p>Warehouse worker</p></li>
<li><p>Warehouse manager</p></li>
<li><p>Shipping clerk</p></li>
</ul></td>
</tr>
</tbody>
</table>

  


