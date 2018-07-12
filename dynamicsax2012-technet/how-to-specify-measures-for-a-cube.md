---
title: 'How to: Specify Measures for a Cube'
TOCTitle: 'How to: Specify Measures for a Cube'
ms:assetid: 79d164a0-5115-4c62-93f4-d1145461598a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Cc558098(v=AX.60)
ms:contentKeyID: 28119386
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Specify Measures for a Cube 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you specify a measure in Microsoft Dynamics AX, you must decide the scope of the measure and where it should be defined. You can specify a measure the following ways:

  - On a field in a table or view in a perspective.

  - On a field in a table.

  - On an extended data type.

In order to specify a measure on a field in a table or view in a perspective, you must have already created the perspective. For more information, see [How to: Create a Perspective for a Cube](create-a-perspective-for-a-cube.md).

The following procedure explains how to specify a measure for a cube on a field in a table or on an extended data type.

### To specify a measure for a cube

1.  In the AOT, select the extended data type or the table field to use to define the measure.

2.  In the **Properties** sheet, specify values for the following properties.
    
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
    <td><p><strong>AnalysisLabel</strong></p></td>
    <td><p>An optional label for the measure. Only specify a label when the label supplied for the <strong>Label</strong> property is not appropriate.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>AnalysisUsage</strong></p></td>
    <td><p><strong>Measure</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>AnalysisDefaultTotal</strong></p></td>
    <td><p>An aggregate function that is used to aggregate the measure values.</p>
    <div>

    > [!NOTE]
    > <P>Count and DistinctCount are the only aggregate function settings allowed on String fields by Analysis Services. If you set the <STRONG>AnalysisDefaultTotal</STRONG> value to an unsupported value, the cube will not build.</P>


    </div></td>
    </tr>
    </tbody>
    </table>
    

    > [!NOTE]
    > <P>If you create a measure group by using a view, the relationship between the measure group and dimensions must be specified manually in Microsoft SQL Server Business Intelligence Development Studio (BIDS) unless the view contains all fields of the backing table that are used to connect to a dimension.</P>

    
    If you specify a measure on an extended data type, any table field that references the extended data type and has its **AnalysisUsage** property set to **Auto** will be a measure. You can override the settings for the measure on a table field. For example, you may want to change the settings so that the table field is not a measure or specify a different aggregate function for the table field. For a detailed description of the BI properties and their options, see [Business Intelligence Properties](business-intelligence-properties.md).
    

    > [!NOTE]
    > <P>Microsoft Dynamics AX uses label translations to name the measures and dimensions of an Analysis Services project. The label translations that you provide are not subject to Common Language Specification (CLS) validations. A label translation may generate a dimension or measure name that does not comply with CLS specifications. An Analysis Services project that contains non-compliant dimensions or measures might not build.</P>

    

    > [!NOTE]
    > <P>Local currency measures are used for currency conversion in multi-dimensional queries and should not be used for reporting.</P>



## See also

[Cube Overview](cube-overview.md)

[Business Intelligence Properties](business-intelligence-properties.md)

[How to: Specify Dimensions and Attributes for a Cube](how-to-specify-dimensions-and-attributes-for-a-cube.md)

[How to: Create a Perspective for a Cube](create-a-perspective-for-a-cube.md)

[How to: Create a New SQL Server Analysis Services Project](create-a-new-sql-server-analysis-services-project.md)

[Measures and Measure Groups (SQL Server Books Online)](http://go.microsoft.com/fwlink/?linkid=115058)

[Introduction to Cubes (SQL Server Books Online)](http://go.microsoft.com/fwlink/?linkid=115081)

