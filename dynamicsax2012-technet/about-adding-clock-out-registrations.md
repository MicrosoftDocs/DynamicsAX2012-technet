---
title: About adding clock-out registrations
TOCTitle: About adding clock-out registrations
ms:assetid: c3463664-85d8-49d5-9ff9-d3d4848c41a3
ms:mtpsurl: https://technet.microsoft.com/library/Aa550712(v=AX.60)
ms:contentKeyID: 39519309
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About adding clock-out registrations 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If workers forget to clock out at the end of their work day, you can create clock-out registrations for them by running a batch job. This helps make sure that calculations include all clock-out registrations. You must run the batch job before you calculate information about worker registrations.

## Adding clock-out registrations

On the specified date, the batch job searches for clock-out registrations. When a missing registration is found, the following occurs:

  - If a worker does not have a clock-in registration before the profile end time, and no registrations exist after the end time, the batch job adds a clock-out registration at the profile end time.
    

    > [!NOTE]
    > <P>The profile end time is the end of the work day according to the worker’s work time profile. For example, if a day profile is set up with an expected clock-in time at 07:00 and an expected clock-out time at 15:00, then 15:00 is the profile end time.</P>



  - If a clock-in registration or a job registration is after the end time specified on the workers profile, then the worker has worked overtime. In this case, the batch job does not add a clock-out registration.


> [!NOTE]
> <P>You can also create clock-out registrations for a worker in the <STRONG>Calculate</STRONG> form and the <STRONG>Approve</STRONG> form.</P>



## See also

[About profiles for time and attendance registrations](about-profiles-for-time-and-attendance-registrations.md)

[Add clock-out registrations for workers](add-clock-out-registrations-for-workers.md)

  


