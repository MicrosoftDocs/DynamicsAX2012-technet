---
title: About resource management for projects
TOCTitle: About resource management for projects
ms:assetid: 324a63e4-855e-4a62-bd0c-1300fa223f9b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208573(v=AX.60)
ms:contentKeyID: 36056355
ms.date: 10/06/2014
mtps_version: v=AX.60
f1_keywords:
- project-based scheduling
- resource assignments
- resource management
- resource scheduling
- resource-based scheduling
- worker attributes
- worker availability
audience: Application User
ms.search.region: Global
---

# About resource management for projects 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX, you can schedule worker resources based on the requirements and schedule of a project or on the skills and availability of workers. By using the resource scheduling capabilities, you can deploy your organization's workers efficiently and effectively. You can quickly find the most qualified workers who are available to work on your project, and you can easily see how to better utilize those workers during the course of the project.


> [!NOTE]
> <P>For more information about how to schedule workers in projects in Microsoft Dynamics AX 2012 R2, see the white paper <A href="http://go.microsoft.com/fwlink/?linkid=268038%26clcid=0x409">Microsoft Dynamics AX 2012 R2 – Resource scheduling in Project management and accounting</A>.</P>
> <P>For more information about how to schedule workers in projects in AX 2012 R3, see the white paper <A href="http://www.microsoft.com/en-us/download/details.aspx?id=43112">Worker resource scheduling in MIcrosoft Dynamics AX 2012 R3</A>.</P>



  - A human resources manager can use resource-based resource scheduling to schedule workers in a way that optimizes the use of the available workforce. The manager can review the capacity of each worker and see whether the worker is being adequately scheduled. The manager can then assign the worker to a project or activity based on the project requirements and the worker’s attributes, experience, and availability.

  - A project manager can use project-based resource scheduling to review the worker assignments for each project or activity to make sure that the project or activity is correctly staffed. Project-based scheduling provides a process to assign workers to a specific project or activity based on the worker’s skills and availability.

## Resource scheduling capabilities in Microsoft Dynamics AX

Microsoft Dynamics AX provides a number of resource scheduling capabilities that give you a high degree of control over how you staff your projects and manage your worker resources over the course of the project. These resource scheduling features enable you to do the following:

  - Use information about a worker’s attributes, such as education, skills, certifications, and project experience, to match the worker to the requirements of a project.

  - Use information about a worker’s calendar and availability to match the worker’s schedule to the project calendar.

  - Review the capacity of each worker and determine how that capacity is being used. For example, if a worker is being underused, the worker can be assigned to a project that fits with the worker’s availability and attributes.

  - Review worker availability to make sure that there are no calendar conflicts with their assignments.

  - Review information about worker utilization in a summary manner, such as by department or by worker, or in a detailed view, such as by workers in a department or by weekly detail for each worker.

  - Modify resource assignments for different units of time, such as day, week, or month, to optimize how the workers are used.

## Prerequisites for using the resource scheduling tools

The following prerequisites must be completed before workers can be assigned to a project or activity:

  - Set up the project parameters that determine the minimum thresholds for how closely a worker’s skills and availability must match the requirements for a project or activity for the worker to be included in search results. The scheduling and skills-match parameters are located in the **Project management and accounting parameters** form, in the **Scheduling** area. For more information about how to set up these project parameters, see [Project management and accounting parameters (form)](https://technet.microsoft.com/en-us/library/aa599440\(v=ax.60\)).

  - Define the scheduling requirements for the project or activity in the **Projects** form.
    

    > [!NOTE]
    > <P>The name of the FastTab that you use to set up scheduling requirements in the <STRONG>Projects</STRONG> form depends on the version of Microsoft Dynamics AX 2012 that you are using.</P>
    > <UL>
    > <LI>
    > <P>In Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack, use the <STRONG>Scheduling</STRONG> FastTab.</P>
    > <LI>
    > <P>In Microsoft Dynamics AX 2012 R2, use the <STRONG>Scheduling and resource assignment</STRONG> FastTab</P>
    > <LI>
    > <P>In cumulative update 7 for Microsoft Dynamics AX 2012 R2, use the <STRONG>Project team and scheduling</STRONG> FastTab.</P></LI></UL>

    
    The requirements include such things as:
    
      - The type of calendar for the project
    
      - The start date and end date of the project or activity
    
      - The length of time required to complete the project or activity
    
      - The estimated number of worker hours required to complete the project
    
    For more information about how to define the scheduling requirements for a project or activity, see [Projects (form)](https://technet.microsoft.com/en-us/library/aa585245\(v=ax.60\)).

  - Define the project activities and any activity requirements in the **Work breakdown structure** form. For more information about how to set up a work breakdown structure, see [About work breakdown structures](about-work-breakdown-structures.md) and [Work breakdown structure (form)](https://technet.microsoft.com/en-us/library/hh209089\(v=ax.60\)).
    

    > [!NOTE]
    > <P>In Microsoft Dynamics AX 2012 R3 or cumulative update 7 or later for AX 2012 R2, you can use Microsoft Project to manage the work breakdown structure (WBS) for a project or a project quotation, and then publish the WBS to your project in Microsoft Dynamics AX. For more information, see <A href="create-or-update-a-project-by-using-microsoft-project.md">Create or update a project by using Microsoft Project</A>.</P>



  - Set up or verify the calendar to use for the worker. For more information about how to set the calendar for a worker, see [Worker (form)](https://technet.microsoft.com/en-us/library/hh209054\(v=ax.60\)).

  - Set up or verify the worker’s education, skills, certifications, project experience, and other attributes.
    
    For more information about how to set up additional worker attributes, see [Set up worker attributes](set-up-worker-attributes.md) and [Other worker attributes (form)](https://technet.microsoft.com/en-us/library/hh242802\(v=ax.60\)).

## See also

[Set up worker attributes](set-up-worker-attributes.md)

[Identify and assign qualified workers to projects](identify-and-assign-qualified-workers-to-projects.md)

[Key tasks: Assign workers to projects based on availability](key-tasks-assign-workers-to-projects-based-on-availability.md)

[Key tasks: Create a schedule based on a project in Microsoft Dynamics AX 2012](key-tasks-create-a-schedule-based-on-a-project-in-microsoft-dynamics-ax-2012.md)

[Assign resources (form)](https://technet.microsoft.com/en-us/library/hh208809\(v=ax.60\))

[Schedule resources (form)](https://technet.microsoft.com/en-us/library/hh209507\(v=ax.60\))

[Resource assignments (form)](https://technet.microsoft.com/en-us/library/hh242655\(v=ax.60\))

[Resource assignment analysis - Project (form)](https://technet.microsoft.com/en-us/library/hh209116\(v=ax.60\))

[Resource assignment analysis - Project (form) in AX 2012 R3](https://technet.microsoft.com/en-us/library/dn736992\(v=ax.60\))

[Resource assignment analysis - worker (form)](https://technet.microsoft.com/en-us/library/hh227569\(v=ax.60\))

  


