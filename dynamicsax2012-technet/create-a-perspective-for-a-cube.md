---
title: Create a perspective for a cube
TOCTitle: Create a perspective for a cube
ms:assetid: b3207987-3f46-4000-8b86-b2c8d9f433f5
ms:mtpsurl: https://technet.microsoft.com/library/Cc617589(v=AX.60)
ms:contentKeyID: 28119569
author: Khairunj
ms.date: 12/19/2013
mtps_version: v=AX.60
---

# Create a perspective for a cube 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A perspective is a collection of tables and views that is used to identify the tables and views that contain measures and dimension attributes for a cube. After you create a perspective, you can use it to generate an Analysis Services cube. The following procedure explains how to create a perspective for a cube and how to add or remove table and view fields to a perspective.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><img src="images/Cc617589.TopicIcons_Task(AX.60).png" title="Tasks" alt="Tasks" />
<p>Prerequisites</p>
<p>Create a perspective for a cube</p>
<p>Add or remove table fields in a perspective</p>
<p>Add or remove view fields in a perspective</p></td>
<td><img src="images/Cc617589.TopicIcons_Resources(AX.60).png" title="Resources" alt="Resources" />
<p><a href="http://www.youtube.com/watch?v=latzrx75_94">How to create a cube in Microsoft Dynamics AX 2012 (video)</a></p></td>
</tr>
</tbody>
</table>


## Prerequisites

Before you can complete the procedures in this topic, you must make sure that the following prerequisites are in place.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
<th><p>For more information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Required software</p></td>
<td><p>Microsoft Dynamics AX with Analysis Services configured</p></td>
<td><p><a href="analytics-in-microsoft-dynamics-ax.md">Analytics in Microsoft Dynamics AX</a></p></td>
</tr>
</tbody>
</table>


## Create a perspective for a cube

1.  In the AOT, expand the **Data Dictionary** node.

2.  Right-click the **Perspectives** node, and then click **New Perspective**.

3.  Select the node for the perspective.

4.  In the **Properties** window, type a name for the **Name** property, specify a label to use in the **Label** property, and select either **OLAP** or **Both** for the **Usage** property. Set other properties as appropriate.
    

    > [!NOTE]
    > <P>If you do not specify a label for the perspective, the cube name will not be available in the business overview web part in Enterprise Portal.</P>



5.  Add tables that are used to define the cube to the perspective by dragging them from the **Tables** node in the AOT onto the **Tables** node that is in the perspective. Be sure to add the tables that already contain, or will contain, measures and dimensions for the cube.
    

    > [!NOTE]
    > <P>If you set the <STRONG>createdDateTime</STRONG> property in any of the tables that you add to a perspective to <STRONG>No</STRONG>, cube processing may fail. If that happens, run the SQL Server Analysis Services project wizard using the update option. Deploy and process the Analysis Services project to make sure the project is generated. If necessary, open the Data Source View (DSV) in Microsoft Business Intelligence Development Studio (BIDS) and remove columns that are referenced in the error when the cube processing failed.</P>

    

    > [!NOTE]
    > <P>Sub-type tables (non-base tables) are not supported in perspectives in Microsoft Dynamics AX 2012 R2. Do not add a table that has a non-empty value for its <STRONG>Extends</STRONG> property to a perspective. If you want to use fields from a sub-type table, create a view that contains the field and then add the view to the perspective.</P>

    
    You can define measures and dimension attributes at different levels and on different objects in the Application Object Tree (AOT). For more information, see [How to: Specify Measures for a Cube](how-to-specify-measures-for-a-cube.md) and [How to: Specify Dimensions and Attributes for a Cube](how-to-specify-dimensions-and-attributes-for-a-cube.md).

6.  Add views that are used to define the cube to the perspective by dragging them from the **Views** node in the AOT onto the **Views** node that is in the perspective. Be sure to add the views that already contain, or will contain, measures and dimensions for the cube.

## Add or remove table fields in a perspective

1.  In the AOT, expand the node for the perspective, expand the **Tables** node, expand the node for the table, and then select the **Fields** node.

2.  In the **Properties** window, set the **Dynamic** property to **No**.

3.  Do one of the following:
    
      - To add a field, right-click the **Fields** node and then click **New Field**. In the **Properties** window, select a field for the **DataField** property. To identify the field as a measure or a dimension attribute, see [How to: Specify Measures for a Cube](how-to-specify-measures-for-a-cube.md) and [How to: Specify Dimensions and Attributes for a Cube](how-to-specify-dimensions-and-attributes-for-a-cube.md).
    
      - To delete a field, expand the **Fields** node, right-click the field and then click **Delete**.

## Add or remove view fields in a perspective

1.  In the AOT, expand the node for the perspective, expand the **Views** node, expand the node for the view, and then select the **Fields** node.

2.  In the **Properties** window, set the **Dynamic** property to **No**.

3.  Do one of the following:
    
      - To add a field, right-click the **Fields** node and then click **New Field**. In the **Properties** window, select a field for the **DataField** property. To identify the field as a measure or a dimension attribute, see [How to: Specify Measures for a Cube](how-to-specify-measures-for-a-cube.md) and [How to: Specify Dimensions and Attributes for a Cube](how-to-specify-dimensions-and-attributes-for-a-cube.md).
    
      - To delete a field, expand the **Fields** node, right-click the field. and then click **Delete**.

## See also

[Create a New SQL Server Analysis Services Project](create-a-new-sql-server-analysis-services-project.md)

[How to: Specify Measures for a Cube](how-to-specify-measures-for-a-cube.md)

[How to: Specify Dimensions and Attributes for a Cube](how-to-specify-dimensions-and-attributes-for-a-cube.md)

[Business Intelligence Properties](business-intelligence-properties.md)

[Introduction to Cubes (SQL Server Books Online)](http://go.microsoft.com/fwlink/?linkid=115081)

