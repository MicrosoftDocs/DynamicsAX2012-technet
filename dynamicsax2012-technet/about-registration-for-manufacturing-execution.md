---
title: About registration for manufacturing execution
TOCTitle: About registration for manufacturing execution
ms:assetid: 2a9370c0-8164-4b83-894e-aa2dd08fcb18
ms:mtpsurl: https://technet.microsoft.com/library/Hh208500(v=AX.60)
ms:contentKeyID: 36056238
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- time
- registration
- feedback
- register
- hour
- hours
- manufacturing execution
audience: Application User
ms.search.region: Global
---

# About registration for manufacturing execution 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic provides general information about manufacturing execution and the various kinds of registrations that workers can perform.

## About manufacturing execution

Manufacturing execution is primarily intended to be used by manufacturing companies. Workers can register time and item consumption on production jobs using the **Job registration** form.


> [!NOTE]
> <P>All registrations are approved and subsequently transferred to the relevant Microsoft Dynamics AX modules. Continuous approval and transfer of registrations give managers the ability to easily track actual costs on production orders.</P>



## Manufacturing execution terminology

The following table contains terms that relate to manufacturing execution and related registration tasks.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Term</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Manufacturing execution</p></td>
<td><p>A function in Microsoft Dynamics AX used to register time, material consumption, costs on production jobs, projects, and indirect activities. Registration is performed in a manufacturing execution registration client.</p></td>
</tr>
<tr class="even">
<td><p>Job list</p></td>
<td><p>In the <strong>Job registration</strong> form, workers are shown the list of jobs that they must perform on a specific resource, such as a machine. A worker can register time and item consumption on each job or task in the job list.</p></td>
</tr>
<tr class="odd">
<td><p>Job bundling</p></td>
<td><p>If a worker starts more than one job at the same time in the <strong>Job registration</strong> form, it is called job bundling. The time that is spent on bundled jobs can be allocated to the individual jobs in different ways by using allocation keys.</p></td>
</tr>
<tr class="even">
<td><p>Pilot/assistant registrations</p></td>
<td><p>A worker can register as an assistant to a resource and create a small team in which several workers work on the same production jobs. Resources that workers are connected to as assistants are called pilots. Only the pilot resource must make registrations; all assistants automatically get the same registrations. If, for example, a machine functions as the pilot, a worker who has registered as an assistant to that machine can make registrations in the <strong>Job registration</strong> form, and both the machine and the workers connected as assistants will receive the same registrations.</p></td>
</tr>
<tr class="odd">
<td><p>Indirect activity</p></td>
<td><p>An activity or task not directly related to a production job or a project, such as a department meeting, a cleaning job, or a maintenance job on the shop floor. Workers can make registrations on indirect activities same way as they can register on production jobs and projects.</p></td>
</tr>
</tbody>
</table>


## Registrations in manufacturing execution

Workers can make various types of registrations in manufacturing execution for work performed on production jobs. Depending on the system setup, it may also be possible to make registrations on project activities and non-productive tasks, such as breaks, absence, and indirect activities. The registration types are as follows:

  - Clock-in / clock-out (available with time and attendance)
    
    A worker clocks in when arriving at work and clocks out when leaving to go home from work.

  - Register on production jobs
    
    A worker can make registrations, such as starting a job and reporting feedback on a job on the production jobs that are displayed in his or her job list. It is possible for a worker to start several jobs at the same time; this is referred to as job bundling.

  - Register on inventory
    
    A worker can make registrations on materials used on the shop floor that are not directly related to production jobs. Examples are grease, lubricants, or other materials used to keep machinery running. Registration is performed in an inventory journal.

  - Register on projects (available with time and attendance)
    
    A worker can make registrations, such as starting and finishing work on the projects or project activities that are displayed in his or her job list.

  - Register project fees and project items (available with time and attendance)
    
    A worker can register fees (expenses) associated with a project in a project fee journal, such as mileage and bridge toll. It is also possible to register item consumption on projects. This is performed in a project item journal.

  - Register as assistant to another worker
    
    If two or more workers will work together on a production job or a project, a worker can register as an assistant to a machine, or to another worker, who will then act as the pilot. If needed, the pilot can select another worker as the pilot.

  - Register absence (available with time and attendance)
    
    A worker can register time on various absence codes that are set up. It is possible to indicate absence if a worker arrives late, requires absence during the work day, or leaves earlier than expected according to the standard work time profile.

  - Register breaks (available with time and attendance)
    
    During the work day, a worker can register that he or she is leaving the work station to take a break. Several break types can be set up. When the worker returns and logs on again, the system registers that the worker is back and the break registration stops.

  - Register indirect activities (available with time and attendance)
    
    Indirect activities are non-productive activities that a worker might engage in during a work day, such as a department meeting, a team meeting, or a maintenance job conducted on the shop floor. Workers can make registrations on the indirect activities that are set up.

  - Register overtime (available with time and attendance)
    
    If a worker has been asked to work longer hours, he or she can select if the extra hours should be registered as flextime or overtime.

## See also

[Key tasks: Work with production jobs in Manufacturing execution](key-tasks-work-with-production-jobs-in-manufacturing-execution.md)

[Key tasks: Process production jobs in Manufacturing execution](key-tasks-process-production-jobs-in-manufacturing-execution.md)

[About allocation keys](about-allocation-keys.md)

[View daily registrations in manufacturing execution](view-daily-registrations-in-manufacturing-execution.md)

  


