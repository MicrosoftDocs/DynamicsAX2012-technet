---
title: Set up general warehouse parameters
TOCTitle: Set up general warehouse parameters
ms:assetid: 5e70fa76-2aeb-4272-8861-eb9d8c313166
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn553165(v=AX.60)
ms:contentKeyID: 62200076
ms.date: 02/17/2015
mtps_version: v=AX.60
f1_keywords:
- Forms.WHSParameters
- MsDynAx060.Forms.WHSParameters
- location profile
- shipping location
- warehouse parameters
- staging location
---

# Set up general warehouse parameters 


_**Applies To:** Microsoft Dynamics AX 2012 R3_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Warehouse management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



You must set up general warehouse parameters before you can perform inbound and outbound warehouse transactions. Use the **Warehouse management parameters** form to set up the following parameters:

  - Locations

  - License plates

  - Inventory adjustments

  - Work

  - Warehouse mobile devices

  - Inventory status

<!-- end list -->

1.  Click **Warehouse management** \> **Setup** \> **Warehouse management parameters**.

2.  On the **Company information** FastTab, enter the GS1 prefix that is used to generate license plates.

3.  On the **Location profiles** FastTab, select the location type that you want to use for user locations. User locations are warehouse locations that are license plate controlled, and allow the storage of mixed items and mixed inventory batches.

4.  On the **Location types** FastTab, select the location types for the staging and final shipping locations.

5.  On the **Receiving exceptions** FastTab, in the **Code for missing items from ASN** field, select the receiving exception code for the load lines that are missing from the Advance Ship Notice (ASN) document.

6.  On the **License plates** FastTab, select the default unit for license plates.

7.  On the **Auto release to warehouse** FastTab, in the **Value type** field, select **Price** or **Quantity** to specify whether the threshold percentage for item price or quantity is used to automatically release orders to a warehouse.

8.  In the **Fulfillment rate** field, enter the threshold percentage that is required to automatically release an order to a warehouse.

9.  On the **Adjustments** FastTab, in the **Default adjustment type code** field, select a code for the inventory adjustment type.

10. On the **Work** FastTab, configure the settings for work processing by using the fields described in the following table.
    
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
    <td><p><strong>Retain temporary work table</strong></p></td>
    <td><p>Select this check box to retain the temporary work table that is created during work processing.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Create work creation history log</strong></p></td>
    <td><p>Select this check box to create a detailed log of work creation.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Default work user ID</strong></p></td>
    <td><p>Select the user ID that is used for automated work transactions.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Work priority</strong></p></td>
    <td><p>Enter the number that is used as the default value for work priority. You can change the priority for a type of work in the <strong>Work templates</strong> form.</p></td>
    </tr>
    </tbody>
    </table>


11. On the **Batches** FastTab, enter the number of days that are required for mixing inventory batches.

12. On the **Mobile device** FastTab, configure the settings for warehouse mobile devices by using the fields described in the following table.
    
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
    <td><p><strong>Mobile device note type</strong></p></td>
    <td><p>Select the type of note that is displayed to a user during sales order picking.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Scanned quantity limit</strong></p></td>
    <td><p>Enter the maximum quantity of items that can be scanned by a mobile device for each session.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Use mobile device session logging</strong></p></td>
    <td><p>Select this check box to create a log of mobile device sessions.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Number of stored sessions</strong></p></td>
    <td><p>Enter the number of sessions that can be stored on the mobile device.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Number of stored errors</strong></p></td>
    <td><p>Enter the number of errors that can be stored on the mobile device.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Default warehouse transfer journal</strong></p></td>
    <td><p>Select the transfer journal that will be used for inventory movement transactions completed by using the mobile device.</p>
    <div>

    > [!NOTE]
    > <P>If you want to use the <STRONG>Warehouse transfer</STRONG> mobile device menu, the transfer journal selected should have the Voucher draw field set to Posting.</P>


    </div></td>
    </tr>
    </tbody>
    </table>


13. On the **Returns** FastTab, select a journal name that will be used to create a journal for return orders.

14. On the **Inventory status** FastTab, in the **Default inventory status ID** field, select the default inventory status for all inventory transactions.

## Next step

After you configure these parameters, you must perform the following tasks to complete the setup of the **Warehouse management** module.

[Set up number sequences for warehouse management](set-up-number-sequences-for-warehouse-management.md)

[Set up parameters to create a warehouse location](set-up-parameters-to-create-a-warehouse-location.md)

[Set up mobile device menus to display work or activities](set-up-mobile-device-menus-to-display-work-or-activities.md)

[Create a location directive](create-a-location-directive.md)

[Create a work template](create-a-work-template.md)

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

