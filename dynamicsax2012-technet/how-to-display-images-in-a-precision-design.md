---
title: 'How to: Display Images in a Precision Design'
TOCTitle: 'How to: Display Images in a Precision Design'
ms:assetid: 0a3c3451-b8ee-44ad-961a-d880d313bc02
ms:mtpsurl: https://technet.microsoft.com/library/Cc565754(v=AX.60)
ms:contentKeyID: 28119302
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Display Images in a Precision Design 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The following procedure explains how to display an image in a precision design report.

### To display an image in a precision design

1.  In Model Editor, expand the node for the report that you want to work with.

2.  Expand the **Designs** node for the report.

3.  To edit a precision design, do one of the following.
    
      - If the precision design already exists, right-click the design, and then click **Edit Using Designer**.
    
      - If you have not created the precision design, right-click the **Designs** node, point to **Add**, and then click **Precision Design**.
    
    This opens the SQL Report Designer.

4.  In the **Toolbox**, select the **Image** control and drag it to an appropriate location in the report.
    
    If you want to display image data along with other data in a list, table, or matrix data region, you must first create the data region. If the image is from a database field, be sure to set the **DataElementName** property for the data region to the dataset that contains the field for the image. After you have done that, drag the image control to the appropriate location within the data region.
    
    The **Image Properties** dialog opens.

5.  Set the following properties:
    
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
    <td><p><strong>Name:</strong></p></td>
    <td><p>Provide a name for the image.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>ToolTip:</strong></p></td>
    <td><p>Provide a tool tip for the image.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Select the image source:</strong></p></td>
    <td><p>Use the drop-down to set the source of the image. For example, you can specify <strong>External</strong>, <strong>Embedded</strong>, or <strong>Database</strong>. For more information, see <a href="report-images-overview.md">Report Images Overview</a>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Use this image:</strong></p></td>
    <td><p>The name or path of the image.</p>
    <ul>
    <li><p>If the <strong>Source</strong> property is set to <strong>Database</strong>, you must specify the field that contains the binary image data and the MIME type.</p></li>
    <li><p>If the <strong>Source</strong> property is set to <strong>External</strong>, you must provide a valid URL path to the image.</p></li>
    <li><p>If the <strong>Source</strong> property is set to <strong>Embedded</strong>, you must specify the name of the image.</p></li>
    </ul></td>
    </tr>
    <tr class="odd">
    <td><p><strong>MIMEType</strong></p></td>
    <td><p>The MIME type for the image. For example, <strong>image/gif</strong> or <strong>image/bmp</strong>.</p></td>
    </tr>
    </tbody>
    </table>


6.  Save the changes made to the report.

7.  To preview the report with the image, click the **Preview** tab in SQL Report Designer. Or, in Model Editor, right-click the node for the design, and then click **Preview**.

## See also

[Report Images Overview](report-images-overview.md)

[How to: Add an Embedded Image](how-to-add-an-embedded-image.md)

[How to: Display Images in an Auto Design](how-to-display-images-in-an-auto-design.md)

