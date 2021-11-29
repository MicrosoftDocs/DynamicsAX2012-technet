---
title: Set up and apply piecework in production
TOCTitle: Set up and apply piecework in production
ms:assetid: 60a3075b-2e62-4bf2-aecb-3af36434fba8
ms:mtpsurl: https://technet.microsoft.com/library/Aa571121(v=AX.60)
ms:contentKeyID: 36057634
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up and apply piecework in production 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Time and attendance contains functionality for applying piecework to production jobs. The piecework setup enables workers to make registrations on piecework production jobs in the **Job registration** form for manufacturing execution.


> [!NOTE]
> <P>You can use the piecework functionality only if your organization also uses time and attendance payroll.</P>



## Set up piecework groups

1.  Click **Human resources** \> **Setup** \> **Time and attendance** \> **Payroll** \> **Piecework groups**.

2.  Press CTRL+N to create a group.

3.  Enter a unique identification and a description.

4.  Click the **Members** button.

5.  In the **Piecework** form, select a worker in the **Worker** field. The name of the worker is displayed in the **Name** field.

6.  Press CTRL+N to create a line.

7.  Repeat steps 5 and 6 until you have added all the relevant workers to the group.

## Set up piecework

1.  Click **Human resources** \> **Setup** \> **Time and attendance** \> **Payroll** \> **Piecework**.

2.  Press CTRL+N to create a piecework setup.

3.  In the upper pane, in the **Piecework** field, enter a unique identification.

4.  In the **Description** field, enter a description.

5.  On the **General** tab, specify the piecework setup:
    
    1.  In the **Piecework code** field, select if one worker, a group, or all workers are included in this piecework:
        
          - **Table** – Apply the code to a specific worker.
        
          - **Group** – Apply the code to a group of workers.
        
          - **All** – Apply the code to all workers.
    
    2.  In the **Piecework relation** field, select the relevant group or worker.
    
    3.  In the **Rate** field, enter the rate to be paid if the estimated number of items is produced in the estimated time. If items are produced faster than estimated, the rate will increase, and pay will be calculated proportionally.
        

        > [!NOTE]
        > <P>The increase in pay if items are produced faster than planned is determined by the <STRONG>Basic version</STRONG> selection in the <STRONG>Piecework rate formula</STRONG> field in the <STRONG>General</STRONG> area of the <STRONG>Production parameters</STRONG> form. Click <STRONG>Production control</STRONG> &gt; <STRONG>Setup</STRONG> &gt; <STRONG>Manufacturing execution</STRONG> &gt; <STRONG>Production parameters</STRONG>.</P>

    
    4.  In the **Pay type** field, select the pay type that will be paid as a minimum. The calculated rate will also be paid based on this pay type when payroll transactions are generated.

6.  In the lower pane, select specific production jobs or operations to be included in the piecework.


> [!NOTE]
> <P>If you use piecework only for some production jobs, select the <STRONG>Specify production order</STRONG> check box in the <STRONG>General</STRONG> area of the <STRONG>Production parameters</STRONG> form. Click <STRONG>Production control</STRONG> &gt; <STRONG>Setup</STRONG> &gt; <STRONG>Manufacturing execution</STRONG> &gt; <STRONG>Production parameters</STRONG>.</P>



## Set up the production order for piecework

Piecework pay is calculated only if production processes are set up for piecework. Before you start setting up piecework, you first have to apply the piecework rate calculation to the production orders or operations that you want to include in the piecework setup.

## Apply piecework to an operation on a production order

1.  Click **Production control** \> **Common** \> **Production orders** \> **All production orders**.

2.  Select the production order.

3.  On the Action Pane, on the **Production order** tab, click **Production details** \> **Route**.

4.  Select the operation and then click the **General** tab.

5.  Select **Piecework rate** in the **Hourly rate / piecework rate** field.
    

    > [!IMPORTANT]
    > <P>This field must be set before you perform scheduling on the production order.</P>



## Apply piecework to a route

If piecework should be applied to the same operation every time, you must update the route setup.

1.  Click **Production control** \> **Common** \> **Routes** \> **All routes**.

2.  Select the **Route number**.

3.  On the Action Pane, click the **Route** button.

4.  Select the appropriate operation, and then select **Piecework rate** in the **Hourly rate / piecework rate** field.

## Stop piecework

Follow these steps to stop using the piecework setup for the selected production jobs or operations.

1.  Click **Human resources** \> **Setup** \> **Time and attendance** \> **Payroll** \> **Piecework**.

2.  In the upper pane, select the piecework setup to stop.

3.  Select the **Closed** check box and then click **Close**.

## Pay agreements and piecework

Piecework pay does not require a special piecework pay agreement, but you might have to correct existing pay agreement lines for hourly pay if the piecework pay replaces the hourly pay.

Click **Human resources** \> **Setup** \> **Time and attendance** \> **Payroll** \> **Pay agreements**. Click **Pay agreement lines**. The **Hourly rate / piecework rate** field determines how piecework pay is applied:

  - **All** – Piecework pay is added to the hourly pay as a bonus.

  - **Hourly rate** – Only hourly pay is generated.

  - **Piecework rate** – Only piecework pay is generated.


> [!NOTE]
> <P>The default selection for new pay agreement lines is <STRONG>All</STRONG>.</P>



## Piecework transactions

The payroll transactions that are generated from piecework are posted with **Piecework** as the wage type.

## See also

[About payroll in Time and attendance](about-payroll-in-time-and-attendance.md)

[About working with routes in production](about-working-with-routes-in-production.md)

[Key tasks: Work with production jobs in Manufacturing execution](key-tasks-work-with-production-jobs-in-manufacturing-execution.md)

  


