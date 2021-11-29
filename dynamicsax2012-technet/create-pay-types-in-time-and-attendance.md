---
title: Create pay types in time and attendance
TOCTitle: Create pay types in time and attendance
ms:assetid: 6d3dd6ef-4f1e-464b-b76f-29ebf56574e6
ms:mtpsurl: https://technet.microsoft.com/library/Aa571208(v=AX.60)
ms:contentKeyID: 36058021
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create pay types in time and attendance 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Pay types are used in pay agreements to calculate different kinds of pay for workers, based on their time and attendance registrations.

Rates for pay types are set up for specific time intervals, and individual rates can be created for workers.


> [!NOTE]
> <P>It is not always necessary to create rates for pay types in time and attendance. This information may already exist in the payroll system that is used to generate wages.</P>



## Create a new pay type

1.  Click **Human resources** \> **Setup** \> **Time and attendance** \> **Payroll** \> **Pay types**.

2.  Press CTRL+N, or click **New** to create a new line.

3.  Insert an identification of the pay type in the **Pay type** field.

4.  Insert a description of the pay type in the **Description** field.

5.  If the rate is calculated based on an existing pay type, select the reference pay type in the **Reference** field.

6.  To create rates for the pay type, click **Rates**.

7.  Press CTRL+N to create a new rate.

8.  In the **From date** and **To date** fields, insert the date interval when the rate is valid.

9.  Insert a rate in the **Rate** field, or, if you selected a reference in step 5, insert the percentage of that pay type that must be used in the **Percent** field.

## Create an individual rate for a worker

1.  Click **Human resources** \> **Setup** \> **Time and attendance** \> **Payroll** \> **Pay types**.

2.  Select the pay type to create an individual rate for.

3.  Click **Rates**.

4.  In the **From date** and **To date** fields, insert the date interval when the rate is valid.

5.  Click **Worker rates**.

6.  Press CTRL+N to create a new line.

7.  Insert a rate in the **Rate** field, or, if a reference pay type is used, insert the percentage of that pay type that must be used in the **Percent** field.

8.  Select a worker in the **Worker** field.


> [!NOTE]
> <P>A pay type for a specific worker can only contain a percentage factor if the pay type, for which the worker-specific rate is created, has a <STRONG>Reference</STRONG> pay type.</P>



## Create a new rate period for an existing pay type

1.  Click **Human resources** \> **Setup** \> **Time and attendance** \> **Payroll** \> **Pay types**.

2.  Select the pay type to create a new rate period for.

3.  Click **Rates**.

4.  Select the rate, and then click **Change pay**.

5.  Select a new date interval in the **From date** and **To date** fields.

6.  If relevant, select a method for increasing the pay rate in the **Pay raise method** field:
    
      - **Rate raise** – Raise the pay rate or percentage by using the amount entered in the **Value** field.
    
      - **Percentage raise** – Raise the pay rate by using the percentage entered in the **Value** field.
    
      - **New rate** – Use the amount entered in the **Value** field as the new pay rate.

7.  Insert the number or amount with which to raise the rate in the **Value** field.


> [!NOTE]
> <P>If you previously created worker-specific rates for the rate that you creating a new period for, the new or raised rate will automatically be reflected in the worker-specific rates, and they will be raised accordingly.</P>



## See also

[About payroll in Time and attendance](about-payroll-in-time-and-attendance.md)

[Pay types (form)](https://technet.microsoft.com/library/aa598661\(v=ax.60\))

  


