---
title: Enable workers to register time and attendance
TOCTitle: Enable workers to register time and attendance
ms:assetid: 1c38b67b-09a3-4dbe-9603-3cd558bdbb02
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa569936(v=AX.60)
ms:contentKeyID: 36056133
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Enable workers to register time and attendance 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you can activate a worker as a time registration worker in **Time and attendance**, you must create a record for the worker in **Human resources**. You can only activate a worker as a time registration worker in the company that the worker is employed in. For more information, see [Workers](workers.md).

## Activate worker as time registration worker

1.  Click **Human resources** \> **Common** \> **Workers** \> **Workers**.

2.  On the **Workers** list page, select the worker.

3.  On the **Time registration** tab, click **Activate on registration terminals** to open the **Create time registration worker** form.  
    

    > [!NOTE]
    > <P>The <STRONG>Activate on registration terminals</STRONG> button is available only if you are working in the company that the worker is employed in.</P>



4.  The **Active** check box is selected by default. This indicates that the worker has been activated as a time registration worker.

5.  In the **Activation date** field, select a date.

6.  In the **Calculation group** field, select the group of workers that the worker's registrations are calculated with. A shop supervisor or manager is responsible for calculating registrations for this group of workers.

7.  If the worker is responsible for calculating registrations for other workers, select a calculation group in the **Default calculation group** field. When the worker opens the **Calculate** form, this calculation group is displayed.

8.  In the **Approval group** field, select the group of workers that the worker's registrations are approved with. A shop supervisor or manager is responsible for approving registrations for this group of workers.

9.  In the **Standard profile** field, select the work time profile that is used to calculate time and pay if the worker makes no registrations during a work day.

10. In the **Pay agreement** field, select the pay agreement that is used when the worker's pay is calculated.

11. In the **Period code** field, select the pay period that is used when the worker's pay is calculated.

12. In the **Profile group** field, select the group that the worker belongs to. Profile groups contain one or more work time profiles that can be applied when a worker makes clock-in and clock-out registrations. The profile that you select depends on the date or the time of day that the worker makes a clock-in registration. For example, the worker may work during a day shift or a night shift. For more information, see [Set up profile groups for time and attendance registrations](set-up-profile-groups-for-time-and-attendance-registrations.md).

13. Select the **New bundle** check box to stop the worker's active jobs when he or she starts a new job. If you clear the check box, new jobs are bundled with the jobs that the worker previously started, but that have not yet been stopped or completed. The **New bundle** check box relates to job bundling. If you use job bundling, a worker can start multiple jobs at the same time in the **Job registration** form in **Production control**. If multiple jobs are started at the same time, but they are not completed at the same time, the job bundling functionality calculates the time that is spent on each job. For more information about job bundling, see [About allocation keys](about-allocation-keys.md).

14. In the **Category** field, select the cost category that is used when the worker makes registrations for projects and project activities.

15. Select the **Use timecard** check box to allow the worker to make registrations on the electronic timecard in **Time and attendance**.

16. In the **Configuration** field, select the registration form that is displayed when the worker logs on to the **Job registration** form in **Production control**.

17. Select the **Flex allowed** check box to allow the worker to register flextime.

18. If the worker is allowed to register flextime, select a flex group in the **Flex group ID** field.

## Update data for a time registration worker

Use this procedure to update data for a worker who has been activated as a time registration worker.

1.  Click **Human resources** \> **Common** \> **Workers** \> **Time registration workers**.

2.  Select the worker, and then click the **Time registration** tab.

3.  Make the necessary changes. For information about the fields that are used to activate a time registration worker, see the previous procedure. In addition, the tab contains the following fields:
    
      - If personal identification numbers (PINs) are used as worker identification, enter the worker's PIN in the **Password** field.
    
      - If you use an external payroll system, enter the worker's pay ID in the **Pay ID** field.
    
      - If the worker uses a badge to make registrations, enter the badge ID in the **Badge ID** field. Then enter the version of the badge in the **Badge version** field.
    
      - If the worker is a shop supervisor, select the **Supervisor options** check box. You also select the check box if the worker is not a shop supervisor, but special tasks have been assigned that require the worker to handle jobs. These tasks are usually performed by a shop supervisor. When the worker logs on to the **Job registration** form after you select this check box, the **Select resource and action** form contains additional options.
    
      - If the worker is responsible for calculating registrations for other workers, select a calculation group in the **Default calculation group** field. When the worker opens the **Calculate** form, this calculation group is displayed.
    
      - If seniority is calculated for employees, select the date that seniority is calculated from in the **Seniority date** field.


> [!NOTE]
> <P>If the worker is allowed to register flextime, the fields in the <STRONG>Flextime</STRONG> section display information and balances for flextime.</P>



## See also

[About time registration workers](about-time-registration-workers.md)

[Workers](workers.md)

[Key tasks: Work with production jobs in Manufacturing execution](key-tasks-work-with-production-jobs-in-manufacturing-execution.md)

  


