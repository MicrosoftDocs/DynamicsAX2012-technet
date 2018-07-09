---
title: Setting up time and attendance
TOCTitle: Setting up time and attendance
ms:assetid: 441b0386-ff33-4ab1-897a-d5a941a44192
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa496971(v=AX.60)
ms:contentKeyID: 36056884
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- implementation
- registration
- dimension
- registering
- time and attendance
---

# Setting up time and attendance [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you set up **Time and attendance**, follow these steps in the sequential order. Some steps may not be relevant, depending on the **Time and attendance** functionality that your company uses. You may have to repeat some of the tasks during the setup process.

1.  Click **Human resources** \> **Setup** \> **Time and attendance** \> **Wizards** \> **Time and attendance configuration wizard**.

2.  Set up various parameters:  
    
    1.  Click **Human resources** \> **Setup** \> **Time and attendance** \> **Time and attendance parameters**.
    
    2.  Click **Human resources** \> **Setup** \> **Time and attendance** \> **Calculation parameters**.   

3.  If you want to use **Manufacturing execution** features together with **Time and attendance**, you must set up integration with production:
    
    1.  Click **Production control** \> **Setup** \> **Production** \> **Allocation keys**.
    
    2.  Click **Production control** \> **Setup** \> **Manufacturing execution** \> **Production parameters**.   

4.  Set up various kinds of groups. For more information, see [About registration groups for time and attendance](about-registration-groups-for-time-and-attendance.md). The following path shows how to access set up forms for groups: **Time and attendance** \> **Setup** \> **Groups**.  
    
    1.  Absence groups and related absence codes are used when workers make absence registrations.
    
    2.  Calculation groups are used to divide workers into groups, for example, teams that have the same supervisor or manager. Calculation groups are used when supervisors or managers calculate workers’ registrations.
    
    3.  Approval groups are used to divide workers into groups. They are used when managers or payroll officers approve workers’ registrations.
    
    4.  Flex groups are used to divide workers into groups in companies where workers can work flexible hours.  

5.  Click **Human resources** \> **Setup** \> **Time and attendance** \> **Indirect activity categories**. For information, see [About indirect activities for time and attendance](about-indirect-activities-for-time-and-attendance.md).

6.  Click **Human resources** \> **Setup** \> **Time and attendance** \> **Time profiles** \> **Profiles**. For information, see [About profiles for time and attendance registrations](about-profiles-for-time-and-attendance-registrations.md).

7.  Set up payroll in **Time and attendance** \> **Setup** \> **Payroll**. For information about payroll, see [About payroll in Time and attendance](about-payroll-in-time-and-attendance.md).

8.  Configure registration forms to comply with company requirements in Click **Human resources** \> **Setup** \> **Time and attendance** \> **Terminals** \> **Configure registration forms**.

9.  Set up the terminals that will be used to make registrations in Click **Human resources** \> **Setup** \> **Time and attendance** \> **Terminals** \> **Terminals**.

10. Set up the workers who can register time in Click **Human resources** \> **Common** \> **Workers** \> **Time registration workers**.. For information, see [About time registration workers](about-time-registration-workers.md).

## See also

[About parameters for calculations](about-parameters-for-calculations.md)

[About time and attendance registrations](about-time-and-attendance-registrations.md)

[About registration for manufacturing execution](about-registration-for-manufacturing-execution.md)

[Key tasks: Set up manufacturing execution](key-tasks-set-up-manufacturing-execution.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

