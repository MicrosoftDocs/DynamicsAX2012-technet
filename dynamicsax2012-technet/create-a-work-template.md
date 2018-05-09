---
title: Create a work template
TOCTitle: Create a work template
ms:assetid: 99de92ca-0cdd-41f2-9b2a-9247525680e1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn553184(v=AX.60)
ms:contentKeyID: 62221423
ms.date: 01/08/2016
mtps_version: v=AX.60
f1_keywords:
- adjustment
- work template
- Forms.WHSWorkTemplateTable
- Inbound transactions
- inventory transfer
- picking of inventory item
- Reservation of inventory item
- warehouse work
- work instructions
- msDynAx060.Forms.WHSWorkTemplateTable
---

# Create a work template 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Warehouse management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



A work template is used to create and process warehouse work at various stages in the warehouse management process. A valid work template should be specified in pairs of pick and put. You can create a work template for the following types of warehouse-related activities:

  - Inbound transactions.

  - Picking of inventory items.

  - Production tasks such as picking or putting of raw materials.

  - Inventory transfers.

  - Movement of inventory items between locations.

  - Replenishment of locations.

When you create a work template, you can specify a location directive code. If you specify a location directive code, Microsoft Dynamics AX validates the location directive to find and use a location. If a work template is created without a location directive code, Microsoft Dynamics AX searches the location directive using sequence numbers and queries to find and use an appropriate location. For more information about location directives, see [Create a location directive](create-a-location-directive.md).

## Create a work template

To create a work template, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Work** \> **Work templates**.

2.  In the **Work order type** field, select the type of warehouse transaction for which you want to create a work template.
    

    > [!NOTE]
    > <P>If you are running Microsoft Dynamics AX 2012 R3 Cumulative Update 8, the work order types <STRONG>Production order put away</STRONG> and <STRONG>Batch order put away</STRONG> have been replaced by <STRONG>Finished goods put away</STRONG> and <STRONG>Co-product and by-product put away</STRONG>. For more information, see <A href="set-up-production-processes-in-a-warehouse.md">Set up production processes in a warehouse</A>.</P>



3.  On the **Overview** tab, click **New** to create a work template.
    

    > [!NOTE]
    > <P>In the <STRONG>Sequence number</STRONG> field, the sequence in which the work is processed is displayed, in ascending order. You can modify the sequence, if needed.</P>



4.  In the **Work template code** field, enter a unique ID for the work template.

5.  Select the **Automatically process** check box to process work created by this work template when a wave is released. You should use this check box if there are inventory items that are not inventoried but must be sequenced for reporting, costing, or bill-of-lading purposes.

6.  In the **Work pool ID** field, select the unique ID for the work pool. This is used as the default work pool ID for grouping work.

7.  In the **Work priority** field, enter a value to define a work priority which can be different from the work priority that you have set in the **Warehouse management parameters** form. Work priority values are used during work flows for mobile devices, especially during work flows for system-directed work.

8.  Optional: Click **Edit query** to set the criteria that will apply to a particular work template. For example, if you want the created work template to be applied on item numbers that begin with 1000, you should set the **Field** as "Item number" and **Criteria** as "1000".
    
    1.  Click **OK** if you want to reset the grouping.
        
          - In the **Reset Grouping?** form, click **Yes** to modify the work template.
        
          - Click **No** to close the **Reset Grouping?** form.
    
    2.  In the **Edit query** form, click **Cancel** to close the form.

9.  On the **General** tab, enter additional settings for the work template by using the fields described in the following table.
    
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
    <td><p><strong>Maximum volume</strong></p></td>
    <td><p>Enter the maximum volume limit.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Maximum weight</strong></p></td>
    <td><p>Enter the maximum weight limit.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Maximum quantity</strong></p></td>
    <td><p>Enter the maximum quantity.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Maximum unit</strong></p></td>
    <td><p>Enter the maximum unit of measure (UOM).</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Batch allocation strategy</strong></p></td>
    <td><p>Specify how batches are allocated during the work creation process, by either the <strong>FEFO</strong> strategy or the <strong>LEFO</strong> strategy.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Packing quantity as maximum</strong></p></td>
    <td><p>Select this check box to ensure that the created work does not exceed the packing quantity limit that is specified in the load line in the <strong>Load planning workbench</strong> form.</p></td>
    </tr>
    </tbody>
    </table>


10. If you have Microsoft Dynamics AX 2012 R3 Cumulative Update 10 or KB 3084491 installed, you can specify work header maximums on the work template in order to split a work header when the sum or work lines exceeds the quantity specified. For example, the following additional fields will be available on the **General** tab:
    
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
    <td><p><strong>Maximum estimated pick time</strong></p></td>
    <td><p>Enter the maximum estimated pick time. The work header will be split when the total estimated time for the initial work pick line has reached the specified value.</p>
    <div class="alert">

    > [!NOTE]
    > <P>Labor standard lines with a Labor standards measurement type set to Work unit will not be accounted for when calculating the pick time.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>Maximum number of pick lines</strong></p></td>
    <td><p>Enter the maximum number of pick lines. The work header will be split when the number of initial work pick lines reaches the specified value.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Maximum total inventory quantity</strong></p></td>
    <td><p>Enter the maximum total inventory quantity. The work header will be split when the inventory work quantity has reached the specified quantity.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Maximum total volume</strong></p></td>
    <td><p>Enter the maximum total volume. The work header will be split when the total volume of the work header has reached the specified value.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Maximum total weight</strong></p></td>
    <td><p>Enter the maximum total weight. The work header will be split when the total weight of the work header has reached the specified value.</p></td>
    </tr>
    </tbody>
    </table>


11. In the lower pane, set the following fields to create the actual work for the selected work template.
    
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
    <td><p><strong>Work type</strong></p></td>
    <td><p>Select the work type to indicate whether the work is a pick action or a put action.</p>
    <div class="alert">

    > [!NOTE]
    > <P>The <STRONG>Valid</STRONG> check box on the <STRONG>Overview</STRONG> tab is selected if there is an even number of pick-put pairs for the selected work template.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>Custom work code</strong></p></td>
    <td><p>Select a code to configure custom mobile device menus for a mobile device work flow. This field is available only if you first select <strong>Custom</strong> in the <strong>Work type</strong> field.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Mandatory</strong></p></td>
    <td><p>Select this check box to indicate if the selected work must be performed.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Stop work</strong></p></td>
    <td><p>Select this check box to stop the work transaction. You can clear this setting on the mobile device to move to the next menu item.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Directive code</strong></p></td>
    <td><p>Select the unique ID for the directive code.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Work class ID</strong></p></td>
    <td><p>Select the unique ID for the work class. You use this value to configure the menu items on the mobile device and the types of work that those menu items can process.</p></td>
    </tr>
    </tbody>
    </table>


12. Optional: To configure custom printer settings for license plate labels, follow these steps:
    
    1.  In the lower pane, in the **Work type** field, select **Print**.
    
    2.  Click **Configure Print** to set label printing settings that will override the settings that you have defined in the **Warehouse management parameters** form. For more information, see “Configure printer settings for warehouse labels” in the [Configure print settings for labels](configure-print-settings-for-labels.md) topic.

## Next step

[Set up mobile device user accounts for workers](set-up-mobile-device-user-accounts-for-workers.md)

## Related tasks

[Create a location directive](create-a-location-directive.md)

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

