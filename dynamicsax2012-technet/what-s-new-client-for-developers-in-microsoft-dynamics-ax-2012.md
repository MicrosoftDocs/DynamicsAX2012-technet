---
title: "What's New: Client for Developers in Microsoft Dynamics AX 2012"
TOCTitle: Client for Developers
ms:assetid: f02a290f-c646-445b-9b39-9ff3e5ab9c52
ms:mtpsurl: https://technet.microsoft.com/library/Gg848092(v=AX.60)
ms:contentKeyID: 35253320
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# What's New: Client for Developers in Microsoft Dynamics AX 2012 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The client is the Windows application that you use to view, update, and create data in Microsoft Dynamics AX 2012. This topic describes the changes and new features that affect how you use forms, controls, and data sources to customize the client.

## What is new or changed?

To customize the client in AX 2012, you can use the changes and new features in the following areas:

  - Forms

  - Controls

  - Data Sources

  - Parts

  - Search

### ![Gg848092.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Gg848092.collapse_all(en-us,AX.60).gif")Forms

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>Microsoft Dynamics AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Set the <strong>Style</strong> property of a form.</p></td>
<td><p>The feature was not available.</p></td>
<td><p>Specify the type of form to create.</p></td>
<td><p>After you set the <strong>Style</strong> property, several form properties are automatically updated so that they use the values that are required for the specified form.</p></td>
<td><p><a href="https://technet.microsoft.com/library/aa844397(v=ax.60)">Form Overview</a></p></td>
</tr>
<tr class="even">
<td><p>Create a <strong>Table of Contents</strong> form.</p></td>
<td><p>The feature was not available.</p></td>
<td><p>Use the table of contents pattern for small forms that display data on one or more tabs.</p></td>
<td><p>The <strong>Table of Contents</strong> form is a useful design pattern that you can use to create a form that sets parameter values. For example, the <strong>Accounts receivable parameter</strong> form uses the table of contents pattern.</p></td>
<td><p><a href="https://technet.microsoft.com/library/hh745331(v=ax.60)">Table of Content Forms</a></p></td>
</tr>
<tr class="odd">
<td><p>Use metadata to create a list page that appears in both the Microsoft Dynamics AX client and Enterprise Portal for Microsoft Dynamics AX.</p></td>
<td><p>If you wanted the same list to appear in both the client and Enterprise Portal, you had to create two separate list pages.</p></td>
<td><p>The list page that you create can appear in both the client and Enterprise Portal.</p></td>
<td><p>A single list page saves development time, and guarantees that the same list is displayed in both the client and Enterprise Portal.</p></td>
<td><p><a href="https://technet.microsoft.com/library/cc586969(v=ax.60)">How to: Create a List Page Form</a></p></td>
</tr>
<tr class="even">
<td><p>Add an Action Pane to a form.</p></td>
<td><p>Action Panes were limited to list pages and content pages.</p></td>
<td><p>You can add an Action Pane to a details form.</p></td>
<td><p>Action Panes improve access to actions that were previously available on the menu or toolbar of the form.</p></td>
<td><p><a href="https://technet.microsoft.com/library/gg844658(v=ax.60)">How to: Create an Action Pane</a></p></td>
</tr>
<tr class="odd">
<td><p>Specify that a form opens in read-only document view mode.</p></td>
<td><p>When you view a form that has editable controls, you could accidentally change a field value.</p></td>
<td><p>To quickly view data values, you use forms that are in read-only mode.</p></td>
<td><p>To reduce the risk of accidental changes, you can specify that a read-only version of the form is displayed.</p></td>
<td><p>Content is not yet available.</p></td>
</tr>
<tr class="even">
<td><p>Add enhanced previews for foreign key fields or controls.</p></td>
<td><p>When you rested the pointer on a record in a list, a tooltip appeared that showed one or two preview fields for that record.</p></td>
<td><p>When you rest the pointer on a record, the preview shows the data fields that are specified by a FactBox.</p></td>
<td><p>Because a FactBox is used, you can include more data fields in the preview.</p></td>
<td><p><a href="https://technet.microsoft.com/library/hh129455(v=ax.60)">Enhanced Preview</a></p></td>
</tr>
<tr class="odd">
<td><p>Specify how a form opens.</p></td>
<td><p>You used a form property to specify the mode for a form.</p></td>
<td><p>You use the <strong>OpenMode</strong> property of menu items and menu item buttons to specify how a form opens in the client.</p></td>
<td><p>You specify whether the form that opens is used to create a new record, update an existing record, or view an existing record in read-only mode.</p></td>
<td><p>Content is not yet available.</p></td>
</tr>
<tr class="even">
<td><p>Add FactBoxes to a form.</p></td>
<td><p>To supply additional information about the record that was selected in a list, you added a preview pane to the bottom of the list page.</p></td>
<td><p>You use FactBoxes and a preview pane to provide various additional information that is related to the record that is selected in a form.</p></td>
<td><p>You can add several FactBoxes that show various types of information. A FactBox uses a part object that defines the data that appears in the FactBox. You can create new parts, and then use these parts as FactBoxes or a preview pane.</p></td>
<td><p><a href="https://technet.microsoft.com/library/gg848021(v=ax.60)">How to: Add a Part to the FactBox Pane</a></p></td>
</tr>
<tr class="odd">
<td><p>Specify whether the query from the parent form is copied to a child form.</p></td>
<td><p>The feature was not available.</p></td>
<td><p>You can use the <strong>CopyCallerQuery</strong> property of menu items and menu item buttons to specify that the query of the parent form is used in the child form.</p></td>
<td><p>By copying the query from the parent form to a child form, you guarantee that the forms display a consistent set of data.</p></td>
<td><p><a href="https://technet.microsoft.com/library/aa845161(v=ax.60)">Form Control Properties</a></p></td>
</tr>
<tr class="even">
<td><p>Changes to form controls and methods are automatically stored in your customization layer.</p></td>
<td><p>Customizations were stored at the main type level or the concept level. Forms and tables are examples of main types.</p></td>
<td><p>Customizations to controls and methods are stored at the child level or the element level. An individual control in a form is an example of an element.</p></td>
<td><p>The additional granularity reduces the risk of conflicts with other customizations.</p></td>
<td><p>Content is not yet available.</p></td>
</tr>
</tbody>
</table>


### ![Gg848092.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Gg848092.collapse_all(en-us,AX.60).gif")Controls

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Use a <strong>DropDialogButton</strong> control.</p></td>
<td><p>The feature was not available.</p></td>
<td><p>You click a button to open a dialog box where you can complete an action.</p></td>
<td><p>You can complete actions without opening another form.</p></td>
<td><p><a href="https://technet.microsoft.com/library/hh812217(v=ax.60)">Dialog Forms Overview</a></p></td>
</tr>
<tr class="even">
<td><p>Add an Action Pane strip to a form.</p></td>
<td><p>The feature was not available.</p></td>
<td><p>You can add an Action Pane strip that provides access to the actions that are associated with the form.</p></td>
<td><p>You use an Action Pane strip when the form has insufficient actions for a full Action Pane. In addition, an Action Pane strip lets you put actions close to the records and data fields that they are related to.</p></td>
<td><p><a href="https://technet.microsoft.com/library/gg848145(v=ax.60)">Action Pane Strip Overview</a></p></td>
</tr>
<tr class="odd">
<td><p>Add FastTabs to a form.</p></td>
<td><p>Tabs were arranged horizontally across the top of the form.</p></td>
<td><p>A FastTab is a new vertical presentation style that replaces the existing tabs for forms.</p></td>
<td><p>FastTabs let you display large amounts of information in a single form.</p></td>
<td><p><a href="https://technet.microsoft.com/library/hh528501(v=ax.60)">How to: Add a FastTab to a Details Form</a></p></td>
</tr>
<tr class="even">
<td><p>Use the <strong>ReferenceGroup</strong> control.</p></td>
<td><p>The feature was not available.</p></td>
<td><p>You can automatically replace a surrogate foreign key with one or more data fields.</p></td>
<td><p>You use the <strong>ReferenceGroup</strong> control in forms and lookup forms that contain a surrogate key. The <strong>ReferenceGroup</strong> control provides data values that are understandable to the user.</p></td>
<td><p><a href="https://technet.microsoft.com/library/aa597861(v=ax.60)">Lookup Forms Overview</a></p></td>
</tr>
<tr class="odd">
<td><p>Use the segmented entry control.</p></td>
<td><p>The feature was not available.</p></td>
<td><p>You use the segmented entry control to enter an account number and associated dimensions.</p></td>
<td><p>The task of entering complex combinations of accounts and dimensions is simplified.</p></td>
<td><p><a href="https://technet.microsoft.com/library/hh300646(v=ax.60)">Segmented Entry</a></p></td>
</tr>
<tr class="even">
<td><p>Use the managed host control to add a .NET control to a form.</p></td>
<td><p>The feature was not available.</p></td>
<td><p>You can add and use .NET controls in forms.</p></td>
<td><p>You can add and use Windows Presentation Foundation (WPF) or managed form controls.</p></td>
<td><p><a href="https://technet.microsoft.com/library/gg861771(v=ax.60)">.NET Controls</a></p></td>
</tr>
<tr class="odd">
<td><p>Use the <strong>MSChart</strong> control.</p></td>
<td><p>To display data in a chart, you had to use the <strong>ChartFX</strong> ActiveX control.</p></td>
<td><p>To display data in a chart, you use the <strong>MSChart</strong> .NET control.</p></td>
<td><p><strong>MSChart</strong> replaces <strong>ChartFX</strong>, and provides new capabilities to create and save a chart.</p></td>
<td><p>Content is not yet available.</p></td>
</tr>
<tr class="even">
<td><p>Disable or hide controls that are not used in a specified country or region.</p></td>
<td><p>The feature was not available.</p></td>
<td><p>The form shows unique controls and navigation elements to users in a specified country or region. Users from other countries or regions cannot access these controls and navigation elements.</p></td>
<td><p>You can target controls and navigation elements to users in specific countries or regions. The targeted controls and navigation elements are automatically disabled or hidden when the form is viewed by users from other countries or regions.</p></td>
<td><p><a href="https://technet.microsoft.com/library/hh404126(v=ax.60)">Applying Country Specific Functionality</a></p></td>
</tr>
<tr class="odd">
<td><p>Set the <strong>Style</strong> property of a control.</p></td>
<td><p>The feature was not available.</p></td>
<td><p>Specify the type of control to create.</p></td>
<td><p>After you set the <strong>Style</strong> property, several control properties are automatically updated so that they use the values that are required for the specified control.</p></td>
<td><p><a href="https://technet.microsoft.com/library/aa845161(v=ax.60)">Form Control Properties</a></p></td>
</tr>
</tbody>
</table>


### ![Gg848092.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Gg848092.collapse_all(en-us,AX.60).gif")Data Sources

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Use date-effective data from a table.</p></td>
<td><p>There was no standard framework for displaying date-effective data.</p></td>
<td><p>You create forms that use from dates and to dates for data records.</p></td>
<td><p>Forms display the current data for fields that support date-effective data. You can reference a table that contains date-effective dates, and you can specify query and update behavior.</p></td>
<td><p><a href="https://technet.microsoft.com/library/jj129663(v=ax.60)">Date Effective Data Sources for Forms</a></p></td>
</tr>
<tr class="even">
<td><p>Use a modeled query via a menu item.</p></td>
<td><p>The feature was not available.</p></td>
<td><p>You use a menu item to specify the query that is used for a Cue or a secondary list page.</p></td>
<td><p>The development and maintenance of Cues and secondary list pages are simplified.</p></td>
<td><p><a href="https://technet.microsoft.com/library/cc606758(v=ax.60)">Walkthrough: Creating a Secondary List Page</a></p></td>
</tr>
<tr class="odd">
<td><p>Replace a surrogate foreign key with specified data fields.</p></td>
<td><p>Tables and lookup forms used replacement keys to identify a related record.</p></td>
<td><p>Tables and lookup forms use a surrogate key to identify a related record.</p></td>
<td><p>A form or lookup form that uses a surrogate key shows values that are understandable to the user, instead of the value of the surrogate foreign key.</p></td>
<td><p><a href="https://technet.microsoft.com/library/gg845085(v=ax.60)">Reference Data Sources for Forms</a></p></td>
</tr>
<tr class="even">
<td><p>Postpone the loading of replacement values for surrogate foreign keys.</p></td>
<td><p>The feature was not available.</p></td>
<td><p>The replacement fields are not loaded until they are visible.</p></td>
<td><p>Performance is improved, because joined data is not retrieved until it is required.</p></td>
<td><p><a href="https://technet.microsoft.com/library/gg845085(v=ax.60)">Reference Data Sources for Forms</a></p></td>
</tr>
<tr class="odd">
<td><p>Use a derived data source to access data from tables in an inheritance hierarchy for tables.</p></td>
<td><p>The feature was not available.</p></td>
<td><p>Controls can be bound to fields from the derived tables in an inheritance hierarchy.</p></td>
<td><p>The derived data source lets you use data from a table in an inheritance hierarchy.</p></td>
<td><p><a href="https://technet.microsoft.com/library/hh272120(v=ax.60)">Derived Data Sources for Forms</a></p></td>
</tr>
<tr class="even">
<td><p>Specify updates to several tables as a single unit of work.</p></td>
<td><p>When an update occurred, each table was updated in a separate trip to Microsoft Dynamics AX Application Object Server (AOS). In addition, each trip was a separate transaction.</p></td>
<td><p>When you save a record that changes multiple tables, the changes are combined into a single transaction that is initiated by AOS.</p></td>
<td><p>The single transaction provides a more efficient and consistent framework for completing data changes.</p></td>
<td><p><a href="https://technet.microsoft.com/library/jj129662(v=ax.60)">Change Group and Optional Record Modes</a></p></td>
</tr>
<tr class="odd">
<td><p>Specify how optional records in outer-joined tables are created or deleted.</p></td>
<td><p>Optional records were always created and saved.</p></td>
<td><p>The optional record is created only if you enter data for an outer-joined table.</p></td>
<td><p>You can specify the behavior of optional records. You can choose whether to always create, implicitly create, or explicitly create the optional record.</p></td>
<td><p>See the <strong>OptionalRecordMode</strong> property in <a href="https://technet.microsoft.com/library/aa676742(v=ax.60)">Form Data Source Properties</a>.</p></td>
</tr>
<tr class="even">
<td><p>Filter on the fields in all joined tables.</p></td>
<td><p>Filtering on outer-joined fields was disabled.</p></td>
<td><p>The <strong>Filter-by-Grid</strong>, <strong>Filter-by-Field</strong>, <strong>Filter-by-Value</strong>, <strong>Filter-by-Selection</strong>, and <strong>Advanced Filter</strong> dialog boxes support filtering on outer-joined fields.</p></td>
<td><p>You can sort and filter on the fields in all the joined tables.</p></td>
<td><p>Content is not yet available.</p></td>
</tr>
</tbody>
</table>


### ![Gg848092.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Gg848092.collapse_all(en-us,AX.60).gif")Parts

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Create or update a FactBox.</p></td>
<td><p>The feature was not available.</p></td>
<td><p>You can create or update a FactBox that appears on a list page or in a form.</p></td>
<td><p>Info parts let you specify the data that appears in a FactBox.</p></td>
<td><p><a href="https://technet.microsoft.com/library/gg844683(v=ax.60)">Parts</a></p></td>
</tr>
<tr class="even">
<td><p>Use an existing form as a FactBox.</p></td>
<td><p>The feature was not available.</p></td>
<td><p>You can use a form as a FactBox that provides additional information about the current record.</p></td>
<td><p>You have more options for customizing the types of controls that appear in the FactBox.</p></td>
<td><p><a href="https://technet.microsoft.com/library/gg864890(v=ax.60)">How to: Create a Form Part</a></p></td>
</tr>
<tr class="odd">
<td><p>Create a Cue in the Microsoft Dynamics AX Application Object Tree (AOT) that uses an existing query.</p></td>
<td><p>Cues used copies of the list page query and could break if the list page query was later changed.</p></td>
<td><p>You use the AOT to create a Cue that uses an existing query.</p></td>
<td><p>Changes to the list page query no longer affect the Cue.</p></td>
<td><p><a href="https://technet.microsoft.com/library/gg841851(v=ax.60)">How to: Create a Cue</a></p></td>
</tr>
<tr class="even">
<td><p>Create a Cue group that you can use as a FactBox.</p></td>
<td><p>The feature was not available.</p></td>
<td><p>A Cue group includes references to one or more Cues.</p></td>
<td><p>You use a Cue group as a FactBox that provides summary information that is related to the current record.</p></td>
<td><p><a href="https://technet.microsoft.com/library/gg840467(v=ax.60)">How to: Create a Cue Group</a></p></td>
</tr>
</tbody>
</table>


### ![Gg848092.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Gg848092.collapse_all(en-us,AX.60).gif")Search

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Make all forms and reports available from Search.</p></td>
<td><p>The feature was not available.</p></td>
<td><p>To make a form or report appear in search results, you create a menu item, and add the search terms to associate with the specified form or report.</p></td>
<td><p>You can use Search to find the forms and reports that are associated with a task.</p></td>
<td><p><a href="https://technet.microsoft.com/library/hh272118(v=ax.60)">Search</a></p></td>
</tr>
</tbody>
</table>


## See also

[Client](https://technet.microsoft.com/library/gg880996\(v=ax.60\))

[What's New in Microsoft Dynamics AX 2012 for Developers](https://technet.microsoft.com/library/gg845327\(v=ax.60\))

  
**Announcements:** New book: "Inside Microsoft Dynamics AX 2012 R3" now available. Get your copy at the [MS Press Store](https://www.microsoftpressstore.com/store/inside-microsoft-dynamics-ax-2012-r3-9780735685109).

