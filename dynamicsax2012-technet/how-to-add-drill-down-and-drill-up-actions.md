---
title: 'How to: Add Drill Down and Drill Up Actions'
TOCTitle: 'How to: Add Drill Down and Drill Up Actions'
ms:assetid: ed28c2fd-532e-490b-8542-5ee8b4de96b5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Cc622722(v=AX.60)
ms:contentKeyID: 28119612
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Add Drill Down and Drill Up Actions 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Drill down and drill up actions allow users to drill into the data that is of most interest to them by expanding and collapsing sections of data within a report. To enable drill down and drill up actions, you must define one or more data groupings for the data region. The expandable and collapsible sections that display correspond to the groupings that have been defined. For more information, see [How to: Define Groupings in a Data Region](how-to-define-groupings-in-a-data-region.md). Drill down and drill up actions are especially useful when you have multilevel groupings. You can add drill down and drill up actions to matrix, table, and list data regions within an auto design report. The following procedure explains how to add drill down and drill up actions to a data region.

### To add drill down and drill up actions

1.  In Model Editor, expand the node for the report that you want to work with.

2.  Expand the **Designs** node for the report.

3.  Locate the auto design that you want to modify, and then expand the node for the auto design to view its data regions.
    

    > [!NOTE]
    > <P>You must <A href="how-to-define-groupings-in-a-data-region.md">define a grouping</A> in the auto design for the drill down action. From the <STRONG>Data</STRONG> node, drag the field to group by onto the <STRONG>Groupings</STRONG> node.</P>



4.  Select the data region for which you want to add drill down and drill up actions.

5.  In the **Properties** window, set the **Data Navigation Style** property to **DrillDown**.

6.  Set the **Style Template** property to **ListStyleTemplate**.
    

    > [!NOTE]
    > <P>If <STRONG>ListStyleTemplate</STRONG> is not an option, select the dataset, in the Properties window, set the <STRONG>Default layout</STRONG> property to <STRONG>HorizontalList</STRONG>.</P>



7.  To preview the layout of the report, right-click the node for the design, and then click **Preview**.
    
    The **Preview** window has two tabs: a **Parameters** tab and a **Report** tab. The **Parameters** tab lists the parameters that have been defined for the report.
    
    Click the **Report** tab to display the report.

## See also

[How to: Display a Document Map](how-to-display-a-document-map.md)

[How to: Define Groupings in a Data Region](how-to-define-groupings-in-a-data-region.md)

[How to: Add a Report Drill Through Action on a Report](how-to-add-a-report-drill-through-action-on-a-report.md)

[How to: Define a Report Parameter](how-to-define-a-report-parameter.md)

[How to: Add a URL Drill Through Action on a Report](how-to-add-a-url-drill-through-action-on-a-report.md)

