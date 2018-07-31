---
title: Common user interface elements
TOCTitle: Common user interface elements
ms:assetid: dee99d9e-eb8f-4aaa-9b8c-52a0cbbd897b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh801195(v=AX.60)
ms:contentKeyID: 43976729
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- UI
- user interface
- common UI
- common UI elements
audience: Application User
ms.search.region: Global
---

# Common user interface elements 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The topics in this section provide information about the Microsoft Dynamics AX workspace.

## Action menu

The action menu is a menu icon that provides additional actions. For example, in the **Configure account structures** form, the action menu is displayed next to segment rows. Click the action menu to set active dates and to copy, paste, delete, or move segments.

## Action pane - Action pane group, tab and button

The **Action Pane** divides the actions into role-tailored tabs and groups in order to make it easier to locate a relevant action.

  - Tabs – The first tab is the Dynamics AX menu, which contains general actions for Microsoft Dynamics AX. All tabs except the **General** tab are role-tailored, which means that they are related to an activity or a set of related activities that can be completed by one or more roles. For example, on the list of sales orders, the **Sell** tab is used by anyone who is completing sales activities, and the **Sell** tab contains all the actions that they need to complete their tasks. The **Collect** tab is used by anyone who is responsible for receiving money from customers and creating invoices. The **General** tab is not associated with a specific activity, but contains actions that are used by anyone on an infrequent basis.

  - Groups – Each tab contains groups of actions, and each group contains actions that are related by being of a similar type or belonging to the same process.

  - Actions – Actions can be displayed by clicking buttons.

## Account number control

The account number control can be displayed by using different field labels, including account number and ledger account. A ledger account includes a main account plus one or more financial dimensions. Financial dimensions are used to additionally analyze transaction information. The account number control includes a user-defined delimiter that separates the segments of the main account and financial dimension combinations. You can select the delimiter in the **General ledger parameters** form. The full account structure is displayed after a user enters a segment, which differentiates the account structure from other account structures.

**Example**

If the name or ID of a system-defined entity that a financial dimension is based on contains delimiters, you cannot copy the name or ID into a ledger account field. For example, suppose there is a bank account titled STD-EUR and an account structure set up in the following format:

Main account – Department – Bank account - Purpose

If you copy the bank account STD-EUR and paste it into the ledger account field, the ledger account will be displayed as follows:

Main account – Department – STD – EUR

Rather than:

Main account – Department – STD-EUR - Purpose

## Calendar control

The calendar control provides a way for you to select a date from a calendar. For example, in the **Manage addresses** form, you can select an effective date for the customer’s address using the calendar. You can also select an expiration date for the address using the calendar.

## FactBox

A FactBox provides information about a specific record in a grid or to an entire form. Some FactBoxes display numbers, links to other forms, or graphs that represent data for a record. For example, the **Customers** list page has a **Recent activity** FactBox that displays the last invoice amount and the last payment amount for a selected customer. By default, some list pages have more FactBoxes available than those that are displayed. Click the **View** button in the upper-right corner of the form, and then select FactBoxes to see a list of the available FactBoxes for the list page that you are currently viewing.

## FastTab

You can use FastTabs to view information that is related to a selected record, without having to open an additional form. FastTabs allow you to see the content of several FastTabs at the same time by allowing you to have more than one FastTab expanded. FastTabs are organized by activity and in order by work process.

## Grid

A grid displays the records on a list page. To sort records, click any of the columns and select the columns to display in the grid.

## Help menu

The Help menu is an icon button that is next to the View menu and that is on the toolbar of individual forms. Use this menu to access resources that you can use to learn more about Microsoft Dynamics AX. For more information, see [Using Help for Microsoft Dynamics AX](using-help-for-microsoft-dynamics-ax.md).

## Preview pane

The preview pane displays information that is related to a selected record. The type of information that is displayed depends on the type of record that you selected.


> [!NOTE]
> <P>A preview pane is not available for all list pages.</P>



## View menu

The View menu is button that is next to the Windows menu and that is on the toolbar of individual forms. Use this menu to hide or show various elements of the Microsoft Dynamics AX workspace, open the **Notification list**, or to modify the default view mode for the current form.

## Windows menu

The Windows menu is button that is under the **Refresh** button. Use this menu to see a list of forms that are currently open, but hidden from view, to open a new workspace, to close all open forms, or to display your Role Center.

  


