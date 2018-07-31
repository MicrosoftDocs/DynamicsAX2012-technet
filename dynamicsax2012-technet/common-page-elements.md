---
title: Common page elements
TOCTitle: Common page elements
ms:assetid: 2fc25a50-fed4-4a15-8d81-c179537b03ca
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208546(v=AX.60)
ms:contentKeyID: 36056301
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Common page elements 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic provides information about the elements and common features that appear on pages in Enterprise Portal for Microsoft Dynamics AX.

## Enterprise Portal page elements

The following figure shows a list page in Enterprise Portal. The following sections describe each feature that is shown in the figure.

![Enterprise Portal page components](images/Hh208546.EPPageComponents(AX.60).png "Enterprise Portal page components")

## 1: Top link bar

The top link bar includes links to home pages for Enterprise Portal sites. Site home pages are also named module sites. Each module site displays important data for a module. Your security roles in Microsoft Dynamics AX determine the site home pages that you can access.

## 2: SharePoint toolbar

The SharePoint toolbar includes the **Site Actions** menu. If you have the appropriate permissions in Microsoft SharePoint, you can create document libraries, configure site permissions, or perform other site-wide configurations by using this menu. The SharePoint toolbar also includes a navigation menu for SharePoint sites and ribbon tabs. Ribbon tabs provide access to commands that you can perform on the current Enterprise Portal page.

## 3: Action Pane

The Action Pane is divided into tabs that may contain button groups. Each button group may contain action buttons. Each action button can be used to move to another page, add records to list pages, or perform common tasks for a selected record. For example, you can create a new sales order for a customer by clicking an action button.

## 4: Quick Launch

The Quick Launch includes links to lists, task pages, and reports for the current module site. Your security roles in Microsoft Dynamics AX determine the lists, task pages, and reports that you can access from the Quick Launch.

## 5: Filters

Filters are available on Enterprise Portal list pages. This version of Microsoft Dynamics AX includes a quick filter and an advanced filter. For more information, see [List filters](list-filters.md).

## 6: Search

You can use Enterprise Search in Microsoft Dynamics AX to search through data, metadata, documents that are attached to records, and Help topics. You can use common nouns such as 'customer' and 'cash flow report' as the search term. You can also search for specific data, such as a customer name, product ID, or telephone number. Search results are displayed on a new page. To return to the previous page, click the **Back** button on the menu bar.

If the search results do not display the tables or fields that you need, ask your Microsoft Dynamics AX system administrator to configure additional tables and fields so that they are displayed in search results.

## 7: \<User name\> menu

This menu includes links to personal options such as your profile and personal settings. This menu also includes the **Personalize this Page** command, which you can use to customize your Role Center page. For more information, see [Modify Role center pages (Enterprise Portal)](modify-role-center-pages-enterprise-portal.md).

## 8: Company list

If your business or organization consists of multiple legal entities, you can open Enterprise Portal pages for other companies by using this list. Access to the other companies in this list is determined by your security roles in Microsoft Dynamics AX.

## 9: Enterprise Portal Help

Click this icon to open the Enterprise Portal Help viewer. The Help viewer displays a topic that corresponds to the Enterprise Portal page that you are currently viewing. You can search for additional topics in the Help viewer or browse the table of contents for the Help by using the breadcrumbs.

## 10: FactBoxes

FactBoxes display information that is related to a selected record, or information that is displayed in a form or on a list page. For example, if you click a customer name on a list page, a FactBox for the selected customer appears in the right pane. The FactBox can include the following FactBox parts: Primary address, Roles, Relationships, Contacts, and Related information. You can customize FactBoxes on Enterprise Portal pages by expanding or collapsing FactBox parts.

## Other common page elements

This section provides information about other common elements that appear on Enterprise Portal pages.

## Lists

Lists display information about multiple items as a grid, or a series of rows and columns. Depending on the type of page on which they are displayed, lists can be editable or read only. For example, lists on task pages may be editable, so that you can modify the data directly in the list.

Lists can include the following features:

  - You can sort the data in a list by clicking the column headings, if the column headings are links.

  - You can use filters to display subsets of some lists. For more information, see [List filters](list-filters.md).

  - When you select certain list items, a drop-down menu appears. You can use the commands on this menu to view or modify records, or to complete other tasks that are related to the selected item.

  - You can view related actions and tasks by using the toolbar, if a toolbar is displayed.

  - You can click the link for an item in the list to open the associated entity overview page for the item. For more information, see [Entity overview pages](entity-overview-pages.md).

## FastTabs

You can use FastTabs to view information that is related to a selected record, without having to open a separate Enterprise Portal page. The details page for a selected record can contain multiple FastTabs. Use the arrow to expand or collapse a FastTab.

## Lookups

Lookups are available for fields that include a list in which you can select among existing values. If a lookup is available for a field, an arrow icon appears to the right of the field. Click the icon to display the lookup. Lookups may contain multiple pages of items.

## Connect

The Connect Web part displays links to online resources, such as training, support, product updates, and information from the Microsoft Dynamics Community. These resources are customized for specific roles in Microsoft Dynamics AX. Therefore, you can collaborate with other users who have your role, learn about best practices, and access the training and support that you need. These resources can help you maximize your use of the product, and they can also help reduce downtime and support costs. For more information, see [Manage and use Connect (Enterprise Portal)](manage-and-use-connect-enterprise-portal.md).

## Infolog

The Infolog displays important messages, such as errors and warnings, when you attempt to save or commit data on a page.

The following table describes the types of Infolog messages.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Type</p></th>
<th><p>Description</p></th>
<th><p>Example</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Informational</p></td>
<td><p>The message is for information only. There are no errors on the page, and you can continue.</p></td>
<td><p>Supplementary items are available.</p></td>
</tr>
<tr class="even">
<td><p>Warning</p></td>
<td><p>There are errors on the page, but you can continue.</p></td>
<td><p>The customer's credit limit has been exceeded.</p></td>
</tr>
<tr class="odd">
<td><p>Error</p></td>
<td><p>There are errors on the page, and you must correct them before you can continue.</p></td>
<td><p>A sufficient quantity is not available.</p></td>
</tr>
</tbody>
</table>


## Workflow message bar

The workflow message bar displays the workflow actions that are required or available for selected items on a page. You can click a button in the message bar, such as **Submit** or **Approve**, to complete the workflow action. If an **Actions** button is displayed, you can click the button to view and select among the available actions. For more information, see [Respond to work items (Enterprise Portals)](respond-to-work-items-enterprise-portals.md).

## See also

[Role Centers (Enterprise Portal)](role-centers-enterprise-portal.md)

[About Role Center page components](about-role-center-page-components.md)

  


