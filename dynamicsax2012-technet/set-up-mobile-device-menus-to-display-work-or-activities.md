---
title: Set up mobile device menus to display work or activities
TOCTitle: Set up mobile device menus to display work or activities
ms:assetid: a5c41be6-43c9-4e9c-8b98-12384e04191b
ms:mtpsurl: https://technet.microsoft.com/library/Dn553188(v=AX.60)
ms:contentKeyID: 62200129
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- display
- menu
- warehouse
- menu item
- mobile device
- Forms.WHSRFMenu
audience: Application User
ms.search.region: Global
---

# Set up mobile device menus to display work or activities 


_**Applies To:** Microsoft Dynamics AX 2012 R3_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Warehouse management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



This topic describes how to set up the menu that is displayed on a mobile device to display work or activities. The menu contains the menu items that a warehouse worker will use to perform their work. You create the structure of the mobile device menu by adding menu items and menus. When you add a menu, its menu items are also assigned.

## Set up mobile device menus to display work or activities

To create a menu for a mobile device, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Mobile device** \> **Mobile device menu**.

2.  Click **New** to create a new menu.

3.  In the **Name** field, enter a unique name for the mobile device menu. After you enter the name, a folder with the menu name is displayed on the **Menu structure** pane in the lower part of the form. The folder is the top node in the menu structure.

4.  In the **Description** field, enter a short description of the menu.

5.  To add menu items to the menu structure, in the **Available menus and menu items** pane, select a menu item or menu, and then drag it to the **Menu structure** pane. Repeat this step until you have added all of the menu items and menus that you want to include in the menu.

## Next step

The next step in the process of setting up a mobile device is to define the appearance of the display. For more information, see [Define the look and feel of mobile device displays](define-the-look-and-feel-of-mobile-device-displays.md).

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

  


