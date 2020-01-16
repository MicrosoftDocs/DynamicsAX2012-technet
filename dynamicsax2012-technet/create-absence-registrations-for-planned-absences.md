---
title: Create absence registrations for planned absences
TOCTitle: Create absence registrations for planned absences
ms:assetid: 9eb55320-a804-41eb-8736-a90c11d16c2a
ms:mtpsurl: https://technet.microsoft.com/library/Aa571737(v=AX.60)
ms:contentKeyID: 43976721
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- absence
- plan
audience: Application User
ms.search.region: Global
---

# Create absence registrations for planned absences 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Supervisors or team leaders calculate time registrations that have been submitted by the workers on their teams. To help make the process of calculating those registrations more efficient, supervisors and team leaders can plan for absences by creating absence registrations in advance.

By registering absences in advance, you can plan for holidays, external training courses, parental leave, and other types of absence registrations that you know about before they actually occur. You can register a planned absence for a group of workers or for an individual worker.

## Register a planned absence for a group of workers

1.  Click **Human resources** \> **Periodic** \> **Time and attendance** \> **Create planned absence**.

2.  In the **Create planned absence** form, in the **From date**, **From**, **To date**, and **To** fields, select the period for the absence registration.

3.  In the **Absence job** field, select the type of absence to register.

4.  If you want the absence registration to stop if a worker clocks in before the planned end time, select the **Interrupt** check box.

5.  If you want to create an absence registration for each day in the specified period, select the **Compose** check box.

6.  Click **Select**.

7.  Create a query, and select the group of workers to include in the absence registration.

## Register a planned absence for one worker

1.  Click **Human resources** \> **Common** \> **Workers** \> **Time registration workers**. On the **Action Pane**, on the **Time registration** tab, click **Set up time registration worker** \> **Absence registrations**.

2.  In the **Absence registration** form, in the **Start date/time** and **End date/time** fields, select the period for the absence registration.

3.  In the **Absence group** and **Absence code** fields, select the absence reasons that must be used for this registration.

4.  If you want the absence registration to stop if the worker clocks in before the planned end time, select the **Interrupt** check box.
    

    > [!NOTE]
    > <P>If the <STRONG>Interrupt</STRONG> check box was selected when the absence registration was created, and the worker clocks in before the end time of the absence registration, the <STRONG>Interrupted</STRONG> check box is automatically selected at the time of the clock-in.</P>



## See also

[Create planned absence (form)](https://technet.microsoft.com/library/aa618740\(v=ax.60\))

[Planned absence registrations (form)](https://technet.microsoft.com/library/aa589208\(v=ax.60\))

  


