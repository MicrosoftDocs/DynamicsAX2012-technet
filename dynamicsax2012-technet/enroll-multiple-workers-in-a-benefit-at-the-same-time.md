---
title: Enroll multiple workers in a benefit at the same time
TOCTitle: Enroll multiple workers in a benefit at the same time
ms:assetid: c2768749-3a9b-4cdf-a4b4-e5393334b681
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242834(v=AX.60)
ms:contentKeyID: 36059280
ms.date: 11/14/2014
mtps_version: v=AX.60
f1_keywords:
- benefits
- mass enrollment
- benefit
- benefit enrollment
- benefit enrollments
- mass benefit enrollment
- mass enrollments
- mass benefit enrollments
---

# Enroll multiple workers in a benefit at the same time [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can select multiple workers and enroll them in a benefit at the same time.


> [!NOTE]
> <UL>
> <LI>
> <P>The benefit plan must be set up before you can enroll workers in it. For more information, see <A href="set-up-benefits.md">Set up benefits</A>.</P>
> <LI>
> <P>If Microsoft Dynamics AX 2012 R2 or AX 2012 R3 is installed, the worker’s eligibility for a benefit must be determined before you can enroll the worker. For more information, see <A href="key-tasks-determine-benefit-eligibility.md">Key tasks: Determine benefit eligibility</A>.</P>
> <LI>
> <P>If the <STRONG>Payroll - USA</STRONG> configuration key is selected, many benefits affect payroll calculations. They require deductions and contributions to be determined for each worker who is enrolled in the benefit. After you enroll a worker in a benefit that affects payroll calculations, see <A href="worker-and-position-payroll-tasks.md">Worker and position payroll tasks</A> to set up payroll information for the worker.</P>
> <P>To enroll a worker in a garnishment or tax levy, see <A href="garnishment-and-tax-levy-enrollment-tasks.md">Garnishment and tax levy enrollment tasks</A>.</P></LI></UL>



1.  Click **Human resources** \> **Common** \> **Workers** \> **Workers**.

2.  Select the workers to enroll in the new benefit.

3.  In the **Personnel actions** group, select **Mass benefit enrollment**.

4.  In the **Benefit** field, select the plan and option.

5.  If you are using a version that was released before Microsoft Dynamics AX 2012 R2, do the following:
    
      - In the **Worker enrollment start date** field, enter the first day that the benefit is available to the workers that you selected.
    
      - In the **Worker enrollment end date** field, enter the last day that the benefit is available to the workers that you selected.

6.  If you are using Microsoft Dynamics AX 2012 R2 or AX 2012 R3, do the following:
    
      - In the **Coverage start date** field, enter the first day that the benefit is available to the workers that you selected.
    
      - In the **Coverage end date** field, enter the last day that the benefit is available to the workers that you selected.

7.  Click **Enroll**.

## See also

[Mass benefit enrollment (form)](https://technet.microsoft.com/en-us/library/hh209571\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

