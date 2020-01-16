---
title: Set up mobile device user accounts for workers
TOCTitle: Set up mobile device user accounts for workers
ms:assetid: 9e3d85c0-cda2-4b65-a360-132e88312c9e
ms:mtpsurl: https://technet.microsoft.com/library/Dn553186(v=AX.60)
ms:contentKeyID: 62200123
author: Khairunj
ms.date: 01/08/2016
mtps_version: v=AX.60
f1_keywords:
- Forms.WHSWorker
audience: Application User
ms.search.region: Global
---

# Set up mobile device user accounts for workers 


_**Applies To:** Microsoft Dynamics AX 2012 R3_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Warehouse management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



This procedure describes how to set up a user account for a warehouse worker to access a mobile device. This involves setting up a worker as a work user, selecting the mobile device menus that the worker can access, and specifying their log on information. You can create multiple work users for each worker.


> [!NOTE]
> <P>All of the work users that have been created for the worker must use the same language. The work user inherits the language setting from the worker through the user relation, which inherits the setting from the user. If a language is not specified for the worker or user, then the default language setting is the Active Directory service account that is used by the Warehouse Mobile Device Portal process to access Microsoft Dynamics AX 2012 R3.</P>



## Set up user accounts for workers

To set up a worker as a work user, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Work users** \> **Worker**.

2.  In the **Worker** column, select the worker, or click **New** to create a new work user.

3.  Optional: On the **Worker** FastTab, assign a packing profile and a container closing profile to the worker. For more information, see [Set up packing and container closing profiles for manual pack process](set-up-packing-and-container-closing-profiles-for-manual-pack-process.md).

4.  On the **Users** FastTab, in the **User ID** field, enter a unique identifier that the work user will use to log on to a mobile device.

5.  In the **User name** field, enter a short name for the user.

6.  In the **Default warehouse** field, select the warehouse in which the mobile device is used. The warehouse is displayed every time that the user logs on to the mobile device.

7.  In the **Menu name** field, select the mobile device menu that the work user can access.

8.  Press **Ctrl+S** on the keyboard to save the settings and open the **Set password** dialog box, where you can enter a password for the user.

9.  Optional: To block or suspend access to the mobile device menu, select the **Inactive** check box.

10. Optional: To grant the work user access to additional warehouses, click **Warehouses**.

11. Optional: On the **Work** FastTab, enter additional settings.
    
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
    <td><p><strong>Allow pick location override</strong></p></td>
    <td><p>Select this check box to allow the work user to override the default pick location when picking an item.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Allow put location override</strong></p></td>
    <td><p>Select this check box to allow the work user to override the default put location when putting an item away.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Is a cycle count supervisor</strong></p></td>
    <td><p>Select this check box to allow the work user to approve quantity differences that are found during cycle count work.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Maximum percentage limit</strong></p></td>
    <td><p>Enter the highest percentage that a cycle count can differ from the expected quantity without requiring approval by a cycle count supervisor.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Maximum quantity limit</strong></p></td>
    <td><p>Enter the total quantity that a cycle count can differ from the expected quantity without requiring approval by a cycle count supervisor.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Maximum value limit</strong></p></td>
    <td><p>Enter the maximum amount that the cost of the inventory can differ from the expected cost without requiring approval by a cycle count supervisor.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Allow sales order over picking</strong></p></td>
    <td><p>This option is only available in Microsoft Dynamics AX 2012 R3 Cumulative Update 10 or from KB 3107010.</p>
    <p>Select this option to allow the work user to enter a higher quantity than specified during a sales order pick operation.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Allow transfer order over picking</strong></p></td>
    <td><p>This option is only available in Microsoft Dynamics AX 2012 R3 Cumulative Update 10 or from KB 3107010.</p>
    <p>Select this option to allow the work user to enter a higher quantity than specified during a transfer order pick operation.</p></td>
    </tr>
    </tbody>
    </table>
    

    > [!NOTE]
    > <P>If you specify limits for differences, approval is needed after the required number of recounts has been performed. The required number of recounts is specified on the mobile device menu item in the <STRONG>Number of attempts</STRONG> field on the <STRONG>Mobile device cycle counting</STRONG> form.</P>



## Related tasks

[Define the types of work orders that a mobile device can process](define-the-types-of-work-orders-that-a-mobile-device-can-process.md)

[Set up mobile device menus to display work or activities](set-up-mobile-device-menus-to-display-work-or-activities.md)

[Define the look and feel of mobile device displays](define-the-look-and-feel-of-mobile-device-displays.md)

[Configure mobile devices for warehouse work](configure-mobile-devices-for-warehouse-work.md)

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

  


