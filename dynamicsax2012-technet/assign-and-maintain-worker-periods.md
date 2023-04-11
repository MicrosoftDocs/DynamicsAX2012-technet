---
title: Assign and maintain worker periods
TOCTitle: Assign and maintain worker periods
ms:assetid: 572dff8b-1445-4d75-a7a5-9fb3912722d6
ms:mtpsurl: https://technet.microsoft.com/library/Aa549057(v=AX.60)
ms:contentKeyID: 36057328
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- period code
- employee periods
- generate periods
- maintain periods
audience: Application User
ms.search.region: Global
---

# Assign and maintain worker periods 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Workers are associated with a period based on the pay and time reporting schedule that they follow.

## Assign a period code to a worker

1.  Click **Human resources** \> **Common** \> **Workers** \> **Workers**.

2.  On the **Action Pane**, on the **Project management** tab, in the **Set up** group, click **Project setup**.

3.  In the **Project setup** – **Worker** form, in the **Period code** field, select a worker-related period type.

## Update worker period definitions

Use the **Update worker periods** form to automatically update period definitions for all workers who are associated with the period.

1.  Click **Organization administration** \> **Common** \> **Calendars** \> **Period types**.

2.  Select the period type that you want to update, and then click the **Update worker periods** button.

3.  In the **Update worker periods** form, specify a start and end date for the period.

4.  Optional: Specify the norm hours for utilization reporting. These are the expected billable and efficiency hours for the worker during a period.

## Generate periods for period types

Use the **Generate periods** form to generate periods for a new period type, or to create a new period interval for an existing period type.

1.  Click **Organization administration** \> **Common** \> **Calendars** \> **Period types**.

2.  Select the period type that you want to update, and then click the **Generate periods** button.

3.  In the **Generate periods** form, select the **Update worker periods** check box.

4.  Click **OK**.

If a period type is revised, the change affects all workers that are associated with the period type.

## Split a period

Split periods are periods that span two calendar units of time, such as two months or two weeks. When you split a period, a new period is created. The original period includes the days in the first calendar unit and the new period includes the days in the second calendar unit.

1.  Click **Organization administration** \> **Common** \> **Calendars** \> **Period types**.

2.  Select a period, and then click the **Periods** button.

3.  In the **Period transactions** form, select a period, and then click **Split period**.

4.  Change the date in the **Split on date** field as required. The split date becomes the last day of the original calendar unit.

## View worker period status

1.  Click **Organization administration** \> **Common** \> **Calendars** \> **Period types**.

2.  Select a period, and then click **Periods**.

3.  In the **Period transactions** form, select a period, and then click **Period status**.

4.  In the **Period status** form, select a worker on the **Overview** tab to view the period utilization calculations for the worker on the **Utilization** tab.

You can also open the **Period status** form in **Human resources**. Click **Human resources** \> **Common** \> **Workers** \> **Workers**. On the **Action Pane**, on the **Project management** tab, in the **View** group, click **Period status**.

## See also

[About project periods](about-project-periods.md)

[Generate timesheet periods](generate-timesheet-periods.md)

  


