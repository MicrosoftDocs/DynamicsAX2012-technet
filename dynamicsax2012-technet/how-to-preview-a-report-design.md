---
title: 'How to: Preview a Report Design'
TOCTitle: 'How to: Preview a Report Design'
ms:assetid: 1066a063-4bfb-4f2e-926b-cf39fde4bf6d
ms:mtpsurl: https://technet.microsoft.com/library/Cc519705(v=AX.60)
ms:contentKeyID: 28119309
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Preview a Report Design 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can preview a report design to be sure that it looks the way that you intended. You do not have to save a report design to preview it. You can preview a new design, or you can preview the modifications made to an existing design. The following procedure explains how to preview a report design.


> [!NOTE]
> <P>If your report uses data methods, the assemblies that contain the data methods must be built before you can preview the report. For more information, see <A href="how-to-build-a-reporting-project.md">How to: Build a Reporting Project</A>.</P>



### To preview a report design

1.  In Model Editor, expand the node for the report that you want to work with.

2.  Expand the **Designs** node for the report.

3.  Right-click the design that you want to preview, and then click **Preview**.
    
    The **Preview** window has two tabs: a **Parameters** tab and a **Report** tab. The **Parameters** tab lists any parameters that have been defined for the report. If the **Dynamics Filters** property on the dataset is set to True, you can filter on any of the fields in the underlying tables that the query is based on. For more information about parameters, see [How to: Define a Report Parameter](how-to-define-a-report-parameter.md). The **Report** tab displays the report. Any errors that are encountered are displayed in the **Error List** window.
    

    > [!NOTE]
    > <P>The preview will return 1000 records by default. This makes the processing of large amounts of data for the preview more efficient. If you want to see all the data in the preview of your report, in the <STRONG>Preview</STRONG> window, click the <STRONG>Load data sets fully</STRONG> link. For information on how to update the default number of records, see <A href="how-to-change-the-default-number-of-records-that-display-in-the-report-preview.md">How to: Change the Default Number of Records that Display in the Report Preview</A>.</P>



## See also

[How to: Create an Auto Design for a Report](how-to-create-an-auto-design-for-a-report.md)

[How to: Create a Precision Design for a Report](how-to-create-a-precision-design-for-a-report.md)

