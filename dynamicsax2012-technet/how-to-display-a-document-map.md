---
title: 'How to: Display a Document Map'
TOCTitle: 'How to: Display a Document Map'
ms:assetid: 88793f46-a9de-4826-a9bb-a481ab186d9a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Cc602847(v=AX.60)
ms:contentKeyID: 28119393
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Display a Document Map [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can display a document map in an auto design report to help users navigate to different areas of a report. The document map displays in a separate pane adjacent to the body of the report. Data groupings determine the structure of a document map. For more information about data groupings, see [How to: Define Groupings in a Data Region](how-to-define-groupings-in-a-data-region.md). Report sections and data groupings are arranged in a hierarchical manner within a document map. Clicking an item in the document map refreshes the report and displays the area of the report that corresponds to the selected item. The following procedure explains how to display a document map in a report.

### To display a document map in a report

1.  In Model Editor, expand the node for the report that you want to work with.

2.  Expand the **Designs** node for the report.

3.  Locate the auto design that you want to modify, and then expand the node for the auto design to view its data regions.

4.  Select the data region for which you want to display a document map.

5.  In the **Properties** window, set the **Data Navigation Style** property to **DocumentMap**.
    

    > [!NOTE]
    > <P>You must <A href="how-to-define-groupings-in-a-data-region.md">define a grouping</A> in the auto design on which the document map will be based.</P>



6.  To preview the layout of the report, right-click the node for the design, and then click **Preview**.
    
    The **Preview** window has two tabs: a **Parameters** tab and a **Report** tab. The **Parameters** tab lists the parameters that have been defined for the report. If the **Dynamics Filters** property on the dataset is set to True, you can filter on any fields in the underlying tables that the query is based on. For more information about parameters, see [How to: Define a Report Parameter](how-to-define-a-report-parameter.md). The **Report** tab displays the report. Any errors that are encountered are displayed in the **Error List** window.

## See also

[How to: Add Drill Down and Drill Up Actions](how-to-add-drill-down-and-drill-up-actions.md)

[Walkthrough: Creating an Auto Design Report](walkthrough-creating-an-auto-design-report.md)

