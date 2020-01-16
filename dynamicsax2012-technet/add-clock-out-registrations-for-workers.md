---
title: Add clock-out registrations for workers
TOCTitle: Add clock-out registrations for workers
ms:assetid: 168c76cf-94b2-4c7d-bfcf-ee43044e435e
ms:mtpsurl: https://technet.microsoft.com/library/Aa569892(v=AX.60)
ms:contentKeyID: 39519055
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Add clock-out registrations for workers 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A supervisor or manager can insert missing clock-out registrations for workers who forgot to make those registrations. Missing clock-out registrations can be inserted by running a batch job for a group of workers, or for one worker at a time.


> [!NOTE]
> <P>It is also possible to make clock-in registrations for workers, but it is more likely that a missing registration form a worker is a clock-out registration.</P>



## Clock out a worker

1.  Click **Human resources** \> **Common** \> **Time and attendance** \> **Calculate**.

2.  Select the worker, and then click **Clock-in and out** \> **Missing clock-out**.

3.  In the **Clock out** section, insert the **Date** and **Time** for the clock-out registration.

4.  To create a clock out registration record in the raw registrations table, select the **Create lines** check box.

## Clock out a group of workers

1.  Click **Human resources** \> **Common** \> **Time and attendance** \> **Approve**.

2.  Click **Clock-in and out** \> **Clock out workers**.
    
      - If you want to clock out all the workers in the selected calculation group or approval group, enter the profile date for the clock-out registration and then click **OK**.
    
      - If you want to clock out specific workers, click **Select** and then select the relevant workers.
    
      - If you want to set up the clock-out registration as a batch job, select the **Batch** tab, and create the batch job.


> [!NOTE]
> <P>You can also clock out workers by setting up a batch job. Click <STRONG>Human resources</STRONG> &gt; <STRONG>Periodic</STRONG> &gt; <STRONG>Time and attendance</STRONG> &gt; <STRONG>Clock out workers</STRONG>.</P>



## See also

[About adding clock-out registrations](about-adding-clock-out-registrations.md)

[Submit a batch processing job from a form](submit-a-batch-processing-job-from-a-form.md)

  


