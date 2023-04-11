---
title: Report Designs (MorphX Reporting Tools)
TOCTitle: Report Designs
ms:assetid: b57623d5-7032-4821-b0aa-a50dcf879df9
ms:mtpsurl: https://technet.microsoft.com/library/Cc967418(v=AX.60)
ms:contentKeyID: 35290330
author: tonyafehr
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Report Designs (MorphX Reporting Tools) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The visible design of a report can be created by using the AOT. There are two available modes, the Automatic and Generated modes.

## Creating a Report Design

Both modes begin by following the same steps.


> [!NOTE]
> <P>Before you create a report design, create a report that has at least one data source. For more information, see <A href="walkthrough-creating-reports-in-the-aot-morphx-reporting-tools.md">Walkthrough: Creating Reports in the AOT (MorphX Reporting Tools)</A>.</P>



### To create a report design

1.  In the AOT, expand the **Reports** node, expand the node of the report for which you want to create a design, right-click **Designs**, and then click **New Report Design**.

2.  Right-click the new report design, and then click **Properties**.

3.  On the **Properties** sheet of the new report design, set the Name property to **MyReportDesign** and set the **Report Template** property to the desired report template (optional).

## Automatic Mode

The Automatic mode for creating a report design is generally recommended over the generated mode. The following steps show how to create an automatic report design.

### To create an automatic report design

1.  Under the **MyReportDesign** node, right-click the **AutoDesignSpecs** node, and then click **Generate Specs From Query**. This creates a **Body** subnode for each data source that is used in the query of the report.

2.  Under the **AutoDesignSpecs** node, right-click a body subnode, point to **New** **Control**, and then click the option that allows you to select a field from one of the data sources that were used in the query of the report. This opens a new window that contains the available fields from the data source you selected. Drag the fields you want to appear in the report onto the body subnode where you want the field to display.
    
    or
    
    Open a new AOT and navigate to the Fields node of one of the data sources that were used in the query of the report. Drag the fields you want to appear in the report onto the body subnode where you want the field to display.
    

    > [!NOTE]
    > <P>Consider under which data source it is appropriate to add fields. If your report has more than one data source and it does not appear as you expect it to look, this may be the issue.</P>



## Generated Mode

The following steps show how to create a generated report design.

### To create a generated report design

1.  Right-click **MyReportDesign** and then click **Generate Design**. This creates a new **Generated Design** node with **PageHeader** and **Section Group** subnodes. The **PageHeader** node is created by the report template (optional).

2.  Under the **Section Group** node of one of the data sources that is used in the query for the report, right-click a body subnode, point to **New Control**, and then click the option that allows you to select a field from one of the data sources that were used in the query of the report. This opens a new window that contains the available fields from the data source you selected. Drag the fields you want to appear in the report onto the body subnode where you want the field to display.
    
    or
    
    Open a new AOT and navigate to the **Fields** node of one of the data sources that were used in the query of the report. Drag the fields you want to appear in the report onto the body subnode where you want the field to display.
    

    > [!NOTE]
    > <P>Consider under which data source it is appropriate to add fields. If your report has more than one data source and it does not appear as you expect it to look, this may be the issue.</P>



## Design Mode Comparison

The report appears the same for each design mode.

### To view the report

1.  In the AOT, navigate to the report.

2.  Right-click the report and then click **Open**.

3.  Click **OK** on the two dialog boxes to accept the default report printing options.

Under the body node, a **PageHeader** node that you can customize appears when you use the generated mode. This **PageHeader** node does not appear when you use the automatic mode.

When changes are made to a report template, the changes are reflected in reports that have designs that were created by using the automatic design mode. If a report is created by using the generated design mode, changes to a report template are not reflected in reports automatically.

