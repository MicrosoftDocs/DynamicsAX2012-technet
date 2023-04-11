---
title: Modify registrations before or after approval
TOCTitle: Modify registrations before or after approval
ms:assetid: c72cde49-5e7b-4b19-be43-c00a4941d7cc
ms:mtpsurl: https://technet.microsoft.com/library/Aa550851(v=AX.60)
ms:contentKeyID: 39519314
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- absence
- pay agreement
- override
audience: Application User
ms.search.region: Global
---

# Modify registrations before or after approval 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can change worker registrations during the approval process. Click **Human resources** \> **Common** \> **Time and attendance** \> **Approve**.

Examples of changes include the following:

  - Edit an absence registration.

  - Apply changes to a pay agreement by overriding the standard pay agreement for the worker.

  - Add premium lines, such as mileage, to worker registrations.

  - Allocate overtime to specific jobs.


> [!NOTE]
> <P>You can make additional changes during the calculation process. For more information, see <A href="modify-registrations-before-or-after-calculation.md">Modify registrations before or after calculation</A>.</P>



## Change an absence registration

1.  In the **Approve** form, select the worker, and then click the **Absence** tab.

2.  Enter the changes for the absence registration.
    

    > [!NOTE]
    > <P>Only the <STRONG>Absence job</STRONG> and <STRONG>Pay units</STRONG> fields can be edited during approval.</P>



## Override a pay agreement

You can override the pay agreement for a specific worker to generate the correct pay for the day.

1.  In the **Approve** form, select the worker.

2.  Click **Override**, and then select **Override pay agreement**.

3.  Click **Retrieve pay agreement**.

4.  Enter the changes to the pay agreement lines for the day.

## Add manual premium lines

1.  In the **Approve** form, select the worker, and then click **Premium lines**.

2.  Press CTRL+N to create a new premium line.

3.  In the **Premiums** field, select the premium to add.

4.  In the **Price** field, enter the number of units to add.

5.  In the **Price** field, enter the price of the unit to add.

6.  In the **Transaction ID** field, select the cost to be assigned to a specific job.

## Allocate overtime

Overtime can be allocated to the relevant jobs performed during the work day.

1.  In the **Approve** form, select the worker.

2.  Click **Overtime allocation**.

3.  In the **Percent** box, enter a percentage for each job.


> [!NOTE]
> <P>Total allocation for a work day must always be 100 percent.</P>



## See also

[About calculating, approving and transferring registrations](about-calculating-approving-and-transferring-registrations.md)

[Calculate time and attendance for workers](calculate-time-and-attendance-for-workers.md)

[Approve time and attendance registrations](approve-time-and-attendance-registrations.md)

  


