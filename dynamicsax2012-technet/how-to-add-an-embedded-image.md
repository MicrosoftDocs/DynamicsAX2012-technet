---
title: 'How to: Add an Embedded Image'
TOCTitle: 'How to: Add an Embedded Image'
ms:assetid: 2eca893f-1178-42f6-b1c2-7e0b543c5d21
ms:mtpsurl: https://technet.microsoft.com/library/Cc586367(v=AX.60)
ms:contentKeyID: 28119331
author: tonyafehr
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Add an Embedded Image 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

An embedded image is one that is added directly to a model in your reporting project. Before you add an image to a model, you first need to decide how the image will be used in your reports. You can add the image so that it is available to all reports within the model or to just a single report. After an image has been added to a model, it can be easily referenced by a report. The following procedure explains how to add an embedded image.

### To add an embedded image

1.  In Model Editor, do one of the following:
    
      - To add the image so that it is available to all reports in the model, select **Image** from the **Add Element** drop-down menu on the Model Editor toolbar.
    
      - To add the image directly to a report, right-click the node for the report, point to **Add**, and then click **Image**. When you add an image directly to a report, it is available to that report only.

2.  Select the node for the image.

3.  In the **Properties** window, type a name for the **Name** property. Click the ellipsis button (…) for the **Base64 Data** property, and then select the image file.
    
    A thumbnail image of the imported file is displayed in the **Properties** window. The MIME type is derived from the image when it is imported. After an image has been added to a model or a report, you can display it in one or more report designs.

## See also

[Report Images Overview](report-images-overview.md)

[How to: Display Images in an Auto Design](how-to-display-images-in-an-auto-design.md)

[How to: Display Images in a Precision Design](how-to-display-images-in-a-precision-design.md)

