---
title: (JPN) Set up and use Microsoft Dynamics AX to assemble or disassemble fixed assets
TOCTitle: (JPN) Set up and use Microsoft Dynamics AX to assemble or disassemble fixed assets
ms:assetid: 06267752-0d30-472d-b4d9-0d76b7c0c5d8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn716010(v=AX.60)
ms:contentKeyID: 62200253
ms.date: 07/16/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.AssetParameters
- Forms.AssetTableListPage
- Forms.AssetTable
- assemble fixed assets
- fixed asset assembly
- fixed asset disassembly
- disassemble fixed assets
---

# (JPN) Set up and use Microsoft Dynamics AX to assemble or disassemble fixed assets 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to set up Microsoft Dynamics AX to allow the assembly or disassembly of a fixed asset using on-hand inventory items. You can then perform the following tasks:

  - Assemble a fixed asset using on-hand inventory items.

  - Disassemble the inventory items during fixed asset maintenance or after fixed asset disposal.

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
<td><p>Microsoft Dynamics AX 2012 R3</p></td>
</tr>
<tr class="even">
<td><p><strong>Country/region</strong></p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: Japan</p></td>
</tr>
<tr class="odd">
<td><p><strong>Related setup task</strong></p></td>
<td><p>Set up a fixed asset group. For more information, see <a href="set-up-fixed-asset-groups.md">Set up fixed asset groups</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Related task</strong></p></td>
<td><p>Create a fixed asset. For more information, see <a href="create-a-fixed-asset.md">Create a fixed asset</a>.</p></td>
</tr>
</tbody>
</table>


## Enable assembly or disassembly of fixed assets

Use the **Fixed assets parameters** form to set up the parameters to assemble or disassemble fixed assets.

To perform this task, follow these steps:

1.  Click **Fixed assets** \> **Setup** \> **Fixed assets parameters**.

2.  In the **Fixed assets** area, on the **General** FastTab, in the **Components** field group, select the **Inventory assemble and disassemble** check box to enable the assembly and disassembly of fixed assets using on-hand inventory items.

3.  In the **Reservation type** field, select one of the following methods to reserve on-hand inventory items during fixed asset assembly or disassembly.
    
      - **Manual** – Manually reserve items during fixed asset assembly.
    
      - **Automatic** – Items are reserved automatically during fixed asset assembly.

## Assemble a fixed asset using on-hand inventory items

Use the **Fixed asset components** form to reserve on-hand inventory items to an assembly component list for a fixed asset.

To perform this task, follow these steps:

1.  Click **Fixed assets** \> **Common** \> **Fixed assets** \> **Fixed assets**.

2.  Select or create a fixed asset. For more information, see [Create a fixed asset](create-a-fixed-asset.md).

3.  On the **Action Pane**, on the **Fixed asset** tab, click **Componentry** \> **Components**.
    

    > [!NOTE]
    > <P>You can define an assembly component list for a fixed asset in the <STRONG>Fixed asset components</STRONG> form only if you select the <STRONG>Inventory assemble and disassemble</STRONG> check box in the <STRONG>Fixed assets parameters</STRONG> form, and if the fixed asset has a status of <STRONG>Open</STRONG>.</P>



4.  In the **Fixed asset components** form, in the **Assembly list** area, click **Add** to create a component record, and then specify the item number, configuration, and reserved quantity for the inventory item.
    
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
    <td><p><strong>Transaction date</strong></p></td>
    <td><p>The date on which the fixed asset acquisition is posted.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Item number</strong></p></td>
    <td><p>Select an inventory item to reserve as a component.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Configuration</strong></p></td>
    <td><p>Select a configuration for the component.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Size</strong></p></td>
    <td><p>The size of the assembly component.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Color</strong></p></td>
    <td><p>The color of the assembly component.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Site</strong></p></td>
    <td><p>Enter the site from which the component is used to assemble a fixed asset.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Warehouse</strong></p></td>
    <td><p>Enter the warehouse from which the component is used to assemble a fixed asset.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Reserved quantity</strong></p></td>
    <td><p>Enter the quantity of the on-hand inventory item that is used as the fixed asset component.</p>
    <div>

    > [!NOTE]
    > <P>If you select <STRONG>Automatic</STRONG> in the <STRONG>Reservation type</STRONG> field in the <STRONG>Fixed assets parameters</STRONG> form, the quantity of the component that you specify is reserved automatically in the <STRONG>Physical reserved</STRONG> field in the <STRONG>On-hand</STRONG> form. If the quantity that you specify exceeds the quantity that is available for reservation, the <STRONG>Autoreservation</STRONG> form is displayed, where you can view the on-hand inventory transactions for the item and adjust the quantity. Click <STRONG>OK</STRONG>. For more information about reservations, see <A href="reserve-inventory-quantities.md">Reserve inventory quantities</A>, <A href="about-setting-up-inventory-reservations.md">About setting up inventory reservations</A>, and <A href="set-up-items-to-reserve.md">Set up items to reserve</A>.</P>
    > <P>–or–</P>
    > <P>If you select <STRONG>Manual</STRONG> in the <STRONG>Reservation type</STRONG> field in the <STRONG>Fixed assets parameters</STRONG> form, the quantity of the component that you specify is not reserved, but is deducted from the inventory when you post the acquisition journal or the acquisition adjustment journal.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Current quantity</strong></p></td>
    <td><p>The current quantity of the on-hand inventory item that is used in the assembly of the fixed asset. The value of the current quantity is automatically updated based on the value that you enter in the <strong>Reserved quantity</strong> field.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Cost</strong></p></td>
    <td><p>The cost of a single item.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Amount</strong></p></td>
    <td><p>The total item cost amount based on the quantity of the item.</p></td>
    </tr>
    </tbody>
    </table>


5.  On the **Detail** FastTab, specify the financial dimensions and the inventory dimensions for the component.

## Verify the inventory transaction details for an assembled component

Use the **Fixed asset components** form to verify the details for an assembled component.

1.  In the **Fixed asset components** form, in the **Assembly list** area, select an assembly list component, and then click **Inventory**.

2.  Click one of the following options to verify the inventory transaction details for the component:
    
      - **Transactions** – Opens the **Inventory transactions** form, where you can view the inventory transactions for the assembly component.
    
      - **On-hand** – Opens the **On-hand** form, where you can view the on-hand inventory of the assembly component.
    
      - **Reservation** – Opens the **Reservation** form, where you can view the quantity of the items in the on-hand inventory that are available for reservation.

After you have finished creating the assembly component list for a fixed asset, you can create and post an acquisition journal or an acquisition adjustment journal for the fixed asset to deduct the quantity of items that you specify in the **Reserved quantity** field from the on-hand inventory. For more information about how to create and post fixed asset journals, see [Journal voucher - Fixed assets (form)](https://technet.microsoft.com/en-us/library/aa620564\(v=ax.60\)).

You can reverse the acquisition transactions for assembled fixed assets by clicking **Reverse transaction** in the **Fixed asset transactions** form. For more information, see [Reverse a transaction](reverse-a-transaction.md). During the reversal, a reversed component line is created for each original line and contains the same financial and inventory dimensions, cost amounts, and negative quantities.

## Disassemble a fixed asset and return items to inventory

Use the **Fixed asset components** form to reserve the list of disassembly components that can be included in inventory and reused after the fixed asset is maintained or disposed of.

You can disassemble a fixed asset in one of the following ways:

  - Add the assembly component lines to the disassembly component list by clicking **Add to disassembly list** in the **Assembly list** area for a fixed asset for which you have posted the acquisition journal or the acquisition adjustment journal.

  - Manually add an item in the disassembly component list in the **Disassembly list** area in the **Fixed asset components** form.

To disassemble a fixed asset, follow these steps:

1.  Click **Fixed assets** \> **Common** \> **Fixed assets** \> **Fixed assets**.

2.  Select or create a fixed asset. For more information, see [Create a fixed asset](create-a-fixed-asset.md).

3.  On the **Action Pane**, on the **Fixed asset** tab, click **Componentry** \> **Components**.
    

    > [!NOTE]
    > <P>You can define a disassembly component list for a fixed asset in the <STRONG>Fixed asset components</STRONG> form only if you select the <STRONG>Inventory assemble and disassemble</STRONG> check box in the <STRONG>Fixed assets parameters</STRONG> form, and if the fixed asset has a status of <STRONG>Open</STRONG>.</P>



4.  If you have posted an acquisition journal or an acquisition adjustment journal for an assembled fixed asset, you can use the following steps to add the assembly list components to the disassembly list:
    
    1.  In the **Fixed asset components** form, in the **Assembly list** area, select the assembly component lines to add to the disassembly component list.
    
    2.  Click **Add to disassembly list**, and then in the **Add to disassembly list** dialog box, the current quantity of the items that are used as a fixed asset component is displayed in the **Available quantity** field.
    
    3.  In the **Add** field, specify the quantity of the item that is added to the disassembly list to return to the inventory.
    
    4.  Click **OK** to add the assembly component lines to the disassembly component list in the **Disassembly list** area.
    
    Alternatively, to manually add the assembly component list to the disassembly list, follow these steps:
    
    1.  In the **Fixed asset components** form, in the **Disassembly list** area, click **Add** to create a component record, and then specify the item number, configuration, and quantity for the inventory item.
        
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
        <td><p><strong>Transaction date</strong></p></td>
        <td><p>The posting date of the disposal or write-down journal.</p></td>
        </tr>
        <tr class="even">
        <td><p><strong>Item number</strong></p></td>
        <td><p>Select an inventory item to reserve as a disassembly component.</p></td>
        </tr>
        <tr class="odd">
        <td><p><strong>Configuration</strong></p></td>
        <td><p>Select a configuration for the component.</p></td>
        </tr>
        <tr class="even">
        <td><p><strong>Size</strong></p></td>
        <td><p>The size of the disassembly component.</p></td>
        </tr>
        <tr class="odd">
        <td><p><strong>Color</strong></p></td>
        <td><p>The color of the disassembly component.</p></td>
        </tr>
        <tr class="even">
        <td><p><strong>Site</strong></p></td>
        <td><p>Enter the site where the disassembled components are returned.</p></td>
        </tr>
        <tr class="odd">
        <td><p><strong>Warehouse</strong></p></td>
        <td><p>Enter the warehouse where the disassembled components are returned.</p></td>
        </tr>
        <tr class="even">
        <td><p><strong>Quantity</strong></p></td>
        <td><p>Enter the quantity of the component that is included in the inventory upon fixed asset disposal or maintenance. If this component is part of an assembly list, then the quantity should not exceed the current quantity of the assembly list.</p></td>
        </tr>
        <tr class="odd">
        <td><p><strong>Initial item cost</strong></p></td>
        <td><p>The initial cost of the items that are used in the assembly of the fixed asset.</p></td>
        </tr>
        <tr class="even">
        <td><p><strong>Total initial cost</strong></p></td>
        <td><p>The total cost of the items that are used in the assembly of the fixed asset.</p></td>
        </tr>
        <tr class="odd">
        <td><p><strong>Book cost</strong></p></td>
        <td><p>The fixed asset net book value divided by the total quantity of the items in the assembly list. The fixed asset net book value is the sum of the acquisition cost, acquisition adjustment, write-up or write-down adjustment, accumulated depreciation, and extra depreciation.</p></td>
        </tr>
        <tr class="even">
        <td><p><strong>Book amount</strong></p></td>
        <td><p>The total value of the book cost for the assembly items.</p></td>
        </tr>
        <tr class="odd">
        <td><p><strong>Market value</strong></p></td>
        <td><p>Enter the market value of the item.</p></td>
        </tr>
        </tbody>
        </table>
    
    2.  On the **Detail** FastTab, specify the financial dimensions and the inventory dimensions of the component.

5.  Click **Calculate prices**, and then in the **Calculate net book value for each component** dialog box, select one of the following considerations to calculate the net book values of all components:
    
      - **Proportion** – All of the revaluations of the components are assessed in proportion to their original values. The acquisition dates of the components are not considered in the calculation.
    
      - **Iteration** – The fixed asset revaluation transaction does not revalue all of the components in proportion to their original values. However, the components are revalued only to the sum that is included at the time of the revaluation. Therefore, the proportions of the items are based on their revalued costs.

6.  Click **Calculate** to calculate the book cost price of the components.

## Verify the inventory transaction details for a disassembled component

Use the **Fixed asset components** form to verify the details for a disassembled component.

1.  In the **Fixed asset components** form, in the **Disassembly list** area, select a disassembly component, and then click **Inventory**.

2.  Click one of the following options to verify the inventory transaction details for the component:
    
      - **Transactions** – Opens the **Inventory transactions** form, where you can view the inventory transactions of the disassembly component.
    
      - **On-hand** – Opens the **On-hand** form, where you can view the on-hand inventory of the disassembly component.
    
      - **Lot** – Opens the **Lot** form, where you can view issue and receipt transactions for the selected component.

You can create and post a write-down regulation journal or a disposal scrap journal to disassemble the fixed asset and return the reserved components to the inventory. For more information about how to create and post fixed asset journals, see [Journal voucher - Fixed assets (form)](https://technet.microsoft.com/en-us/library/aa620564\(v=ax.60\)).

## Related tasks

[About fixed asset acquisitions](about-fixed-asset-acquisitions.md)

[About fixed asset disposal](about-fixed-asset-disposal.md)

[About fixed asset reserves](about-fixed-asset-reserves.md)

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
<td><p>No configuration key is required for this task.</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>To set up AX 2012 to assemble or disassemble fixed assets, you must be a member of a security role that includes the following duties:</p>
<ul>
<li><p><strong>Approve fixed assets transactions</strong> (AssetFixedAssetsApprove)</p></li>
<li><p><strong>Maintain fixed assets</strong> (AssetFixedAssetsMaintain)</p></li>
<li><p><strong>Maintain fixed asset budget master from role center</strong> (AssetFixedAssetsTransRoleCenterMaintain)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To set up AX 2012 to assemble or disassemble fixed assets, you must be a member of a security role that includes the <strong>Maintain componentry</strong> (AssetComponentMaintain_JP) privilege.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

