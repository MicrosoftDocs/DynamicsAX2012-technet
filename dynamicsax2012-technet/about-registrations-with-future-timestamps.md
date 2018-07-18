---
title: About registrations with future timestamps
TOCTitle: About registrations with future timestamps
ms:assetid: 25e387e5-8ffb-4246-bce0-46cd550c35e4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa496820(v=AX.60)
ms:contentKeyID: 43976707
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- future
- JmgTermReg
- missing clock-out
- archive
audience: Application User
ms.search.region: Global
---

# About registrations with future timestamps 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When workers clock in and clock out, Microsoft Dynamics AX checks the registration table for the most recent clock-in or clock-out registration. If the most recent registration is a clock-out, the application clocks in the worker. If the most recent registration is a clock-in, the application clocks out the worker.

When registrations are calculated, a supervisor or team leader may mistakenly create a clock-in or clock-out registration that has a future timestamp. This is accomplished by using the missing clock-out feature. For more information, see [About adding clock-out registrations](about-adding-clock-out-registrations.md).

**Example**

On a Tuesday, a supervisor mistakenly registers a clock-out time for Wednesday at 16:00 for a worker by using the **Missing clock-out** function. When the worker clocks in Wednesday morning at 08:00, he or she receives a clock-in message, which is correct. However, when the worker attempts to clock out at 16:05, Microsoft Dynamics AX acknowledges the registration as a clock-in, because the worker already has a clock-out registration for Wednesday at 16:00.

To prevent the problems that these types of registrations can cause, you can remove faulty registrations that contain future timestamps from the registration table.

## Remove registrations that have timestamps set for the future

1.  Click **Production control** \> **Periodic** \> **Clean up** \> **Archive future registrations**.
    
    –or–
    
    Click **Human resources** \> **Periodic** \> **Time and attendance** \> **Update** \> **Archive future registrations**.

2.  Click **OK**.


> [!NOTE]
> <P>You can set up this task to run regularly as a batch job, such as one time every 24 hours. For more information, see <A href="submit-a-batch-processing-job-from-a-form.md">Submit a batch processing job from a form</A>.</P>



## See also

[About time and attendance registrations](about-time-and-attendance-registrations.md)

[About registration for manufacturing execution](about-registration-for-manufacturing-execution.md)

  


