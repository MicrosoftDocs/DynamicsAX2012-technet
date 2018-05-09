---
title: About work breakdown structures
TOCTitle: About work breakdown structures
ms:assetid: f6c235f9-468a-431c-ab7d-6bf649fe7620
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh227544(v=AX.60)
ms:contentKeyID: 36060018
ms.date: 10/06/2014
mtps_version: v=AX.60
f1_keywords:
- project add-in
- worker attributes
- worker skills
- breakdown structures
- work breakdown structures
- project activities
- worker experience
---

# About work breakdown structures 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A project often consists of multiple tasks. In Microsoft Dynamics AX 2012, a work breakdown structure (WBS) is a hierarchy that represents the sequence of tasks for a project. In a WBS, you can schedule a task, specify the education and experience that are required for the task, assign qualified workers, and enter the estimated cost and revenue for the task.

You can make a task dependent on the completion of another task or tasks in the same WBS. For example, make the start of a design task dependent on finishing a planning task. In the WBS, the starting date for a dependent task is automatically set to the day after the predecessor task ends.

You can create a WBS manually, or copy the WBS from another project into the current project and then modify the WBS details for the current project. You can also save a WBS as a template, and then use the template as a starting point to create a WBS for projects that are frequently repeated. By using a template, you can set up a WBS for a new project more efficiently.

In Microsoft Dynamics AX 2012 R3 or cumulative update 7 or later for AX 2012 R2, you can use Microsoft Project to manage the work breakdown structure (WBS) for a project or a project quotation, and then publish the WBS to your project in Microsoft Dynamics AX. For more information, see [Create or update a project by using Microsoft Project](create-or-update-a-project-by-using-microsoft-project.md).

In AX 2012 R3, you can also easily transfer item estimates from a WBS to project forecasts. For more information, see [Transfer work breakdown estimates to project forecasts](transfer-work-breakdown-estimates-to-project-forecasts.md).

In a WBS, you can add the following details for each task:

  - The estimated effort, expressed in number of hours.

  - The cost per hour.

  - The sales price per hour to charge the customer.

  - The number of workers needed to complete the task.

  - The starting date and ending date.
    
    If there are conflicts or overlaps in the date range that you select for tasks, you can view and fix these scheduling discrepancies.

  - The name of the worker who is expected to complete the task. You can add more than one worker per task.


> [!NOTE]
> <P>In Microsoft Dynamics AX 2012 Feature Pack and Microsoft Dynamics AX 2012, the <STRONG>Work breakdown structure</STRONG> form is named <STRONG>Activity breakdown structure</STRONG>.</P>



## See also

[Work breakdown structure (form)](https://technet.microsoft.com/en-us/library/hh209089\(v=ax.60\))

[Create a work breakdown structure of tasks for a project](create-a-work-breakdown-structure-of-tasks-for-a-project.md)

[Create a work breakdown structure template for projects](create-a-work-breakdown-structure-template-for-projects.md)

[Transfer work breakdown estimates to project forecasts](transfer-work-breakdown-estimates-to-project-forecasts.md)

[Activities (form)](https://technet.microsoft.com/en-us/library/aa576083\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

