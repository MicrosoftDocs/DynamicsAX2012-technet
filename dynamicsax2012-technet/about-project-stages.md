---
title: About project stages
TOCTitle: About project stages
ms:assetid: 9a3e4a61-cd36-4b46-9047-e5fb54d170b0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa498453(v=AX.60)
ms:contentKeyID: 36058703
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- created
- estimated
- scheduled
- finished
- project stages
- in process
---

# About project stages 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Project stages can serve as a guide to the project life cycle. You can define the project stages that you want to include in your projects on the **Project stage** tab of the **Project parameters** form.

There are five predefined project stages and three user-defined stages. The following table describes the predefined stages.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Stage</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Created</strong></p></td>
<td><p>Initial stage.</p></td>
</tr>
<tr class="even">
<td><p><strong>Estimated</strong></p></td>
<td><p>Manually started. This stage typically signifies that the project estimation process has been run.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Scheduled</strong></p></td>
<td><p>Automatically started when hour consumption is scheduled.</p></td>
</tr>
<tr class="even">
<td><p><strong>In process</strong></p></td>
<td><p>Manually started. This stage typically signifies start of the project.</p>
<div class="alert"> 

> [!NOTE]
> <P>This is the minimum stage required for recording transactions on the project.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Finished</strong></p></td>
<td><p>Manually started.</p>
<div class="alert"> 

> [!NOTE]
> <P>If you select this stage, additional processes cannot be run on the project.</P>


</div></td>
</tr>
</tbody>
</table>


Two stages, **In process** and **Finished**, are required for all projects except time projects. (A time project cannot have the **Finished** project stage assigned to it. This is because the finished stage implies that estimation has been a part of the project stage process. There are no estimations involved with time projects.) All other stages are optional.


> [!NOTE]
> <P>The stages that a particular project type must pass through are defined in the <STRONG>Project parameters</STRONG> form.</P>



You can rename the project stages and have the new names appear in forms and menu options. The three user-defined project stages can be used to track your project in more detail.

You can select the following tasks to assign to a project stage:

  - **Create quotation** - Create a project quotation for fixed-price and time-and-material projects.

  - **Create forecast/budget** - Create and schedule forecast lines for any transaction.

  - **Create estimates** - Create estimates for fixed-price projects.

  - **Create item tasks** - Create sales and purchase orders, item requirements, and production orders for projects.

  - **Create journals** - Create journals transactions for projects.

  - **Create invoice proposal** - Create an invoice proposal for fixed-price and time-and-material projects.

  - **Reverse eliminate** - Allow a reverse elimination of the budget for selected project types.


> [!TIP]
> <P>In the <STRONG>Project</STRONG> form, on the <STRONG>Action Pane</STRONG>, on the <STRONG>Maintain</STRONG> tab, in the <STRONG>Maintain</STRONG> group, click <STRONG>Project stage</STRONG> to select the appropriate stage to change the project to. Changes can be made at the same time to multiple project stages.</P>



## See also

[Modify a project stage](modify-a-project-stage.md)

[Project management and accounting parameters (form)](https://technet.microsoft.com/en-us/library/aa599440\(v=ax.60\))

[Projects (form)](https://technet.microsoft.com/en-us/library/aa585245\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

