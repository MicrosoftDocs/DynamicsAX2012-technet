---
title: 'How to: Specify a Report Design by Using X++ (MorphX Reporting Tools)'
TOCTitle: 'How to: Specify a Report Design by Using X++'
ms:assetid: 78f9b36b-cdcf-4b6f-8ab8-4881ba89ee18
ms:mtpsurl: https://technet.microsoft.com/library/Aa611590(v=AX.60)
ms:contentKeyID: 35290301
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Specify a Report Design by Using X++ (MorphX Reporting Tools) 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When a report has multiple designs, you can use X++ to specify which design will be displayed when the report is printed.

## Specifying a Report Design

Use the ReportRun::design method to specify a report design.

### To specify a report design

1.  In the Application Object Tree (AOT), expand the report node, right-click **Methods**, and then click **New Method**.

2.  In the new method, call the design method to specify a report design.
    
    In the following example, the design method specifies the ReportDesign2 design for the AssetAcquisition report.
    
        public void SetDesign()
        {
            Args ArgList = new Args(reportStr("AssetAcquisition"));
            ReportRun rr = new ReportRun(ArgList);
        
            rr.design('ReportDesign2');
            rr.run();
        
        }

## See also

[MorphX Reporting Tools](morphx-reporting-tools.md)

