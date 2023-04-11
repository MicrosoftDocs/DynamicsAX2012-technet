---
title: Report Images Overview
TOCTitle: Report Images Overview
ms:assetid: e34f12e3-9dba-41bc-90e9-d8b81acb0300
ms:mtpsurl: https://technet.microsoft.com/library/Cc622140(v=AX.60)
ms:contentKeyID: 28119603
author: tonyafehr
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Report Images Overview 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

There are several common scenarios for displaying images in reports. For example, in product listings, it is common to display images along with the data in a report. In this scenario, images are usually stored along with the data in the database. If you create key performance indicator (KPI) reports, you typically work with a small set of images that are constant. In this case, it is typical to embed the images directly in the report. It is also common to display a company logo in a report.


> [!NOTE]
> <P>Displaying a company logo in a report is currently only supported in precision design reports.</P>



## Supported File Extensions

The file extensions that are supported for image files are: .bmp, .gif, .jpeg, .png, and .xpng.

## Referencing Images in Reports

There are several ways to reference an image in a report. You can use embedded images, external images, or images that are stored as binary data in a database table. The following table describes each scenario.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Type</p></th>
<th><p>Used in</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Embedded</p></td>
<td><p>Auto designs and precision designs</p></td>
<td><p>An embedded image is one that is added directly to a model in your reporting project. You can add an image so that it is available to all reports in the model or just a single report. For more information, see <a href="how-to-add-an-embedded-image.md">How to: Add an Embedded Image</a>.</p></td>
</tr>
<tr class="even">
<td><p>External</p></td>
<td><p>Precision designs</p></td>
<td><p>An external image is one that is stored separate from a report. To reference an external image in a report, you must specify a URL to indicate the location of the image. For more information, see <a href="how-to-display-images-in-a-precision-design.md">How to: Display Images in a Precision Design</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Database</p></td>
<td><p>Auto designs and precision designs</p></td>
<td><p>Images that are stored as binary image data in a database table can also be displayed in reports. This is typical in the case of product listings where an image of the product displays along with the product details. For more information, see <a href="how-to-display-images-in-an-auto-design.md">How to: Display Images in an Auto Design</a> and <a href="how-to-display-images-in-a-precision-design.md">How to: Display Images in a Precision Design</a>.</p></td>
</tr>
</tbody>
</table>


## See also

[Displaying Images in Reports](displaying-images-in-reports.md)

