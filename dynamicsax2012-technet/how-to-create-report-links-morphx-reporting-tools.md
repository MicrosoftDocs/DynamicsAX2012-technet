---
title: 'How to: Create Report Links (MorphX Reporting Tools)'
TOCTitle: 'How to: Create Report Links'
ms:assetid: 89cf087d-e2c7-4318-a49b-8c8179ac09be
ms:mtpsurl: https://technet.microsoft.com/library/Bb314839(v=AX.60)
ms:contentKeyID: 35290303
author: tonyafehr
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Create Report Links (MorphX Reporting Tools) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When a report is displayed, some of the data fields can be secondary links. Secondary links are presented in orange and are underlined. You can right-click a secondary link, and then select from the context menu items that link to forms, other reports, or other kinds of Application Object Tree (AOT) objects. When a link is clicked, the value of the data field is sent to the form, which displays data related to that value.


> [!NOTE]
> <P>The <STRONG>MenuItemName</STRONG> and <STRONG>MenuItemType</STRONG> report control properties are ignored by Microsoft Dynamics AX. They cannot create report links. They should not be used.</P>



## Creating Links in Reports

You can use a relation on an extended data type or you can use a relation that is added to a table. Before you create links, create a form and a report. Both are based on the same table. The report field values do not have links.

### To create a form and a report

1.  Use the AOT to create a new table named **WidgetTable**. Add fields named **widgetId** and **widgetDescription** (use the string data type). For more information, see [How to: Create Tables](https://technet.microsoft.com/library/aa882181\(v=ax.60\)).

2.  Create a new form named **WidgetForm**. Set WidgetTable as its data source. Design the form to have one grid. The grid should have a column for both fields that are on the WidgetTable table (widgetId and widgetDescription).

3.  Use the **WidgetForm** form to populate the WidgetTable table with data. Add the following two rows of data for the **widgetId** and **widgetDescription** fields:
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>widgetId</p></th>
    <th><p>widgetDescription</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Wid1</p></td>
    <td><p>red</p></td>
    </tr>
    <tr class="even">
    <td><p>Wid2</p></td>
    <td><p>blue</p></td>
    </tr>
    </tbody>
    </table>
    

    > [!NOTE]
    > <P>Press CTRL+N to add a new blank row to the grid or press ALT+F9 to delete a grid row.</P>



4.  Create a new report named **WidgetReport**. Set the **WidgetTable** table as its data source. Run the report and then verify that it contains no links.
    

    > [!NOTE]
    > <P>To run the report, right-click the report in the AOT and then click <STRONG>Open</STRONG>.</P>



## Adding Links by Using an Extended Data Type

Using an extended data type is a good way to create report links while minimizing future maintenance work. A relation must be created on the extended data type. This approach can work when only one table is involved. For this approach, continue with the additional steps. In the following steps, you will link a report field to a form.

### To prepare to add links by using an extended data type

1.  Create a menu item of type display. Name the menu item **WidgetFormMenuitem**. Set its **ObjectType** property to Form, and then set its **Object** property to **WidgetForm** (from the drop-down list). For more information, see [How to: Create Menus and Menu Items](https://technet.microsoft.com/library/aa639737\(v=ax.60\)).

2.  In the AOT, expand the **Data Dictionary** node, expand the **Tables** node, and then click the **WidgetTable** node. Right-click **WidgetTable**, and then click **Properties**.

3.  On the **Properties** sheet, set the **FormRef** property of the **WidgetTable** table to **WidgetFormMenuitem**.

### To add the extended data type

1.  Create an extended data type named **widgetIdEdt**. For more information, see [How to: Create an Extended Data Type](https://technet.microsoft.com/library/aa633402\(v=ax.60\)).

2.  In the AOT, expand the **Data Dictionary** node, expand the **Extended Data Types** node, and then expand the new **widgetIdEdt** node. Right-click the **Relations** node, point to **New**, and then click **Normal**. The new relation node cannot be renamed.

3.  Click the new relation node. On the **Properties** sheet, set the **Table** property to **WidgetTable**, and the **RelatedField** property to **widgetId**.

4.  In the AOT, expand the **Data Dictionary** node, expand the **Tables** node, expand the **WidgetTable** node, and then click **widgetId**. On the **Properties** sheet, set the **ExtendedDataType** property of the **WidgetId** field to **widgetIdEdt**.

5.  Test the orange links on the **WidgetReport** report, under the **widgetId** column.

## Adding Links by Using a Table Relation

Another way to create report links is by defining a relation on a table. This approach involves two tables. Typically, the primary key column of one table is a foreign key column in another table. The relation is defined by the table that has the foreign key column.

To use this table relation approach instead of the extended data type approach, continue with these additional steps (instead of the extended data type steps). In the following steps, a report field links to another report.

### To create a form and a report to add links by using a table relation

1.  Use the AOT to create a table. Name the table **WidgetGroupTable**. Add fields named **widgetGroupId** and **widgetGroupDescription** (make the field types string). For more information, see [How to: Create Tables](https://technet.microsoft.com/library/aa882181\(v=ax.60\)).

2.  Create a new form named **WidgetGroupForm**. Set **WidgetGroupTable** as its data source. Design the form to have one grid. The grid should have a column for both fields that are on the **WidgetGroupTable** table (**widgetGroupId** and **widgetGroupDescription**).

3.  Use the **WidgetForm** form to populate the **WidgetTable** table with data. Add the following two rows of data for the **widgetId** and **widgetDescription** fields:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>widgetId</p></th>
<th><p>widgetDescription</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>wgid9</p></td>
<td><p>round</p></td>
</tr>
<tr class="even">
<td><p>wgid8</p></td>
<td><p>square</p></td>
</tr>
</tbody>
</table>



> [!NOTE]
> <P>Press CTRL+N to add a new blank row to the grid or press ALT+F9 to delete a grid row.</P>



1.  Create a new report named **WidgetGroupReport**. Set the **WidgetGroupTable** table as its data source.

### To prepare the tables to be joined

1.  Add a field named **widgetGroupId** to the **WidgetTable** table. This is considered to be a foreign key.

2.  Add a field named **widgetGroupId** to the **WidgetForm** form and the **WidgetReport** report.
    

    > [!NOTE]
    > <P>To add a field to the <STRONG>WidgetForm</STRONG> form, delete the <STRONG>WidgetTable</STRONG> data source from the <STRONG>WidgetForm</STRONG> form and create the <STRONG>WidgetTable</STRONG> data source again. If you re-create the <STRONG>WidgetTable</STRONG> data source, you must set the properties of the form design again.</P>



3.  Use the **WidgetForm** form to populate the new column with the value **wgid9** in each cell.

### To create a menu item to use to link the tables

1.  In the AOT, expand the **Menu Item** node, right-click **Output**, and then click **New Menu Item**.

2.  On the Properties sheet of the new menu item, set the **Name** property to **WidgetGroupReportMenuItem**, set the **ObjectType** property to **Report**, and then set the **Object** property to **WidgetGroupReport**.

3.  In the AOT, expand the **Data Dictionary** node, expand the **Tables** node, and then click **WidgetGroupTable**. Right-click **WidgetGroupTable**, and then click **Properties**.

4.  On the **Properties** sheet of the **WidgetGroupTable**, set the **ReportRef** property to **WidgetGroupReportMenuItem**.

### To add the table relation

1.  In the AOT, expand the **Data Dictionary** node, expand the **Tables** node, and then expand the **WidgetTable** node. Right-click the **Relations** node, and then click **New Relation**. Rename the new relation node **WidgetGroupRel**.

2.  On the **Properties** sheet of the **WidgetGroupRel** relation, set the **Table** property to **WidgetGroupTable**.

3.  Right-click the **WidgetGroupRel** node, click **New**, and then click **Normal**. The new column matching node cannot be renamed.

4.  On the **Properties** sheet of the new node, set the **Field** property to **widgetGroupId** (this refers to the foreign key column in the WidgetTable table). Set the **RelatedField** property to **widgetGroupId** (the primary key column in the **WidgetGroupTable** table).

5.  Click the **Save All** icon in the AOT.
    

    > [!NOTE]
    > <P>Confirm that the <STRONG>RelatedField</STRONG> property is set to <STRONG>widgetGroupId</STRONG>. If it is not, set it again.</P>



### To test the report links

1.  In the AOT, expand the **Reports** node, right-click **WidgetReport**, and then click **Open**.

2.  Right-click any underlined orange link, and then click a form or report name shown in the menu, which opens that form or report. The form or report should be populated only with data that is associated with the specific value of the link that you clicked.

## Toggling the Display of Report Links

When a report that has links is viewed, the orange highlighted links can be toggled on and off.

### To toggle the display of report links

  - From the **Command** menu, click **Show Link**.

