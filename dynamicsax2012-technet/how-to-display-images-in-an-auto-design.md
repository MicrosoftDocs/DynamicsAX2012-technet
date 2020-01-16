---
title: 'How to: Display Images in an Auto Design'
TOCTitle: 'How to: Display Images in an Auto Design'
ms:assetid: f9ffab6a-21b3-4ada-a87d-5cddca48b103
ms:mtpsurl: https://technet.microsoft.com/library/Cc654537(v=AX.60)
ms:contentKeyID: 28119621
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Framework.Design.Model.Reports.ImageItemDefinition
---

# How to: Display Images in an Auto Design 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can display images along with the data in a list or table data region, as well as in group headers and group footers. You can also display images in row groupings within a matrix data region. The following procedures explain how to display images in an auto design report.

### To display an image in a list or table data region

1.  In Model Editor, expand the node for the report, and then expand the **Designs** node.

2.  Expand the node for the auto design that you want to work with, and then expand the node for the data region.

3.  Right-click the **Data** node, point to **Add**, and then click **Image**.

4.  Type a name for the image.

5.  Select the node for the image.

6.  In the **Properties** window, specify values for the following properties.
    
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
    <td><p><strong>Source</strong></p></td>
    <td><p>The source type of the image. For example, you can specify <strong>Embedded</strong> or <strong>Database</strong>. For more information, see <a href="report-images-overview.md">Report Images Overview</a>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>MimeType</strong></p></td>
    <td><p>The MIME type for the image. For example, <strong>image/gif</strong> or <strong>image/bmp</strong>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Expression</strong></p></td>
    <td><p>A name or expression that identifies the image.</p>
    <ul>
    <li><p>If the <strong>Source</strong> property is set to <strong>Embedded</strong>, you can specify the name of the image as it appears in the model. Or, you can specify an expression that evaluates to a name of an image, such as =IIF(Fields!Status.Value = 0, &quot;GreenIcon&quot;, IIF(Fields!Status.Value = 1, &quot;YellowIcon&quot;, &quot;RedIcon&quot;)). In either case, the images must be added to the model or report in Model Editor. For more information, see <a href="how-to-add-an-embedded-image.md">How to: Add an Embedded Image</a>.</p></li>
    <li><p>If the <strong>Source</strong> property is set to <strong>Database</strong>, you must specify the field that contains the binary image data.</p></li>
    </ul></td>
    </tr>
    <tr class="even">
    <td><p><strong>Caption</strong></p></td>
    <td><p>The text that displays for the image in the report.</p></td>
    </tr>
    </tbody>
    </table>
    
    There are several additional properties for an image that display in the **Properties** window. For example, you can specify border style settings and image sizing information. Modify the remaining properties as appropriate.

### To display an image in a group header or footer in a list or table data region

1.  In Model Editor, expand the **Groupings** node for the data region.

2.  Expand the node for the grouping that you want to work with.

3.  Expand the **Header** or **Footer** node, right click the node for the row, point to **Add**, and then click **Image**.

4.  Select the node for the image and specify properties for the image in the **Properties** window. Be sure to specify a value for the **Source**, **MimeType** and **Expression** properties. For a description of these properties, see the first procedure in this topic.

### To display an image in a row grouping in a matrix data region

1.  In Model Editor, expand the **Row Groupings** node for the data region.

2.  Expand the node for the grouping that you want to work with.

3.  Right-click the **Data** node, point to **Add**, and then click **Image**.

4.  Select the node for the image and specify properties for the image in the **Properties** window. Be sure to specify a value for the **Source**, **MimeType** and **Expression** properties. For a description of these properties, see the first procedure in this topic.

## See also

[Report Images Overview](report-images-overview.md)

[How to: Add an Embedded Image](how-to-add-an-embedded-image.md)

[How to: Display Images in a Precision Design](how-to-display-images-in-a-precision-design.md)

