---
title: About indirect activities for time and attendance
TOCTitle: About indirect activities for time and attendance
ms:assetid: 85ca7cf1-11fc-4666-a7b1-fa8c0a389b57
ms:mtpsurl: https://technet.microsoft.com/library/Aa571575(v=AX.60)
ms:contentKeyID: 36058409
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- break
- profile
- indirect activities
- switch code
audience: Application User
ms.search.region: Global
---

# About indirect activities for time and attendance 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Indirect activities are used by workers to make registrations on jobs that are not directly related to a production order or a project. Also, indirect activities can be used to register breaks, on-call activities, and switch codes. Switch codes can be used to trigger a specific bonus pay or to switch one registration with another registration.

Indirect activities are grouped in categories that can only contain activities of the same registration type. Indirect activities include the following registration types.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Registration type</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Job</p></td>
<td><p>Activities that are not related to a specific production order or project, for example, staff meetings, cleaning jobs, repair jobs, seminars, and courses.</p>
<p>All system jobs, including clock-in and clock-out registrations, are this type of indirect activity.</p></td>
</tr>
<tr class="even">
<td><p>Break</p></td>
<td><p>This activity is used if workers register breaks.</p>
<p>Activities can also be set up to cancel one or all breaks in a work time profile. This is relevant, for example, when a worker works during a planned break. The following steps describe where to set up an activity to cancel breaks. Click <strong>Human resources</strong> &gt; <strong>Common</strong> &gt; <strong>Time and attendance</strong> &gt; <strong>Indirect activities</strong>. Double-click an indirect activity, and in the <strong>Activities</strong> form, click the <strong>General</strong> tab. In the <strong>Cancel break</strong> field, make the appropriate selection.</p></td>
</tr>
<tr class="odd">
<td><p>Switch code</p></td>
<td><p>This registration type is used for switching a registration for another registration or for activating certain pay lines in a pay agreement.</p>
<p>Switch codes can be used to override standard settings, for example, in case a supervisor allows a worker to take time off instead of receiving unpaid overtime. Switch codes can also be used to enable payment of a specific premium to a worker. Switch codes are valid for the entire profile day.</p></td>
</tr>
<tr class="even">
<td><p>On call</p></td>
<td><p>When workers are on call, they must register this type of indirect activity when they clock in.</p>
<p>When an on-call activity is registered, the registration will have the clock-in time as the starting time and the clock-out time as the stopping time. The worker can make registrations on specific jobs during this period.</p>
<p>On-call activities are often used to generate specific bonuses, but they can also be used to track on-call time.</p></td>
</tr>
</tbody>
</table>


## See also

[About time and attendance registrations](about-time-and-attendance-registrations.md)

[About registration for manufacturing execution](about-registration-for-manufacturing-execution.md)

[About profiles for time and attendance registrations](about-profiles-for-time-and-attendance-registrations.md)

[About payroll in Time and attendance](about-payroll-in-time-and-attendance.md)

[Set up indirect activities for time and attendance](set-up-indirect-activities-for-time-and-attendance.md)

  


