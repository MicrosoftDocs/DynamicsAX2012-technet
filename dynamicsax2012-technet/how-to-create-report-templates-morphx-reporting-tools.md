---
title: 'How to: Create Report Templates (MorphX Reporting Tools)'
TOCTitle: 'How to: Create Report Templates'
ms:assetid: 9138f635-8d6a-4383-8dd2-a6c0e3f89ca8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa661024(v=AX.60)
ms:contentKeyID: 35290310
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Create Report Templates (MorphX Reporting Tools) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create a template for reports. A report template can specify the sections that a report includes, such as a page header and footer, the controls that are included in each section, and the layout of the controls.

Report templates are in the Application Object Tree (AOT). To manage changes to AOT objects, a version control system is available. For more information, see [Version Control System](https://technet.microsoft.com/en-us/library/aa639568\(v=ax.60\)).

## Creating a Report Template

### To create a report template

1.  In the AOT, expand the **Reports** node, right-click **Report Templates**, and then click **New Report Template**.

2.  Right-click the template that you want, click **New**, and then click a section to add it to the template. For more information, see [Report Sections (MorphX Reporting Tools)](report-sections-morphx-reporting-tools.md).

3.  To add a control to the section, right-click the section, click **New Control**, and then click a control to add it to the section. Repeat this step to add additional controls.
    
    You can add an image to the report template by using a **Bitmap** control.

4.  To modify control and section properties, right-click a control or a section, and then click **Properties**. For more information, see [Report Design Section Properties](https://technet.microsoft.com/en-us/library/aa643974\(v=ax.60\)) and [Report Control Properties](https://technet.microsoft.com/en-us/library/aa652720\(v=ax.60\)).

5.  Right-click the template, and then click **Save**.

