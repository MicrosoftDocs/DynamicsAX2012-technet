---
title: 'How to: Add or Delete a Field Group in a Data Region'
TOCTitle: 'How to: Add or Delete a Field Group in a Data Region'
ms:assetid: 0ea1fbf2-83be-47a3-9733-0ffb2c7768d6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Ee873245(v=AX.60)
ms:contentKeyID: 28119308
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Add or Delete a Field Group in a Data Region 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you bind a report to a query that was defined in the AOT, the report framework provides support for field groups. Field groups are objects that group together fields that logically belong together. When a change is made to a field group, the change is reflected in all cases where the field group is used. This means that the change is reflected in the report. For more information on field groups created in Microsoft Dynamics AX, see [Defining Field Groups](https://technet.microsoft.com/en-us/library/bb314861\(v=ax.60\)).

When you bind a dataset to a query, you can select one or more field groups that exist on the table referenced in the query. The following procedure explains how to add or delete a field group data region within an auto design.

### To bind a dataset to a query

1.  In Model Editor, expand the node for the report to which you want to add a field group.

2.  Right-click the **Datasets** node, and then click **Add Dataset**.

3.  Select the node for the dataset.

4.  In the **Properties** window, specify the following values.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Property</p></th>
    <th><p>Value</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Data Source</strong></p></td>
    <td><p><strong>Dynamics AX</strong> - The data source for the dataset must be set to <strong>Dynamics AX</strong> if you want to set the data source type to an AX Query.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Data Source Type</strong></p></td>
    <td><p><strong>Query</strong> indicates you will bind the dataset to an AX Query.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Default Layout</strong></p></td>
    <td><p>The default data region type for the dataset. <strong>Table</strong>, <strong>TopDownList</strong>, and <strong>HorizontalList</strong> layouts will support adding field groups. For more information about data region types, see <a href="report-data-region-overview.md">Report Data Region Overview</a>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Dynamic Filters</strong></p></td>
    <td><p>Set the <strong>Dynamic Filters</strong> property to True to create dynamic filters on your report. When this value is True, a dataset parameter and report parameter will be created. Both of which will have the same name. When the value is False, the dataset parameter and report parameter for the default ranges are created. For more information about creating dynamic filters, see <a href="adding-interactive-features-to-reports.md">Adding Interactive Features to Reports</a>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Name</strong></p></td>
    <td><p>Provide a name for the dataset.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Query</strong></p></td>
    <td><p>Click the ellipsis button (…). A dialog box displays with the queries that are defined in the AOT. Select a query and then click <strong>Next</strong>. Expand the field nodes and select fields, field groups, and display methods that you want to use on the report.</p>
    <div class="alert">

    > [!NOTE]
    > <P>The field groups you select in this step will be the field groups you can add to the report design.</P>


    </div>
    <p>Click <strong>OK</strong>.</p></td>
    </tr>
    </tbody>
    </table>


5.  Drag the dataset onto the **Designs** node. An auto design named **AutoDesign1** is created for the report.

### To add a field group to a data region within an auto design

1.  In Model Editor, expand the node for the data region to which you want to add a field group.

2.  The following table describes the next step to navigate to each of the data region elements to which you can add a field group.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Data region element</p></th>
    <th><p>How to navigate</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Table data</p></td>
    <td><p>Right-click the <strong>Data</strong> node for the data region. </p></td>
    </tr>
    <tr class="even">
    <td><p>Table grouping header</p></td>
    <td><p>Expand the <strong>Groupings</strong> node, expand the <strong>SubsegmentId</strong> &gt; <strong>Header</strong> node, right-click the <strong>Row</strong> node.</p></td>
    </tr>
    <tr class="odd">
    <td><p>Table grouping footer</p></td>
    <td><p>Expand the <strong>Groupings</strong> node, expand the <strong>SubsegmentId</strong> &gt; <strong>Footer</strong> node, right-click the <strong>Row</strong> node.</p></td>
    </tr>
    <tr class="even">
    <td><p>List data</p></td>
    <td><p>Right-click the <strong>Data</strong> node for the data region.</p></td>
    </tr>
    <tr class="odd">
    <td><p>List grouping header</p></td>
    <td><p>Expand the <strong>Groupings</strong> node, expand the <strong>SubsegmentId</strong> node, right-click the <strong>Header</strong> node.</p></td>
    </tr>
    <tr class="even">
    <td><p>List grouping footer</p></td>
    <td><p>Expand the <strong>Groupings</strong> node, expand the <strong>SubsegmentId</strong> node, right-click the <strong>Footer</strong> node.</p></td>
    </tr>
    </tbody>
    </table>


3.  Point to **Add**, and then click **Field Group**.

4.  In the **Properties** window, specify the following properties.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Property</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>DataSetFieldGroupBase</strong></p></td>
    <td><p>Select the field group to add to the data region. The drop-down contains a list of the field groups that you selected when you bound the dataset to the query.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>AutoFieldGroupOrder</strong></p></td>
    <td><p>Indicates the save status of the fields. Select the drop-down list to display the following options.</p>
    <ul>
    <li><p><strong>Do not save the field properties</strong> - Use this option when all the properties of the sub-fields should be read-only. In model editor, expand the field group and select one of the fields. The visibility, text align, and caption will be used from the base field. The default styles and format will be used. Fields cannot be re-ordered.</p></li>
    <li><p><strong>Save the field properties</strong> - Use this option when the properties of the sub-fields should be editable. You can change the properties for each field. The overridden properties are then used when the report displays. Fields cannot be re-ordered.</p></li>
    <li><p><strong>Save the field properties and order</strong> – Use this option when the properties of the sub-fields should be editable and the fields can be re-ordered.</p></li>
    </ul></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Caption</strong></p></td>
    <td><p>Enter a Label ID to be used for the field group.</p></td>
    </tr>
    </tbody>
    </table>


### To delete a field group for a data region within an auto design

1.  In Model Editor, expand the node for the data region that contains the field group you want to delete.

2.  Expand the **Data** node.

3.  Right-click the field group you want to delete, and then click **Delete**.
    
    When you delete a field group in a data region, it is deleted from the selected data region only.

## See also

[Defining Field Groups](https://technet.microsoft.com/en-us/library/bb314861\(v=ax.60\))

[How to: Create a Field Group](https://technet.microsoft.com/en-us/library/aa611907\(v=ax.60\))

[Working with Data Regions](working-with-data-regions.md)

