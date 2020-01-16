---
title: Configure mobile devices for warehouse work
TOCTitle: Configure mobile devices for warehouse work
ms:assetid: fd207796-b021-4e7e-804c-71a7bee7124d
ms:mtpsurl: https://technet.microsoft.com/library/Dn553216(v=AX.60)
ms:contentKeyID: 62554032
author: Khairunj
ms.date: 01/08/2016
mtps_version: v=AX.60
f1_keywords:
- scan
- device
- menu item
- mobile device
- Forms.WHSRFMenuItem
- hand held
- rf
audience: Application User
ms.search.region: Global
---

# Configure mobile devices for warehouse work 


_**Applies To:** Microsoft Dynamics AX 2012 R3_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Warehouse management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



This topic describes how to configure the menu items that workers use to perform work on a mobile device. Menu items are displayed on the mobile device menu. The configuration of these menu items determines what the menu item is used for. You can configure menu items to do the following:

  - Process an inquiry or perform an activity, such as print a label, generate license plate numbers, start a production order, or quickly look up information about items in a location.

  - Create work that will be performed through another process. For example, receiving an item for a purchase order can create put away work for another worker.

  - Perform work that was created by another process. This is called existing work. For example, performing put away work that was created when an item was received for a purchase order.

The procedures in this topic describe how to configure a menu item for each of these activities.


> [!NOTE]
> <P>Depending on the mode that you select for the menu item, and if the menu item is used to perform existing work, additional fields are available for the menu item. These include required and optional fields for the menu item. For information about the additional field selections, see the section titled “Additional menu item options” in this topic.</P>



## Enter the menu item text that is displayed in the mobile device menu

For all menu items, you must enter the text that is displayed in the mobile device menu to indicate what the menu item is used for. For example, if the menu item starts a cycle count, the name and title could be “Cycle Count.”

To enter the text that is displayed in the menu, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Mobile device** \> **Mobile device menu items**.

2.  Click **New** to create a new menu item.

3.  In the **Menu item name** and **Title** fields, enter a name for the menu item, and the title to display on the mobile device.

## Set up a menu item for activities and inquiries

You can configure a menu item to perform general activities or inquiries that do not create work. For example, these include activities such as reprinting license plate labels, and inquiries about the items in a location.

To set up a menu item to perform general activities or inquiries, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Mobile device** \> **Mobile device menu items**.

2.  Enter a name and a title for the menu item.

3.  In the **Mode** field, select **Indirect**.

4.  On the **General** FastTab, in the **Activity code** field, select the activity or inquiry that the menu item will perform. The following table describes the activities and inquiries that are available.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Options</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>None</strong></p></td>
    <td><p>This default value does not enable an activity or inquiry.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>About</strong></p></td>
    <td><p>View information about the system, such as the version number, warehouse ID, and the worker who is currently logged in.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Change warehouse</strong></p></td>
    <td><p>Change the warehouse that a worker is logged on to.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Location enquiry</strong></p></td>
    <td><p>View information about all items and quantities for a location.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>License plate enquiry</strong></p></td>
    <td><p>View the quantity of items on a license plate, and the location of the license plate.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Start production order</strong></p></td>
    <td><p>Start a production order.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Production scrap</strong></p></td>
    <td><p>Enter the quantity of scrap that was created during production for each bill of materials line.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Production last pallet</strong></p></td>
    <td><p>Indicate that the last pallet of items has been produced for a production order, and that the status of the production order must be updated to reported as finished by using the Microsoft Dynamics AX 2012 R3 client.</p>
    <p>The status of the raw materials that were not consumed during production is reverted from <strong>Picked</strong> to <strong>On order</strong>, and the items can be returned to inventory.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Item inquiry</strong></p></td>
    <td><p>Scan an item to determine where it is in the warehouse. The inquiry returns all locations and quantities for the scanned item.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Reprint label</strong></p></td>
    <td><p>Reprint a license plate label.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>License plate build</strong></p></td>
    <td><p>Create a parent license plate by combining multiple license plates in the same location. This is useful if you move multiple license plates at the same time. After the parent license plate is moved, you must perform a license plate break before you can pick items from each license plate.</p>
    <div class="alert">

    > [!TIP]
    > <P>To move a parent license plate, you must use a mobile device that is configured to create work for movements.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>License plate break</strong></p></td>
    <td><p>Break up a license plate build so that you can pick items from the license plates that were in the build.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Driver check in</strong></p></td>
    <td><p>If you’re using <strong>Transportation management</strong>, register that a driver has arrived by scanning the outbound load ID, appointment ID, or shipment ID. This requires that a load is assigned to the appointment, and that the status of the load is <strong>Loaded</strong>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Driver check out</strong></p></td>
    <td><p>N/A</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Flush number sequence cache</strong></p></td>
    <td><p>Delete number sequence numbers from the number sequence cache. This activity is typically performed by a system administrator to resolve caching problems when accessed from mobile devices.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Change batch disposition</strong></p></td>
    <td><p>Select this check box to allow a worker to specify a batch disposition code for an item and batch. This selection will update the disposition code that is specified for the batch.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Display open work list</strong></p></td>
    <td><p>This option is only available in Microsoft Dynamics AX 2012 R3 Cumulative Update 9. It enables you to show a list of work available to a particular user, and the user can select the work to perform and will be directed to it. This display is expected to be viewed on tablet devices with screen sizes of 7 inches or more.</p>
    <p>When you select this option, the <strong>Edit query</strong> and <strong>Field list</strong> menu items are enabled.</p>
    <p>The <strong>Edit query</strong> form enables you to set up criteria for what work to show on the list.</p>
    <p>The <strong>Field list</strong> form is used to select what fields to show in the work list. For example, you may want to reduce the number of fields that are visible to make it quicker for the user to select the most appropriate work item. You can also select how many work records per page should be shown in the <strong>Records per page</strong> field on the <strong>General</strong> FastTab. If the <strong>Allow users to filter work by transaction type</strong> checkbox is selected, the user will see an additional <strong>Filter work</strong> control on the work list which allows them to filter by transaction type.</p>
    <div class="alert">

    > [!NOTE]
    > <P>The user will only see work in the work list that they have permission to access. You need to make sure they have permission for one or more user-directed menu items that support the specific work class type(s) that they should be able to access. Permissions will also be verified when the user attempts to perform work from the list.</P>


    </div></td>
    </tr>
    </tbody>
    </table>


## Set up a menu item to create work for another worker or process

You can set up a menu item that will create work for another worker after an initial action is performed on the mobile device. For example, when one worker uses a mobile device to receive an item, put away work is created for another worker.

To set up a menu item that will create work, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Mobile device** \> **Mobile device menu items**.

2.  Enter a name and a title for the menu item.

3.  In the **Mode** field, select **Work**.

4.  On the **General** FastTab, in the **Work creation process** field, select the process that will generate work. In the following table, the options are arranged by work order type.  
    

    > [!NOTE]
    > <P>Depending on your selection in the <STRONG>Work creation process</STRONG> field, additional fields are available on the <STRONG>General</STRONG> FastTab. For a description of each field, see the section titled “Additional menu item options” in this topic.</P>

    
    <table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th> <p>
   
	 Work order type
  </p> </th>
    <th> <p>
   
	 Option
  </p> </th>
    <th> <p>
   
	 Description
  </p> </th>
  </tr>
  <tr>
    <td rowspan="7"> <p>
   
	 Purchase order
  </p> </td>
    <td> <p> <strong>Purchase order line receiving</strong> </p> </td>
    <td> <p>
   
	 Register the receipt of a quantity of an item by using the purchase order number and purchase order line number. Create put away work for another worker.
  </p> </td>
  </tr>
  <tr>
    <td> <p> <strong>Purchase order line receiving and put away</strong> </p> </td>
    <td> <p>
   
	 Register the receipt of a quantity of an item by using the purchase order number and purchase order line number, and put the items away. The same worker will perform both actions.
  </p> </td>
  </tr>
  <tr>
    <td> <p> <strong>Purchase order item receiving</strong> </p> </td>
    <td> <p>
   
	 Register the receipt of a quantity of an item for a purchase order by registering the purchase order number and item number. Create put away work for another worker.
  </p> </td>
  </tr>
  <tr>
    <td> <p> <strong>Purchase order item receiving and put away</strong> </p> </td>
    <td> <p>
   
	 Register the receipt of a quantity of an item for a purchase order by registering the purchase order number, and put the item away. The same worker will perform both actions.
  </p> </td>
  </tr>
  <tr>
    <td> <p> <strong>License plate receiving</strong> </p> </td>
    <td> <p>
   
	 Receive an inbound load by using the license plate ID.
  </p> </td>
  </tr>
  <tr>
    <td> <p> <strong>Load item receiving</strong> </p> </td>
    <td> <p>
   
	 Register the receipt of a quantity for a load by using the load ID. The item number and product dimensions match the receipt to the purchase order lines. Create put away work for another worker.
  </p> </td>
  </tr>
  <tr>
    <td> <p> <strong>Load item receiving and put away</strong> </p> </td>
    <td> <p>
   
	 Register the receipt of a load by using the load ID, and put the items away. The item number and product dimensions match the receipt to the purchase order lines. The same worker will perform both actions.
  </p> </td>
  </tr>
  <tr>
    <td rowspan="2"> <p>
   
	 Return order
  </p> </td>
    <td> <p> <strong>Return order receiving</strong> </p> </td>
    <td> <p>
   
	 Register the receipt of a quantity of an item by registering the RMA number, and create put away work for another worker.
  </p> </td>
  </tr>
  <tr>
    <td> <p> <strong>Return order receiving and put away</strong> </p> </td>
    <td> <p>
   
	 Register the receipt of a quantity of an item by registering the RMA number, and put the items away. The same worker will perform both actions.
  </p> </td>
  </tr>
  <tr>
    <td rowspan="4"> <p>
   
	 Transfer order
  </p> </td>
    <td> <p> <strong>Transfer order item receiving</strong> </p> </td>
    <td> <p>
   
	 Register the receipt of a quantity of an item, and create put away work for another worker.
  </p> <div class="alert"><table><tr><th align="left"><img runat="server" AltText="Note" src="https://technet.microsoft.com/en-us/Dn553216.alert_note(AX.60).gif" title="Note" alt="Note" /><strong>Note </strong></th></tr><tr><td> <p>
   
	 Use this option only if the items were shipped from a warehouse that is not enabled for warehouse management processes.
  </p> </td></tr></table></div></td>
  </tr>
  <tr>
    <td> <p> <strong>Transfer order item receiving and put away</strong> </p> </td>
    <td> <p>
   
	 Register the receipt of a quantity of an item, and put the items away. The same worker will perform both actions.
  </p> <div class="alert"><table><tr><th align="left"><img runat="server" AltText="Note" src="https://technet.microsoft.com/en-us/Dn553216.alert_note(AX.60).gif" title="Note" alt="Note" /><strong>Note </strong></th></tr><tr><td> <p>
   
	 Use this option only if the items were shipped from a warehouse that is not enabled for warehouse management processes. 
  </p> </td></tr></table></div></td>
  </tr>
  <tr>
    <td> <p> <strong>Transfer order line receiving</strong> </p> </td>
    <td> <p>
   
	 Register the receipt of a quantity of an item, and create put away work for another worker.
  </p> </td>
  </tr>
  <tr>
    <td> <p> <strong>Transfer order line receiving and put away</strong> </p> </td>
    <td> <p>
   
	 Register the receipt of a quantity of an item, and put the items away. The same worker will perform both actions.
  </p> </td>
  </tr>
  <tr>
    <td rowspan="4"> <p>
   
	 Production
  </p> </td>
    <td> <p> <strong>Report as finished</strong> </p> </td>
    <td> <p>
   
	 Register a quantity of a finished item that has been finished for a production. The quantity can be some or all of the quantity that was planned for production. Create put away work for another worker.
  </p> </td>
  </tr>
  <tr>
    <td> <p> <strong>Report as finished and put away</strong> </p> </td>
    <td> <p>
   
	 Register a quantity of a finished item that has been finished for a production, and put the items away. The quantity can be some or all of the quantity that was planned for production. The same worker will perform all actions.
  </p> </td>
  </tr>
  <tr>
    <td> <p> <strong>Kanban</strong> </p> </td>
    <td> <p>
   
	 Indicate that a Kanban is completed, and create put away work for another worker.
  </p> </td>
  </tr>
  <tr>
    <td> <p> <strong>Kanban put away</strong> </p> </td>
    <td> <p>
   
	 Indicate that a Kanban is completed, and put away the items. The same worker will perform all actions.
  </p> </td>
  </tr>
  <tr>
    <td rowspan="5"> <p>
   
	 Inventory
  </p> </td>
    <td> <p> <strong>Movement</strong> </p> </td>
    <td> <p>
   
	 Register that items have been moved from one location to another. The worker specifies the location that the items are moved from and where they are moved to.
  </p> </td>
  </tr>
  <tr>
    <td> <p> <strong>Quarantine</strong> </p> </td>
    <td> <p>
   
	 Change the status of the on-hand inventory for a license plate or location to make damaged or missing inventory items unavailable.
  </p> </td>
  </tr>
  <tr>
    <td> <p> <strong>Movement by template</strong> </p> </td>
    <td> <p>
   
	 Move items from one location to another in a semi-automated manner. The worker selects the location to move items from, and Microsoft Dynamics AX uses the location directive to determine where to move it to.
  </p> </td>
  </tr>
  <tr>
    <td> <p> <strong>Warehouse transfer</strong> </p> </td>
    <td> <p>
   
	 Register that items have been transferred from one warehouse to another. This requires that the worker is allowed to perform work in both warehouses.
  </p> <div class="alert"><table><tr><th align="left"><img runat="server" AltText="Note" src="https://technet.microsoft.com/en-us/Dn553216.alert_note(AX.60).gif" title="Note" alt="Note" /><strong>Note </strong></th></tr><tr><td> <p>
   
	 This menu item requires a default inventory transfer journal with the Voucher draw field set to Posting. 
  </p> </td></tr></table></div></td>
  </tr>
  <tr>
    <td> <p> <strong>License plate loading</strong> </p> </td>
    <td> <p>
   
	 Use this option when you are setting up your warehouse for the first time. Scan all of the license plates in all locations in the warehouse.
  </p> <p>
   
	 The locations must be license plate controlled. You cannot use this option if Serial number or Batch number are listed above Location in the Inventory reservation hierarchy. For more information, see <a href="set-up-reservation-hierarchies.md" runat="server" xmlns="http://www.w3.org/1999/xhtml">Set up reservation hierarchies</a>.
  </p> </td>
  </tr>
  <tr>
    <td rowspan="3"> <p>
   
	 Cycle count
  </p> </td>
    <td> <p> <strong>Adjustment in</strong> </p> </td>
    <td> <p>
   
	 Increase the quantity of items in inventory. Specify the location, license plate, item, quantity, unit of measure, and status.
  </p> </td>
  </tr>
  <tr>
    <td> <p> <strong>Adjustment out</strong> </p> </td>
    <td> <p>
   
	 Reduce the quantity of items in inventory. Specify the location, license plate, item, quantity, unit of measure, and status of the inventory.
  </p> </td>
  </tr>
  <tr>
    <td> <p> <strong>Spot cycle counting</strong> </p> </td>
    <td> <p>
   
	 Start a count for a location. The worker must count all items in the location. When the result of a count is less than the expected quantity, the missing quantity is considered a loss.
  </p> </td>
  </tr>
</table>


## Set up a menu item to process existing work

To set up a menu item that will process existing work, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Mobile device** \> **Mobile device menu items**.

2.  Enter a name and a title for the menu item.

3.  In the **Mode** field, select **Work**.

4.  Select the **Use existing work** check box.

5.  On the **General** FastTab, in the **Directed by** field, select the method to use to direct work to the mobile device. The following table describes the options.
    

    > [!NOTE]
    > <P>Depending on your selection in the <STRONG>Directed by</STRONG> field, additional fields are available on the <STRONG>General</STRONG> FastTab. For a description of each field, see the section titled “Additional menu item options” in this topic.</P>

    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Option</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>None</strong></p></td>
    <td><p>This default value does not process work.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>System directed</strong></p></td>
    <td><p>Microsoft Dynamics AX controls the type of work that is assigned to a worker and the sequence in which to perform it.</p>
    <p>When you select this option, you can click <strong>System-directed work</strong> to open the <strong>System-directed sorting order</strong> form, where you can set up sorting criteria for the work. The sorting criteria control the order in which the worker will perform the work. You can add as many criteria as needed.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>User directed</strong></p></td>
    <td><p>The worker selects the work to perform and the sequence in which to perform it.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>User grouping</strong></p></td>
    <td><p>The worker manually groups work. For example, this is useful when a worker can pick multiple items at the same time in a location. After the worker has finished picking all of the required items, he or she can put the items away.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>System grouping</strong></p></td>
    <td><p>Microsoft Dynamics AX groups work for the worker based on a specified field. For example, picking work is grouped when a worker scans a shipment ID, load ID, or any value that can link each work unit.</p>
    <p>If you select this option, the following fields are required:</p>
    <ul>
    <li><p><strong>System grouping field</strong> – Select the field that the worker will scan to group the work.</p></li>
    <li><p><strong>System grouping label</strong> - Enter text to inform the worker about what to scan to group the work.</p></li>
    </ul></td>
    </tr>
    <tr class="even">
    <td><p><strong>Validated user directed</strong></p></td>
    <td><p>The worker selects the work to perform when work is associated with a larger entity, such as a load or shipment. The worker determines the order in which to pick the items.</p>
    <p>If you select this option, you must select the following:</p>
    <ul>
    <li><p><strong>Validated User Directed Field</strong> – Select the field that the worker will scan to group the work.</p></li>
    <li><p><strong>Validated User Directed Label</strong> - Enter the text that will inform the worker about what to scan when picking work is grouped by the system.</p></li>
    </ul>
    <p>For example, this is useful when multiple pallets are staged for a load. If you select the <strong>LoadId</strong> field, the worker can pick any pallet that is associated with the load. An error message is displayed if a worker scans an item that is not associated with the load.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Cluster picking</strong></p></td>
    <td><p>The worker groups work into clusters. Clusters enable workers to pick items from a single location for multiple work orders at the same time. For more information, see <a href="set-up-cluster-picking.md">Set up cluster picking</a>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Cycle count grouping</strong></p></td>
    <td><p>The worker selects a zone, work pool, or location, and Microsoft Dynamics AX will assign work based on the selection. For more information, see <a href="set-up-cycle-counting-thresholds-and-plans-to-perform-cycle-counting.md">Set up cycle counting thresholds and plans to perform cycle counting</a>.</p>
    <p>If you select this option, you can also click <strong>Cycle counting</strong> to specify additional information to display, and specify the number of times that the worker must repeat the count if a difference is found.</p></td>
    </tr>
    </tbody>
    </table>


6.  On the **Work classes** FastTab, click **New**.

7.  In the **Work class ID** field, select the work class to control access to this task. You can add as many work classes as needed.

## Additional menu item options

Additional menu items options are available in the **Mobile device menu items** form, depending on the process that you’re configuring the menu item for. The following table describes these options.

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
<td><p><strong>Allow over pick</strong></p></td>
<td><p>This option is only available in Microsoft Dynamics AX 2012 R3 Cumulative Update 10 or from KB 3107010.</p>
<p>Select this option to allow users to over pick sales and transfer orders. The work user also needs to be set up to allow over picking. For more information, see <a href="set-up-mobile-device-user-accounts-for-workers.md">Set up mobile device user accounts for workers</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Allow splitting of work</strong></p></td>
<td><p>Select this check box to let users put items for a work order into more than one target license plate. This is useful, for example, when a target license plate is full and the worker must add the remaining items to another license plate. The worker can click <strong>Full</strong> to indicate that the license plate is full and stop receiving picking work for it. The put location for the picked items is then displayed, and the picking work that has already been completed is moved to a new work order. The remaining picking work for the target license plate stays on the original work order.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Anchoring</strong></p></td>
<td><p>Select this check box to allow workers to specify a location that will override the suggested staging or loading location. All of the remaining put away work is directed to the new location.</p>
<p>For example, this is useful when a worker is to put items for order 1 in a staging location by Dock 1, but can’t because a previous load hasn’t cleared the location. Rather than waiting for the Dock 1 staging location to become available, the worker decides to use the staging location for Dock 2 instead, and overrides the suggested staging location. The put location for all remaining items for the work order is updated to the Dock 2 staging location.</p>
<p>If you select this check box, you must specify whether to anchor by shipment or by load in the <strong>Anchor by</strong> field.</p></td>
</tr>
<tr class="even">
<td><p><strong>Anchor by</strong></p></td>
<td><p>If you are using anchoring, you must specify whether you want to anchor by shipment or by load.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Audit template ID</strong></p></td>
<td><p>Select the work audit template that will interrupt the work process for this menu item so that another operation can be performed. For example, if this menu item is for inbound work, the audit template might require that the worker checks the temperature in the delivery container.</p>
<p>The point at which the process is interrupted is specified on the audit template and can be, for example, when work is started or completed, or when its status changes.</p></td>
</tr>
<tr class="even">
<td><p><strong>Cluster profile ID</strong></p></td>
<td><p>Select the cluster profile to use for cluster picking. The cluster profile includes settings such as whether to create clusters automatically, the names of positions and the number of work units they can be assigned, when to break clusters into individual units, and whether verification is required. For more information, see <a href="set-up-cluster-picking.md">Set up cluster picking</a>.</p>
<p>This option is available only if <strong>Cluster picking</strong> is selected in the <strong>Directed by</strong> field.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Count total item quantity first</strong></p></td>
<td><p>Select this check box to require a worker to count the total quantity first during a count. If a difference is found, the worker must provide additional information, such as the license plate number, batch number, serial numbers, and so on.</p></td>
</tr>
<tr class="even">
<td><p><strong>Create movement</strong></p></td>
<td><p>Select this check box to enable a worker to create work for a movement without requiring the worker to perform the work immediately. For example, this is useful if a quality inspection has been completed, and the inspector wants the item to be moved from the quality inspection area.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Directive code</strong></p></td>
<td><p>To use a specific location directive, select the directive code that is associated the location directive. This option is available when you create work and the work creation process is <strong>Movement by template</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Disable cycle count thresholds</strong></p></td>
<td><p>Select this check box to ignore the cycle count thresholds. If you select this check box, cycle count work is not created when threshold values are exceeded. For more information, see <a href="set-up-cycle-counting-thresholds-and-plans-to-perform-cycle-counting.md">Set up cycle counting thresholds and plans to perform cycle counting</a>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Display batch disposition code</strong></p></td>
<td><p>Select this check box to display batch disposition codes. For example, you can display batch disposition codes when you receive a returned batch. This will enable workers to evaluate the status or quality of a batch, and select the appropriate code. The rules on the batch disposition code determine whether the batch will be available to other warehouse processes. For more information, see <a href="https://technet.microsoft.com/library/hh208612(v=ax.60)">Batch disposition master (form)</a>.</p>
<p>If you do not select this check box, one of the following is used:</p>
<ul>
<li><p>If you receive a new batch number, the default batch disposition code that is specified on the item model group is used.</p></li>
<li><p>The batch disposition code that is already assigned to the batch is used.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Display disposition code</strong></p></td>
<td><p>Select this check box to display disposition codes. For example, display disposition codes when receiving return items. This will enable workers to evaluate the status or quality of the items, and select the appropriate code. The rules on the disposition code determine whether the items will be available to other warehouse processes. For more information, see <a href="create-disposition-codes.md">Create disposition codes</a>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Display inventory status</strong></p></td>
<td><p>Select this check box to display the status of items in inventory. For more information, see <a href="set-up-an-inventory-status.md">Set up an inventory status</a>. This option is available for all menu items that use existing work, except cycle counting.</p></td>
</tr>
<tr class="even">
<td><p><strong>Display summary of pick screen</strong></p></td>
<td><p>Select this check box to display a summary of picking work for the selected work order. The summary is displayed until the first work line is processed for the work order.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Generate license plate</strong></p></td>
<td><p>Select this check box to generate a unique license plate number based on the number sequence selection. For example, you can generate a license plate number for items received for purchase orders.</p></td>
</tr>
<tr class="even">
<td><p><strong>Group put away</strong></p></td>
<td><p>Select this check box to group the put away work. This option is available when the work was grouped either by the worker or by Microsoft Dynamics AX. When the worker finishes all of the picking work in the group, put away work is created for the same group.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Inventory adjustment types</strong></p></td>
<td><p>Select the inventory adjustment type that determines the inventory counting journal that is used to post the adjustment, and whether to remove reservations. This option is available only for the <strong>Adjustment in</strong> or <strong>Adjustment out</strong> work creation processes. For more information, see <a href="https://technet.microsoft.com/library/aa552692(v=ax.60)">Journal names, Inventory (form)</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Override batch number</strong></p></td>
<td><p>Select this check box to allow workers who are reporting a quantity as finished for a production order to enter a batch number that differs from the batch number that is assigned to the production order.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Override license plate during put:</strong></p></td>
<td><p>This option is only available in Microsoft Dynamics AX 2012 R3 Cumulative Update 10 or from KB 3107010.</p>
<p>Select this option to allow the warehouse worker to override the target license plate from the work order, when performing a put operation. For example, this is useful when the warehouse worker wants to place some items on an existing pallet instead of using the target license plate from the work order. The warehouse worker can create a new target license plate or place the items on a license plate that already exists for the location.</p></td>
</tr>
<tr class="even">
<td><p><strong>Override target license plate</strong></p></td>
<td><p>Select this check box to allow workers to specify a target license plate number that differs from the suggested target license plate.</p>
<p>Use this option when the first pick for a work order is for the entire quantity of an item on a license plate. For example, this is useful when reusing a pallet.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Pick and pack</strong></p></td>
<td><p>Select this check box to allow workers to combine work for a sales order or load into a single work unit. The worker can perform work only for the sales order or load. For example, this is useful when you must increase a quantity for a sales order after the load, shipment, and work has been created for the sales order.</p>
<p>This option is available when the menu item uses existing work, and the work is directed by the user or system.</p></td>
</tr>
<tr class="even">
<td><p><strong>None</strong></p></td>
<td><p>Indicate if the worker must pick the oldest batch in a location first. The following options are available:</p>
<ul>
<li><p><strong>None</strong> – The worker can pick any batch in the location. No message is displayed.</p></li>
<li><p><strong>Warn</strong> – The worker can pick any batch in the location, but a warning message is displayed if a batch is not the oldest.</p></li>
<li><p><strong>Force</strong> – The worker must pick the oldest batch in the location. An error message is displayed if a batch is not the oldest.</p>
<div class="alert">

> [!NOTE]
> <P>This is relevant only if <STRONG>Batch number</STRONG> is lower than <STRONG>Location</STRONG> in the reservation hierarchy that is assigned to the item. For more information, see <A href="set-up-reservation-hierarchies.md">Set up reservation hierarchies</A>.</P>


</div></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Print label</strong></p></td>
<td><p>Select this check box to allow workers to print license plate labels. For more information, see <a href="configure-print-settings-for-labels.md">Configure print settings for labels</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>System grouping field</strong></p></td>
<td><p>Select the field that will determine how Microsoft Dynamics AX will group picking work for worker. For example, if you select the <strong>ShipmentId</strong> field, the worker will scan the shipment ID to group the picking work. All work for the shipment is then assigned to the worker.</p>
<p>This requires that you create a menu item to use existing work that is grouped by the system. You must also enter text in the <strong>System grouping label</strong> field to show the worker what to scan.</p></td>
</tr>
<tr class="odd">
<td><p><strong>System grouping label</strong></p></td>
<td><p>Enter the text that will inform the worker about what to scan when picking work is grouped by Microsoft Dynamics AX. For example, if you are using the <strong>ShipmentId</strong> field to group picking work by shipment, you might enter Shipment ID in the field.</p>
<p>This requires that you create a menu item to use existing work that is grouped by the system. You must also select the field to group by in the <strong>System grouping field</strong> field.</p></td>
</tr>
<tr class="even">
<td><p><strong>Use default data</strong></p></td>
<td><p>Select this check box to enable the <strong>Default data</strong> button, where you can select fields to display data that a worker typically needs in their daily work. For example, this is useful if a worker often picks items from the same location. You can select the <strong>From location</strong> field to display the location by default.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Validated User Directed Field</strong></p></td>
<td><p>Select the field that the worker will scan to group the work. For example, if you select <strong>LoadId</strong>, a worker can pick any work that is associated with a selected load.</p>
<p>You must also enter text in the <strong>Validated User Directed Label</strong> field to show the worker what to scan.</p></td>
</tr>
<tr class="even">
<td><p><strong>Validated User Directed Label</strong></p></td>
<td><p>Enter the text that will inform the worker about what to scan when picking work is grouped by a validated user directed field. For example, if you’re using the <strong>LoadId</strong> field to group picking work for a load, you might enter Load ID in the field.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Work template code</strong></p></td>
<td><p>Select the work template that will create the work for a process. For example, if you are receive an item for a purchase order, the put away work will be generated based on the work template.</p>
<p>If you do not select a work template, Microsoft Dynamics AX will assign a template based on query criteria. For more information, see <a href="create-a-work-template.md">Create a work template</a>.</p></td>
</tr>
</tbody>
</table>


## Require workers to confirm the product, location or quantity when picking items

You can set up work confirmations that require a worker to use a mobile device to register the location or quantity when performing work in the warehouse. This helps to ensure that the worker is at the correct location, or is handling the correct quantity of items. You can also enable Microsoft Dynamics AX to automatically confirm the worker’s registration. If you enable auto-confirmation, you cannot also require confirmations for location or quantity.


> [!NOTE]
> <P>If you’ve installed AX 2012 R3 CU8, work confirmations also include products and product variants. Additionally, you can register confirmations by scanning a bar code. Work confirmations in earlier versions do not include products, product variants, or bar code scanning. To confirm products and product variants, you must enter an ID for the product or product variant. This can be a product ID, product search ID, external ID, GTIN, or bar code. After you enter the ID or scan the bar code, the dimensions for the product variant are displayed on the mobile device.</P>



To set up work confirmations, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Mobile device** \> **Mobile device menu items**.

2.  Select the menu item, and then click **Work confirmation setup**.

3.  In the **Work type** field, select the work process that will use the confirmation.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Option</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Pick</strong></p></td>
    <td><p>Require confirmation when picking items.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Put</strong></p></td>
    <td><p>Require confirmation when putting items in a location.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Counting</strong></p></td>
    <td><p>Require confirmation during cycle counting.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Adjustments</strong></p></td>
    <td><p>Require confirmation when adjusting inventory quantities.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Custom</strong></p></td>
    <td><p>Require confirmation for custom work.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Quarantine</strong></p></td>
    <td><p>Require confirmation when moving items to quarantine.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>License plate building</strong></p></td>
    <td><p>Require confirmation when consolidating the items to build a license plate.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Print</strong></p></td>
    <td><p>Require confirmation when printing license plate labels.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Status change</strong></p></td>
    <td><p>Require confirmation when changing the status of inventory.</p></td>
    </tr>
    </tbody>
    </table>


4.  Select the confirmation that you want to require.
    

    > [!NOTE]
    > <P>You can only require product confirmation for pick and put work types.</P>



## Next step

After one or more menu items are created, the next step in the process of setting up a mobile device is to add the menu items to a mobile device menu. For more information, see [Set up mobile device menus to display work or activities](set-up-mobile-device-menus-to-display-work-or-activities.md).

## Related tasks

[Define the types of work orders that a mobile device can process](define-the-types-of-work-orders-that-a-mobile-device-can-process.md)

[Set up mobile device menus to display work or activities](set-up-mobile-device-menus-to-display-work-or-activities.md)

[Define the look and feel of mobile device displays](define-the-look-and-feel-of-mobile-device-displays.md)

[Set up mobile device user accounts for workers](set-up-mobile-device-user-accounts-for-workers.md)

[Configure print settings for labels](configure-print-settings-for-labels.md)

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


## See also

About setting up mobile devices for warehouse workers

  


