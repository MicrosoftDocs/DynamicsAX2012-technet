---
title: Adding Links to a Report
TOCTitle: Adding Links to a Report
ms:assetid: 114da6ff-e3c8-436f-8ccf-f845a36df6f0
ms:mtpsurl: https://technet.microsoft.com/library/Hh533446(v=AX.60)
ms:contentKeyID: 39056462
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Adding Links to a Report 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This section provides information about how to add links in a Microsoft Dynamics AX report. Visual Studio tools for Microsoft Dynamics AX supports links for the following actions:

  - A **Report Drill Through Action** lets you link to other reports. When defining a report drill through action, there are two reports involved: the top-level report and the drillthrough report. The top-level report is where the report drill through action is defined. The drillthrough report is opened by the user by clicking a link within the top-level report. It lets the user drill through to additional data about the item that was clicked in the top-level report. Parameters can be used to pass data from the top-level report to the drillthrough report. It is not required that you pass data to a drillthrough report. For example, you might display codes on your report and link to a list that describes what each code represents.

  - A **URL Drill Through Action** lets you add a hyperlink so that users can access a web page, an Enterprise Portal page, or a form in the Microsoft Dynamics AX client by clicking a linked item in a report. The hyperlink can be a static URL or an expression that evaluates to a URL.

The following topics describe how to create each type of link:

[How to: Add a Report Drill Through Action on a Report](how-to-add-a-report-drill-through-action-on-a-report.md)

[How to: Add a URL Drill Through Action on a Report](how-to-add-a-url-drill-through-action-on-a-report.md)

