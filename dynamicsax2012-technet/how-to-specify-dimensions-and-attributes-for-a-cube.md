---
title: 'How to: Specify Dimensions and Attributes for a Cube'
TOCTitle: 'How to: Specify Dimensions and Attributes for a Cube'
ms:assetid: 95790e4f-71c4-4a10-b0b6-aaec644c385b
ms:mtpsurl: https://technet.microsoft.com/library/Cc595579(v=AX.60)
ms:contentKeyID: 28119400
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Specify Dimensions and Attributes for a Cube 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The following procedures illustrate how to specify dimensions and attributes for a cube in Microsoft Dynamics AX.

### To specify a table as a dimension

1.  In the AOT, expand the **Data Dictionary** node.

2.  Do one of the following:
    
      - To specify a dimension directly on a table, expand the **Tables** node, right-click the table that you want to specify as a dimension, and then click **Properties**.
    
      - To specify a dimension on a table in a perspective, expand the **Perspectives** node, expand the node for the perspective, expand the **Tables** node, right-click the table that you want to specify as a dimension, and then click **Properties**.
    
      - To specify a dimension on a view in a perspective, expand the **Perspectives** node, expand the node for the perspective, expand the **Views** node, right-click the view that you want to specify as a dimension, and then click **Properties**.

3.  In the **Properties** sheet, specify the following properties.
    
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
    <td><p><strong>IsLookup</strong></p></td>
    <td><p>Used to automatically create a dimension attribute hierarchy.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>AnalysisIdentifier</strong></p></td>
    <td><p>The dimension instance identifier.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>AnalysisDimensionType</strong></p></td>
    <td><p>The type of dimension to create.</p></td>
    </tr>
    </tbody>
    </table>


For a detailed description of the Business Intelligence properties and their options, see [Business Intelligence Properties](business-intelligence-properties.md).

Now that the dimension is defined, add fields to the dimension.

### To specify a field as an attribute on a dimension

1.  In the AOT, expand the **Data Dictionary** node.

2.  Do one of the following:
    
      - To specify a dimension attribute directly on a table field, expand the **Tables** node, expand the node for the table, expand the **Fields** node, right-click the table field that you want to specify as a dimension attribute, and then click **Properties**.
    
      - To specify a dimension attribute on a table field in a perspective, expand the **Perspectives** node, expand the node for the perspective, expand the **Tables** node, expand the node for the table, expand the **Fields** node, right-click the table field that you want to specify as a dimension attribute, and then click **Properties**.
    
      - To specify a dimension attribute on a view field in a perspective, expand the **Perspectives** node, expand the node for the perspective, expand the **Views** node, expand the node for the view, expand the **Fields** node, right-click the table field that you want to specify as a dimension attribute, and then click **Properties**.

3.  In the **Properties** sheet, specify the following properties.
    
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
    <td><p><strong>AnalysisUsage</strong></p></td>
    <td><p><strong>Attribute</strong></p></td>
    </tr>
    <tr class="even">
    <td><p><strong>AnalysisLabel</strong></p></td>
    <td><p>A label for the measure. Only specify a label for this property when the label supplied for the <strong>Label</strong> property is not appropriate.</p></td>
    </tr>
    </tbody>
    </table>
    

    > [!NOTE]
    > <P>If a table field has the same name as its table and you set the table field as an attribute, the attribute will not be generated.</P>



Microsoft Dynamics AX uses label translations to name the measures and dimensions of an Analysis Services project. The label translations that you provide are not subject to Common Language Specification (CLS) validations. A label translation may generate a dimension or measure name that does not comply with CLS specifications. An Analysis Services project that contains non-compliant dimensions or measures might not build.

For a detailed description of the Business Intelligence properties and their options, see [Business Intelligence Properties](business-intelligence-properties.md).

## See also

[Defining Cubes in Microsoft Dynamics AX](defining-cubes-in-microsoft-dynamics-ax.md)

[How to: Specify Measures for a Cube](how-to-specify-measures-for-a-cube.md)

[Walkthrough: Creating a Cube](walkthrough-creating-a-cube.md)

