---
title: 'How to: Use an Enum as a Report Parameter'
TOCTitle: 'How to: Use an Enum as a Report Parameter'
ms:assetid: 8dce6344-12ac-4c81-91b7-69fd1e7beb65
ms:mtpsurl: https://technet.microsoft.com/library/Ee873271(v=AX.60)
ms:contentKeyID: 28119397
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Use an Enum as a Report Parameter 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic provides the steps to use an Enum type as a report parameter. The collection of enumeration values can then be referenced by the report. For example, from the Facility Management sample for Microsoft Dynamics AX, the room type is stored as an enumeration type. You can add a dataset that binds to the RoomType enumeration and restrict the report to display a specific room type, such as **Cubicle**. You will create the dataset as an **AX Enum Provider** data source type so that the enum parameter can be accessed from Enterprise Portal in addition to the Microsoft Dynamics AX client.

## Creating an Enum Type Parameter

To create a parameter of type Enum, you must have the following:

  - A data source that contains a field of type Enum. From the Facility Management sample, the data source is the **FCMRooms** table that contains the **RoomType** enumeration.

  - An Microsoft Dynamics AX query based on the data source. From the Facility Management sample, the query is **FCMRoomsReport**. The data source for this query has a range set for **RoomType**.
    

    > [!NOTE]
    > <P>You can set a range on the query or create a filter in Model Editor to provide the filter logic for the enumeration parameter.</P>



The following screenshot illustrates the Facility Management sample **FCMRoomsReport** query, **RoomType** range, and **FCMRooms** data source.

![Query, data source, and range for enum parameter.](images/Ee873271.ReportEnumParameter_RoomType(AX.60).jpg "Query, data source, and range for enum parameter.")

This section describes how to create an enumeration parameter on a report. You will add a dataset bound to a query that contains a range based on an enumeration field. You will add a second dataset that is bound to the enumeration field to convert the parameter to a friendly drop-down list. Then you will reference the second dataset from the report parameter that was generated from the query range. The following screenshot illustrates these elements in the Facility Management model of the FCMRooms report project.

![Facility Manager with RoomType enum example](images/Ee873271.RoomTypeAll(AX.60).png "Facility Manager with RoomType enum example")

The following numbered list describes the screenshot elements of the **FCMRooms** report in the Facility Management sample.

1.  The dataset that is bound to the **FCMRoomsReport** query that has a range set for the **RoomType** field. **RoomType** is an Enum type.

2.  The dataset parameter generated from the range that was set for the **RoomType** field in the query.

3.  The dataset bound to the **RoomType** enumeration that is used to create a friendly drop-down report parameter on the report.

4.  The name of the enumeration to bind to the AX Enum Provider dataset. Set the **Query** property to the **EnumType** property of the enumeration field on the table. To find the **EnumType** property in the Facility Management sample, the navigation path is **Application Explorer** \> **Data Dictionary** \> **Tables** \> **FCMRooms** \> **Fields** \> **RoomType** \> in the Properties window, **Type** is set to **Enum**.

5.  The report parameter generated from the range set on the query to which the dataset is bound. The **RoomTypeEnum** dataset is referenced from the **Values** property set on this report parameter.

### To create a dataset bound to a query with a range of type Enum

1.  In Model Editor, right-click the **Dataset** node, and then click **Add Dataset**.

2.  Select the new dataset and in the Properties window, set the following:
    
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
    <td><p>Dynamic Filters</p></td>
    <td><p>False</p>
    <p>Setting the <strong>Dynamic Filters</strong> property to <strong>False</strong> and because there is a range set on the query to which the dataset is bound will cause a dataset parameter named <strong>RoomType</strong> and a report parameter named <strong>FCMRooms_RoomType</strong> to be generated.</p></td>
    </tr>
    <tr class="even">
    <td><p>Data Source Type</p></td>
    <td><p>Query</p></td>
    </tr>
    <tr class="odd">
    <td><p>Query</p></td>
    <td><ol>
    <li><p>Click the ellipsis button (...) to open the <strong>Select a Microsoft Dynamics AX Query</strong> dialog box. You can select a query that is defined in the AOT and identify the fields that you want to use.</p></li>
    <li><p>Select the <strong>FCMRoomsReport</strong> query, and then click <strong>Next</strong>.</p></li>
    <li><p>Select the <strong>All Fields</strong> check box.</p></li>
    <li><p>Expand the <strong>FCMRooms_1_FCMPrivateRooms</strong> node and then select the <strong>All Fields</strong> check box.</p></li>
    <li><p>Expand the <strong>FCMRooms_1_FCMPublicRooms</strong> node and then select the <strong>All Fields</strong> check box.</p></li>
    <li><p>Click <strong>OK</strong>.</p></li>
    </ol></td>
    </tr>
    </tbody>
    </table>


The user needs to select the **EnumType** field for which the enumeration values will be retrieved. This enumeration will be the same enumeration field that is being used for the query on the dataset. In the following section, **FCMRoomType** is the enumeration field for which the enumeration values will be retrieved. The **FCMRoomType** enumeration field was used in the query to restrict which records are retrieved.

### To create a dataset bound to an AX Enum Provider

1.  In Model Editor, right-click the **Dataset** node, and then click **Add Dataset**.

2.  Select the new dataset and in the Properties window, set the following:
    
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
    <td><p>Data Source Type</p></td>
    <td><p>AX Enum Provider</p></td>
    </tr>
    <tr class="even">
    <td><p>Query</p></td>
    <td><p>To find the value, in the Application Explorer, click <strong>Data Dictionary</strong> &gt; <strong>Tables</strong> &gt; the table that contains the enumeration field &gt; <strong>Fields</strong> &gt; the field name that is an Enum type. In the Properties window, the <strong>EnumType</strong> property is set to the value that you must set in the <strong>Query</strong> field of the dataset. The drop-down list contains the Microsoft Dynamics AX base and system enums.</p></td>
    </tr>
    </tbody>
    </table>
    
    The dataset you created now contains three fields that contain metadata for the dataset. In Model Editor, expand the **RoomTypeEnum** dataset, expand the **Fields** node, and note the following fields were added: **Name**, **Value**, and **Label**.

### To bind the report parameter to the AX Enum Provider dataset

1.  Expand the **Parameters** node for the report and select the **FCMRooms\_RoomType** report parameter that will be bound to the AX Enum Provider dataset. The naming convention is Dataset\_EnumFieldName.

2.  In the Properties window, in the **Values** property, click the ellipsis button (...) to open the **Select Values** dialog window. Set the following:
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Value</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Dataset:</p></td>
    <td><p>RoomTypeEnum which is the dataset created to retrieve values from the enumeration field.</p></td>
    </tr>
    <tr class="even">
    <td><p>Value field:</p></td>
    <td><p>Value</p></td>
    </tr>
    <tr class="odd">
    <td><p>Label field:</p></td>
    <td><p>Label</p></td>
    </tr>
    </tbody>
    </table>


You can use the additional properties to control the look of the report parameters, such as whether the parameter is visible or has a default value. Now your report with a report parameter based on an enumeration can be accessed from a Microsoft Dynamics AX [menu item](how-to-create-a-menu-item-for-a-report.md) or [Enterprise Portal](https://technet.microsoft.com/library/cc571238\(v=ax.60\)).

For the complete steps to use an AX Enum Provider data source type, see [Walkthrough: Using AX Enum Provider in a Column Chart Report](walkthrough-using-ax-enum-provider-in-a-column-chart-report.md).

## See also

[Enums](https://technet.microsoft.com/library/aa881702\(v=ax.60\))

