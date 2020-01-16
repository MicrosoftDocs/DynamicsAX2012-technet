---
title: The Microsoft Dynamics AX workspace
TOCTitle: The Microsoft Dynamics AX workspace
ms:assetid: 1a6cad45-a2a9-4726-82ae-2a7ca3e52c61
ms:mtpsurl: https://technet.microsoft.com/library/Gg230970(v=AX.60)
ms:contentKeyID: 36056121
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- Address bar
- Area page
- Content pane
- List page
- Navigation pane
- Role center
- Status bar
audience: Application User
ms.search.region: Global
---

# The Microsoft Dynamics AX workspace 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Microsoft Dynamics AX workspace is the main work area for Microsoft Dynamics AX. Use this main work area to open forms, list pages, Role Center pages, and reports.

The Microsoft Dynamics AX workspace is divided into the following areas.

## Navigation Pane

The Navigation Pane provides access to specific modules and your favorites list. The following table describes the different elements in the Navigation Pane.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Level</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Favorites</strong></p></td>
<td><p>This area is used to create and organize shortcuts to items, such as forms, reports, and queries.</p>
<p>For more information, see <a href="using-favorites.md">Using favorites</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Module menu items</strong></p></td>
<td><p>The area directly under the <strong>Favorites</strong> contains menu items that link to the area page, list pages, forms, and reports for a module.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Module names</strong></p></td>
<td><p>The module buttons are named according to their functionality, such as <strong>General ledger</strong>, <strong>Accounts payable</strong>, and <strong>Accounts receivable</strong>. Click a module button to display the module's area page and to display links to the list pages, forms, and reports for that module in the Navigation Pane.</p></td>
</tr>
</tbody>
</table>


## Content pane

The content pane appears to the right of the Navigation Pane. The content pane displays content pages, such as area pages, Role Centers, and list pages.

## Role Centers

If your organization uses Role Centers, your Role Center is your default home page within Microsoft Dynamics AX. In the Navigation Pane, click **Home** to display your Role Center.

For more information about Role Centers, see [Role centers](role-centers.md).

The following graphic illustrates how a Role Center looks in the main workspace.

![A Microsoft Dynamics AX role center](images/Gg230970.ContentPane3(AX.60).jpg "A Microsoft Dynamics AX role center")

## List pages

You can use list pages to view a list of similar records, select a record, and then perform actions against that record.

For more information about list pages, see [List pages](list-pages.md).

The following graphic illustrates how a list page looks in the main workspace.

![A Microsoft Dynamics AX list page](images/Gg230970.ContentPane2(AX.60).jpg "A Microsoft Dynamics AX list page")

## Area pages

To display an area page, click a module button in the Navigation Pane. Area pages contain menu items that link to frequently used list pages, forms, and reports for a module.

Menu items are displayed in a tree view that is divided into groups on the area page. Common groups that might appear on an area page are **Periodic**, **Setup**, **Reports**, and **Inquiries**.

To expand or collapse each group, the arrow in the upper-right corner of the group.

To expand a top-level menu item that appears in a group, click the item. For example, in the **General ledger** module, within the **Setup** group, click **Sales tax** to display a list of forms, such as the **Sales tax codes** form.

To collapse a top-level menu item, click the item.

The following graphic illustrates how an area page looks in the main workspace.

![The Microsoft Dynamics AX area page](images/Gg230970.ContentPane1(AX.60).jpg "The Microsoft Dynamics AX area page")

## Address bar

The address bar appears at the top of the Microsoft Dynamics AX workspace. You can use the address bar to move to list pages, to area pages, and to your Role Center.

The address bar has the following six distinct areas of importance:

## Forward and back buttons

To return to the last content page (Role Center, list page, or area page) that you viewed, click the **Back** button on the address bar.

To view one of the last pages that you visited in a session, click the arrow icon button to the right of the **Forward** button, and then select the page in the list.

## Address field

You can use the address field to move to specific content pages within Microsoft Dynamics AX. You can type a path or click the arrow icon button next to each entry in the path to select your next location.

The path that you type in the address field must meet the following general structure:

Company account **/** Module name **/** Area page group name **/** Top-level node name **/** menu item name

For example, to move to the **Bank accounts** list page for company account DAT, you would type the following path:

**DAT/Cash and bank management/Common/Bank accounts**

## Refresh button

The **Refresh** button appears to the right of the address field. Click this button to refresh the content in the content page that is displayed.

## Search box

The search box is located to the right of the address field and you can use it to search through data, metadata, documents that are attached to records, and help topics in the Help Server. The search box is only available if you have Enterprise Search implemented. For more information about Enterprise Search, see [Using search](using-search.md).

## Windows menu

The **Windows** menu is an icon button that is under the **Refresh** button. Use this menu to see a list of forms that are currently open but hidden from view, to open a new workspace, to close all open forms, or to display your Role Center.

## View menu

The **View** menu is an icon button that is next to the **Windows** menu and that is on the toolbar of individual forms. Use this menu to hide or show various elements of the Microsoft Dynamics AX workspace, open the **Notification list**, or to modify the default view mode for the current form.

## Help menu

The **Help** menu is an icon button that is next to the **View** menu and that is on the toolbar of individual forms. Use this menu to access resources that you can use to learn more about Microsoft Dynamics AX. For more information, see [Using Help for Microsoft Dynamics AX](using-help-for-microsoft-dynamics-ax.md).

## Status bar

The status bar is located at the bottom of the workspace and on the bottom of individual forms. The status bar displays information about some buttons, fields, and menus that you are focused on, and can also display other useful information, such as your user name, the customer account that you are logged on to, and the number of notifications you have. To select the information to display on the status bar, select the check box for the information in the **Status bar** area of the **Options** form (Click **File** \> **Tools** \> **Options**).

Some forms, such as the **Worker** form, have additional buttons on the status bar that let you move to other records in the form or let you switch between the edit and view modes.

## See also

[Customize your workspace](customize-your-workspace.md)

[Common user interface elements](common-user-interface-elements.md)

[Options (class form)](https://technet.microsoft.com/library/aa618202\(v=ax.60\))

  


