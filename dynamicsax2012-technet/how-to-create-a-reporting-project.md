---
title: 'How to: Create a Reporting Project'
TOCTitle: 'How to: Create a Reporting Project'
ms:assetid: c8de8a82-023a-4f8f-805b-aa9e7dbb209d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Cc575711(v=AX.60)
ms:contentKeyID: 28119584
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Create a Reporting Project [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to create a Microsoft Dynamics AX reporting project in Microsoft Visual Studio.

### To create a reporting project

1.  Open Microsoft Visual Studio.

2.  On the **File** menu, point to **New**, and then click **Project**. The **New Project** dialog box displays.

3.  In the **Installed Templates** pane, select **Microsoft Dynamics AX**.

4.  In the right pane, select **Report Model**.

5.  In the **Name** field, type a name for the project.

6.  In the **Location** field, enter a path, or click **Browse** to specify one of the following:
    
      - Location in which a new solution will be stored.
    
      - Location of an existing solution to which a project will be added.
    

    > [!NOTE]
    > <P>Specify the location based on the <STRONG>Solution</STRONG> you specify.</P>



7.  The **Solution** field drop-down provides two options, click **Create new solution** or **Add to solution**.

8.  In the **Solution name** field when creating a new solution, type a name for the solution.

9.  Click the following check boxes if applicable:
    
      - Create directory for solution
    
      - Add to [source control](https://technet.microsoft.com/en-us/library/aa639568\(v=ax.60\))

10. Click **OK**.
    
    Next, you will add a report to the reporting project. For more information, see [How to: Add or Delete a Report](how-to-add-or-delete-a-report.md).

There is a distinction between managing reports versus managing report projects. Storing a report in the AOT happens when you add a report to a Microsoft Dynamics AX Report Model. If you want to store your reporting project or business logic assemblies for your reports in the AOT, then you must add the report project into Microsoft Dynamics AX. In the Solution Explorer, right-click the reporting project and click **Add \[project name\] to AOT**. When you add a report project to the AOT, the reporting project is added to the **Visual Studio Projects** \> **Dynamics AX Model Projects**. The following table summarizes the distinction between reports and report projects.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>AOT element</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Reports</p></td>
<td><ul>
<li><p>Stored and available in the AOT when it is added to a Microsoft Dynamics AX Report Model in Visual Studio.</p></li>
<li><p>Can be included in any number of reporting projects.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Report projects</p></td>
<td><ul>
<li><p>Stored and available in the AOT when you right-click the reporting project and click <strong>Add [project name] to AOT</strong>.</p></li>
<li><p>Used to manage a collection of reports or report business logic assemblies.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## See also

[Creating Reports Overview](creating-reports-overview.md)

[Reporting Project Overview](reporting-project-overview.md)

[How to: Add a Reporting Project to a Solution](how-to-add-a-reporting-project-to-a-solution.md)

[How to: Build a Reporting Project](how-to-build-a-reporting-project.md)

