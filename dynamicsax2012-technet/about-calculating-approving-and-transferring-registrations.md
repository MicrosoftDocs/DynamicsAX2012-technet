---
title: About calculating, approving and transferring registrations
TOCTitle: About calculating, approving and transferring registrations
ms:assetid: 42e201a0-94d5-460a-8474-d1fd2d0def87
ms:mtpsurl: https://technet.microsoft.com/library/Aa496963(v=AX.60)
ms:contentKeyID: 36056876
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- approval
- calculation
- transfer
- approve
- calculate
- calculating
- clock out
- clock in
- approving
- transferring
audience: Application User
ms.search.region: Global
---

# About calculating, approving and transferring registrations 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create and manage time and attendance registrations. Registrations made by workers must be calculated, approved, and transferred daily. During that process, any registration errors can be corrected, missing registrations can be added, and incorrect registrations can be deleted.


> [!TIP]
> <P>Time and attendance features can be used in manufacturing execution for time and attendance registrations in a production environment.</P>



## Calculating registrations

When registrations are calculated, they are verified against a worker's work time profile. The registrations that are calculated include work time, pay time, pay overtime, and absence time. Calculation is typically performed by a team leader or a supervisor. You can set up calculation groups for groups of workers to help make sure that the person calculating registrations can view information about only the workers on his or her team.

Before calculating registrations, you can override the work time profile for a specific worker.

If the registered time does not correspond to a worker’s work time profile, the calculation procedure will create errors, for example, a missing absence registration. The errors can be corrected and the registrations recalculated.

## Approving registrations

When all registrations have been calculated without errors, the registrations are ready to be approved. Approval is usually done by a worker other than the one in charge of calculating registrations, for example, a payroll administrator. You can set up approval groups for relevant groups of workers.

Before approving registrations, you can override pay agreements for individual workers and add manual premiums. See [Modify registrations before or after approval](modify-registrations-before-or-after-approval.md) for more information.

If overtime has been calculated for specific workers, the overtime can be allocated to specific jobs during the day. This is relevant if job cost is calculated based on worker pay.

During the process of approving a registration, you may have to enter additional information about absence registrations. If more absence information is needed, this will be pointed out during the approval process.

## Approving registrations using workflow

It is possible to set up a workflow approval process that automatically approves registrations that comply with the rules set up in the workflow. If workflow approval is activated, the user who calculates registrations, for example, a team leader or a supervisor, submits the calculated registrations for approval. Through the workflow process, the appropriate approvals and tasks are created and they are assigned to the users and roles as identified in the workflow.

The approval workflow automates the approval process and allows users who have approval rights to approve many worker registrations at a time. Only deviations that are not accepted in the approval workflow must be handled manually.

Two types of workflow approval can be created in time and attendance:

  - **Time and attendance days total workflow** – The workflow validates registrations against, for example, the expected number of work hours for the day.

  - **Time and attendance journal registration workflow** – The workflow validates each registration type for the date of the registration. The following journal registration types are available. The registration types are automatically selected in time and attendance, depending on the worker’s registration:
    
      - Regarding registration in time and attendance and manufacturing execution:
        
          - **Clock in**
        
          - **Clock out**
        
          - **Absence**
        
          - **Break**
        
          - **Switch code**
        
          - **Project**
        
          - **Project activity**
        
          - **Indirect activity**
    
      - Regarding registration on production jobs in manufacturing execution:
        
          - **Queue before**
        
          - **Setup**
        
          - **Process**
        
          - **Overlap**
        
          - **Transport**
        
          - **Queue after**
        
          - **Start assistance**
        
          - **Stop assistance**

## Transferring registrations

When registrations have been approved, they can be transferred to a periodic payroll job.

A transferred registration is posted to an activity or job that it relates to, for example, a production order or a project. Also, payroll transactions are generated for each worker based on the registrations.

## Reversing registrations

Registrations that have been transferred can be reversed (rolled back). The task of reversing registrations can be done until the time when the payroll period's pay transfer is run. This means that payroll data has been transferred to an external file. The external file can be imported into a payroll system.

When reversed, all registrations are withdrawn, and any transactions posted on production orders or projects are offset and neutralized.

## See also

[Calculate time and attendance for workers](calculate-time-and-attendance-for-workers.md)

[Approve time and attendance registrations](approve-time-and-attendance-registrations.md)

[Transfer time and attendance registrations](transfer-time-and-attendance-registrations.md)

[Set up calculation and approval groups for time and attendance](set-up-calculation-and-approval-groups-for-time-and-attendance.md)

[About profiles for time and attendance registrations](about-profiles-for-time-and-attendance-registrations.md)

[About payroll in Time and attendance](about-payroll-in-time-and-attendance.md)

[Updating payroll data for time and attendance](updating-payroll-data-for-time-and-attendance.md)

  


