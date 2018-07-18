---
title: Business Intelligence Properties
TOCTitle: Business Intelligence Properties
ms:assetid: 08629d9b-f7c0-4091-8a8a-b5dd23fb1349
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Cc519277(v=AX.60)
ms:contentKeyID: 28119301
ms.date: 07/25/2014
mtps_version: v=AX.60
---

# Business Intelligence Properties 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic provides a description of the Business Intelligence (BI) properties in Microsoft Dynamics AX that are used to define cubes that can be deployed to a SQL Server Analysis Services database. Property descriptions are divided into the following categories.

Table Properties

Table Field Properties

Extended Data Type Properties

Enumeration Properties

Perspective Properties

Perspective Table Properties

## Table Properties

The following properties are in the **Properties** sheet when a table is selected in the Application Object Tree (AOT).

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
<td><p><strong>IsLookup</strong></p></td>
<td><p>Determines whether to generate a consolidated dimension or a distinct dimension. You can specify one of the following values.</p>
<ul>
<li><p><strong>Yes</strong> - Indicates that attributes from the table are to be consolidated into the parent dimension (star schema).</p></li>
<li><p><strong>No</strong> - Indicates that a separate dimension is to be generated for the table (snowflake schema).</p></li>
</ul>
  
> [!NOTE]
> <P>If a perspective contains a table that has a surrogate foreign key and the <STRONG>IsLookup</STRONG> property is set to <STRONG>Yes</STRONG>, the dimension usage between the measure group and dimension will not get generated in the perspective. Instead, use a view to retain the relationship.</P>


<p>For more information about dimensions and star and snowflake schemas, see <a href="http://go.microsoft.com/fwlink/?linkid=115450">Introduction to Dimensions (SQL Server Books Online)</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>AnalysisIdentifier</strong></p></td>
<td><p>Specifies the table field that is referenced as the dimension instance identifier. The AnalysisIdentifier property sets the NameColumn property on the key attribute of the dimension. The Name property determines the value that is displayed by the key attribute.</p>
<p>The key attribute is inferred from the indexes of the table where AllowDuplicates is false and all the fields in the index are in the view or table of the perspective.</p></td>
</tr>
<tr class="odd">
<td><p><strong>AnalysisDimensionType</strong></p></td>
<td><p>Determines the type of dimension created based on the <strong>IsLookup</strong> property setting. You can specify one of the following values.</p>
<p><strong>IsLookup</strong> property set to <strong>Yes</strong></p>
<ul>
<li><p><strong>Auto</strong> - Specifies that the table may contain factual as well as dimensional data. The BI Wizard will extract dimensional data and create dimensions and attributes while factual data will be extracted to create measures. One child dimension is created with attributes from the parent table.</p></li>
<li><p><strong>MasterInner</strong> - Specifies an inner (full) join to create relationships with this table to the child table. Each record combination for this table and the child table are generated in the dimension.One child dimension is created with attributes from the parent table.</p></li>
<li><p><strong>MasterLeftOuter</strong> - Specifies a left outer join to create relationships with this table to the child table. Dimensions will have additional attributes based on values in this table that can also be empty. One child dimension is created with attributes from the parent table.</p></li>
<li><p><strong>Transaction</strong> - Specifies that the table should strictly be used to generate factual data (measures). This setting should be used when a table only contains transactional data. One child dimension is created containing only enumeration fields from the table.</p></li>
</ul>
<p><strong>IsLookup</strong> property set to <strong>No</strong></p>
<ul>
<li><p><strong>Auto</strong> - Specifies that the table may contain factual as well as dimensional data. The BI Wizard will extract dimensional data and create dimensions and attributes while factual data will be extracted to create measures. One parent and child dimension is created.</p></li>
<li><p><strong>MasterInner</strong> - Not applicable. Same as <strong>Auto</strong>.</p></li>
<li><p><strong>MasterLeftOuter</strong> - Not applicable. Same as <strong>Auto</strong>.</p></li>
<li><p><strong>Transaction</strong> - Specifies that the table should strictly be used to generate factual data (measures). This setting should be used when a table only contains transactional data. One child dimension is created containing only enumeration values from the table.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>AnalysisDimensionLabel</strong></p></td>
<td><p>Names the dimension that is generated. If this property is not specified, the label of the table or view is used to name the generated dimension.</p></td>
</tr>
<tr class="odd">
<td><p><strong>AnalysisKeyAttributeLabel</strong></p></td>
<td><p>Names the key of the dimension that is generated. If this property is not specified, the label of the dimension is used to name the key attribute.</p></td>
</tr>
<tr class="even">
<td><p><strong>AnalysisMeasureGroupLabel</strong></p></td>
<td><p>Names the measure group that is generated. If this property is not specified, the label of the table or view is used to name the generated measure group.</p></td>
</tr>
<tr class="odd">
<td><p><strong>TitleField1</strong></p></td>
<td><p>The key field for the records in the table to use as the fallback of the ID of the dimension. If you do not set this property, fields set as measures will not be included in the cube and the table will not be included in the data source view and after the cube is generated.</p></td>
</tr>
</tbody>
</table>


## Table Field Properties

The following properties display in the **Properties** sheet when a field from table is selected in the AOT.

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
<td><p><strong>AnalysisLabel</strong></p></td>
<td><p>Specifies the label for the field when it is used as a dimension attribute or measure. Only specify a label for this property when the label supplied for the <strong>Label</strong> property is not appropriate.</p></td>
</tr>
<tr class="even">
<td><p><strong>AnalysisUsage</strong></p></td>
<td><p>Identifies the role of the field in the cube. You can specify one of the following values.</p>
<ul>
<li><p><strong>Attribute</strong> - The field is a dimension attribute.</p></li>
<li><p><strong>Measure</strong> - The field is a measure.</p></li>
<li><p><strong>Both</strong> - The field is both a dimension attribute and a measure.</p></li>
<li><p><strong>None</strong> - The field is not a dimension attribute and not a measure.</p></li>
<li><p><strong>Auto</strong> - The value of the <strong>AnalysisUsage</strong> property for the extended data type or enumeration that the field is based on is to be used.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>AnalysisDefaultTotal</strong></p></td>
<td><p>Determines the aggregate function for a measure. Use this property when <strong>AnalysisUsage</strong> is set to <strong>Measure</strong>. You can specify one of the following values.</p>
<ul>
<li><p><strong>Sum</strong> - Returns the sum of all the values in a set.</p></li>
<li><p><strong>Count</strong> - Returns the number of non-null items in a set.</p></li>
<li><p><strong>CountDistinct</strong> - Returns the number of distinct non-null items in a set.</p></li>
<li><p><strong>Min</strong> - Returns the minimum value in a set.</p></li>
<li><p><strong>Max</strong> - Returns the maximum value in a set.</p></li>
<li><p><strong>None</strong> - No aggregate function is applied.</p></li>
<li><p><strong>Auto</strong> - Applies to derived extended data types. The value of the <strong>AnalysisUsage</strong> property for the parent extended data type is to be used.</p></li>
</ul>
  
> [!NOTE]
> <P>Count and DistinctCount are the only aggregate function settings allowed on String fields by Analysis Services. If you set the <STRONG>AnalysisDefaultTotal</STRONG> value to an unsupported value, the cube will not build.</P>

</td>
</tr>
<tr class="even">
<td><p><strong>ExchangeRateDateField</strong></p></td>
<td><p>The date to use to calculate the value in the consolidation currency. This optional property is used only with MST fields.</p></td>
</tr>
</tbody>
</table>


## Extended Data Type Properties

The following properties are in the **Properties** sheet when an extended data type is selected in the AOT.

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
<td><p><strong>AnalysisUsage</strong></p></td>
<td><p>Identifies the role of the extended data type in the cube. This setting is propagated to all table fields that reference the extended data type. However, the setting can be overridden on the table field. Specify one of the following values.</p>
<ul>
<li><p><strong>Attribute</strong> - A field that references the extended data type is a dimension attribute.</p></li>
<li><p><strong>Measure</strong> - A field that references the extended data type is a measure.</p></li>
<li><p><strong>Both</strong> - A field that references the extended data type is both a dimension attribute and a measure.</p></li>
<li><p><strong>None</strong> - A field that references the extended data type is not a dimension attribute and not a measure.</p></li>
<li><p><strong>Auto</strong> - Applies to derived extended data types. The value of the <strong>AnalysisUsage</strong> property for the parent extended data type is used.</p>
  
> [!NOTE]
> <P>Extended data types that are based on enumerations cannot be measures.</P>

</li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>AnalysisDefaultTotal</strong></p></td>
<td><p>Determines the aggregate function for a measure. Use this property when <strong>AnalysisUsage</strong> is set to <strong>Measure</strong>. You can specify one of the following values.</p>
<ul>
<li><p><strong>Sum</strong> - Returns the sum of all the values in a set.</p></li>
<li><p><strong>Count</strong> - Returns the number of non-null items in a set.</p></li>
<li><p><strong>CountDistinct</strong> - Returns the number of distinct non-null items in a set.</p></li>
<li><p><strong>Min</strong> - Returns the minimum value in a set.</p></li>
<li><p><strong>Max</strong> - Returns the maximum value in a set.</p></li>
<li><p><strong>None</strong> - No aggregate function is applied.</p></li>
<li><p><strong>Auto</strong> - Applies to derived extended data types. The value of the <strong>AnalysisUsage</strong> property for the parent extended data type is used.</p></li>
</ul>
<p>The aggregate function can be overridden at the field level. That is, you can change the aggregate function for the field using the <strong>AnalysisDefaultTotal</strong> property for the field.</p></td>
</tr>
</tbody>
</table>


## Enumeration Properties

The following BI properties display in the **Properties** sheet when an enumeration is selected in the AOT.

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
<td><p><strong>AnalysisUsage</strong></p></td>
<td><p>Identifies the role of the enumeration in a cube. This setting is propagated to all table fields that reference the enumeration. However, the setting can be overridden on the table field. Specify one of the following values.</p>
<ul>
<li><p><strong>Attribute</strong> - A field that references the enumeration is a dimension attribute.</p></li>
<li><p><strong>None</strong> - A field that references the enumeration is not a dimension attribute.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Perspectives Properties

The following BI properties display in the **Properties** sheet when a perspective is selected in the AOT.

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
<td><p><strong>Usage</strong></p></td>
<td><p>Specifies the materialization options for a Microsoft Dynamics AX perspective. You can specify one of the following values.</p>
<ul>
<li><p><strong>AdHocReporting</strong> - The perspective will be used to generate a transactional Semantic Model Definition Language (SMDL) model.</p></li>
<li><p><strong>OLAP</strong> - The perspective will be used to generate a cube in a SQL Server Analysis Services (SSAS) Business Intelligence project.</p></li>
<li><p><strong>Both</strong> - The perspective will be to generate both a transactional SDML model and a cube in a SSAS Business Intelligence project.</p></li>
<li><p><strong>None</strong> - The perspective will not be materialized.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>SharedDimensionContainer</strong></p></td>
<td><p>Determines whether to share items in the perspective. When true, the items in the perspective are added to all other perspectives that are in the project and no cube is created for the perspective.</p></td>
</tr>
</tbody>
</table>


## Perspective Table Properties

The perspective table properties are the same as the BI table properties. The BI property settings in the **Perspectives** node override BI property settings on the table itself. Use table property settings in the **Perspectives** node when you do not want to set properties on the table itself, for example, when a table will be used in multiple perspectives.

## Perspective View Properties

The view properties are the same as the table properties, except for the **IsLookup** property. The **IsLookup** property is not supported on views in perspectives.

## See also

[How to: Specify Measures for a Cube](how-to-specify-measures-for-a-cube.md)

[How to: Specify Dimensions and Attributes for a Cube](how-to-specify-dimensions-and-attributes-for-a-cube.md)

[Create a perspective for a cube](create-a-perspective-for-a-cube.md)

[Walkthrough: Creating a cube](walkthrough-creating-a-cube.md)

[Properties of AOT Elements](https://technet.microsoft.com/en-us/library/gg731856\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

