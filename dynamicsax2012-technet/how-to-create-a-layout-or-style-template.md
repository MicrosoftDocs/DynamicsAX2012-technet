---
title: 'How to: Create a Layout or Style Template'
TOCTitle: 'How to: Create a Layout or Style Template'
ms:assetid: 99bf5100-1f47-46d7-aea5-b0c02588c097
ms:mtpsurl: https://technet.microsoft.com/library/Cc607039(v=AX.60)
ms:contentKeyID: 28119540
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Create a Layout or Style Template 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic explains how to create layout and style templates. A layout template defines the general layout and style settings for a report. A style template contains the layout and style settings for a data region that displays in the body of a report. Each style template is specific to a data region type. For example, if you define a style template for a table data region, it can only be applied to table data regions. Layout and style templates are used in auto design reports and not accessed for precision design reports.


> [!NOTE]
> <P>If you want your reports to have the same look and feel as existing reports included with Microsoft Dynamics AX, be sure to use the predefined layout and style templates for Microsoft Dynamics AX. For more information, see <A href="predefined-layout-and-style-templates.md">Predefined Layout and Style Templates</A>.</P>



### To create a layout template for a report

1.  In Solution Explorer, right-click the reporting project that you want to add a layout template to, point to **Add**, and then click **New Item**. The **Add New Item** dialog box displays.

2.  In the **Templates** pane, click **Report Layout Template**. This is a model that contains a single layout template.

3.  Type a name for the layout template.

4.  Click **Add**.
    
    A node for the layout template displays along with several subnodes for the various sections within the report. The layout template contains default settings for each section.

5.  To change the settings for a particular section, select the node for the section and edit the properties in the **Properties** window.

### To create a style template for a data region

1.  In Solution Explorer, right-click the reporting project that you want to add a style template to, point to **Add**, and then click **New Item**. The **Add New Item** dialog box displays.

2.  In the **Templates** pane, select the type of style template that you want to create. For information about each style template, see [Predefined Layout and Style Templates](predefined-layout-and-style-templates.md).

3.  Type a name for the style template.

4.  Click **Add**.
    
    A node for the style template displays along with several subnodes for the various sections within the data region. The style template contains default settings for each section.

5.  To change the settings for a particular section, select the node for the section and edit the properties in the **Properties** window.

## See also

[Creating Reports Overview](creating-reports-overview.md)

[Predefined Layout and Style Templates](predefined-layout-and-style-templates.md)

[How to: Apply a Layout or Style Template](how-to-apply-a-layout-or-style-template.md)

