---
title: 'How to: Add an Existing Report to a Reporting Project'
TOCTitle: 'How to: Add an Existing Report to a Reporting Project'
ms:assetid: b11e0118-6d16-4046-927f-ee1093e660b5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg724096(v=AX.60)
ms:contentKeyID: 35133454
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Add an Existing Report to a Reporting Project [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to add an existing report to a reporting project. The task to add an existing report to a reporting project is performed in Visual Studio. You use Application Explorer and Model Editor tools to complete the task.

### To Add an Existing Report

1.  In Visual Studio, with a project open, on the **View** menu, select **Application Explorer**. The Application Explorer opens. Application Explorer lets you view items and perform tasks in the Application Object Tree (AOT) in Microsoft Dynamics AX.

2.  In Application Explorer, expand the **SSRS Reports** \> **Reports** node. Find the report that you want to add to the project.

3.  Right-click the report and select **Add to Project**. The report is added to the current project.
    

    > [!NOTE]
    > <P>You may need to open the report for edit at the Visual Studio project level. The project solution will contain any necessary dependencies for the report to build. For example, report drill-throughs require both the source and target report to be loaded in the solution to build successfully. For information on the reports that a reporting project contains, see <A href="list-of-reporting-projects.md">List of Reporting Projects</A>.</P>



## See also

[Report Integration and Customization Overview](report-integration-and-customization-overview.md)

[How to: Add or Delete a Report](how-to-add-or-delete-a-report.md)

[Application Explorer](https://technet.microsoft.com/en-us/library/cc637855\(v=ax.60\))

[Model Editor Overview](https://technet.microsoft.com/en-us/library/cc643142\(v=ax.60\))

[Working with Reporting Projects](working-with-reporting-projects.md)

