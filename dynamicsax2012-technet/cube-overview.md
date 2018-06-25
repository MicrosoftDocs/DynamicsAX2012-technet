---
title: Cube overview
TOCTitle: Cube overview
ms:assetid: 2cbca5c2-50bf-4aaa-b3ea-5b901ea0f6d6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dd252604(v=AX.60)
ms:contentKeyID: 28119326
ms.date: 12/19/2013
mtps_version: v=AX.60
---

# Cube overview [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A cube is a multidimensional structure that provides the basis for developing Business Intelligence (BI) applications. This article describes the components of a cube so that you can better understand how to use a cube to analyze data.

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><img src="images/Dd252604.TopicIcons_Conceptual(AX.60).png" title="Concepts" alt="Concepts" />
<p>Cube structure</p>
<p>Dimension and measure group relationships</p>
<p>KPIs and calculated members</p></td>
</tr>
</tbody>
</table>


## Cube structure

A cube consists of a set of measures and dimension attributes. For Microsoft Dynamics AX analysis cubes, measures and dimensions are defined in the Application Object Tree (AOT). A perspective is used to identify the tables and views that contain the measures and dimensions.

## Measures

A measure is a column in a table or view that contains quantifiable data, usually numeric, that can be aggregated. Measures correspond to something that users are interested in examining or analyzing; such as revenue, profit, or the total number of items sold. When you specify a measure, you must also specify an aggregate function that is used to aggregate the data. A cube has one or more measures.

Measures that you specify in Microsoft Dynamics AX are grouped into measure groups. For more information about measures and measure groups and how they are used in cubes, see [Measures and Measure Groups (SQL Server Books Online)](http://go.microsoft.com/fwlink/?linkid=208692). For information about how to define measures in Microsoft Dynamics AX, see [How to: Specify Measures for a Cube](how-to-specify-measures-for-a-cube.md).

You define measures at different levels and on different objects in the AOT using the Business Intelligence (BI) properties that appear in the **Properties** sheet. The following table describes the objects you can define measures and how they are used.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Object</p></th>
<th><p>Usage</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Extended data type</p></td>
<td><p>When you identify an extended data type as a measure, any field that references the extended data type will be a measure unless overridden on the table field.</p>
<p>An extended data type can extend another extended data type. If the base extended data type is a measure, you can either keep or override the settings from the base extended data type.</p></td>
</tr>
<tr class="even">
<td><p>Field</p></td>
<td><p>If the field is based on an extended data type that has already been identified as a measure, you can override the settings on the field.</p>
<p>There are two locations where you can identify a field as a measure.</p>
<ul>
<li><p>Directly on the table</p></li>
<li><p>On the table or view in the perspective that is used to define the cube</p></li>
</ul>
<p>Property settings that are supplied on the perspective override the settings from all other locations.</p></td>
</tr>
</tbody>
</table>


## Dimensions

You can set AOT properties on tables, views, and fields to create analysis services dimensions and *attributes*. Attributes are fields or columns in a table or view in the AOT. Dimensions are groups of attributes.

After you define dimension and attribute properties, you add the dimension tables and views to a perspective to create a cube. If you do not want to specify dimensions and attributes directly on a table or view, you can create a perspective, and then add the dimension information to the perspective. For more information, see [Create a perspective for a cube](create-a-perspective-for-a-cube.md).

For more information about how dimensions are used in cubes, see [Introduction to Dimensions (Analysis Services - Multidimensional Data) in SQL Server Books Online](http://go.microsoft.com/fwlink/?linkid=143293%26clcid=0x409).

## Dimension and measure group relationships

The relationships that are defined between dimensions and measure groups in a cube determine how the data in the cube is sliced. For Microsoft Dynamics AX cubes, relationships are generated based on the relationships that exist between the tables and views in the application. When you open a BI project in SQL Server Business Development Studio (BIDS), you can view the relationships that were generated when you click the **Dimension Usage** tab in Cube Designer. You can define additional relationships or modify existing relationships between dimensions and measure groups in Cube Designer. For more information, see [Dimension Relationships in SQL Server Books Online](http://go.microsoft.com/fwlink/?linkid=143289%26clcid=0x409).

## KPIs and calculated members

A Key Performance Indicator (KPI) is a collection of calculations used to measure business success. A calculated member is a member of a dimension or measure group that is defined based on a combination of cube data, arithmetic operators, numbers, and functions. KPIs are added using Cube Designer in BIDS after a project has been generated. The calculations that make up a KPI are a combination of Multidimensional Expressions (MDX) and calculated members that are added using Cube Designer. A KPI generally consists of the value achieved, a goal, a status value, and the trend.

