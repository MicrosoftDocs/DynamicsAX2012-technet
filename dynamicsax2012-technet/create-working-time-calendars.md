---
title: Create working time calendars
TOCTitle: Create working time calendars
ms:assetid: b11e7433-30a7-407c-84b7-653ff9047368
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa498646(v=AX.60)
ms:contentKeyID: 43976724
ms.date: 12/05/2014
mtps_version: v=AX.60
f1_keywords:
- payroll
- schedule
- capacity
- calendar
- hours
- working time
- calendars
- work week
- working times
audience: Application User
ms.search.region: Global
---

# Create working time calendars 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Working time calendars define the capacity that is available for an operations resource or resource group on specific days and at specific times. You can create an overall calendar for your production, several calendars for resources that operate at different times or shifts, or a separate calendar for each operations resource or resource group.

Working time calendars also define schedules that can be used to generate earnings and pay. This function is available only if the **Payroll - USA** configuration key is selected.

If you must create more than one working time calendar, it is useful to create a standard base calendar first. Then, to create additional working time calendars, copy the base calendar, and change the relevant times to reflect the changes in working times.

## Create a calendar and working times

1.  Click **Organization administration** \> **Common** \> **Calendars** \> **Calendars**.

2.  On the toolbar, click **New** to create a new line.

3.  In the **Calendar** field, enter a unique identifier of up to ten characters.

4.  In the **Name** field, enter a descriptive name.

5.  Optional: In the **Base calendar** field, select the base calendar that the new calendar is based on.

6.  Click **Working times**, and then click **Compose working times** to create or update working times for the calendar.

7.  In the **Calendar** field, select the name of the calendar to compose working times for.

8.  In the **From date** field, enter the first date to compose working times for. By default, the field contains the current date.

9.  In the **To date** field, enter the last date to compose working times for. By default, the field contains a date that is one year from the current date.

10. If you want to create the calendar from a base calendar, select the **Use base calendar** check box.

11. In the **Working time template** field, select the appropriate template.

12. Click **OK**.

## Copy working times from another calendar

1.  Click **Organization administration** \> **Common** \> **Calendars** \> **Calendars**.

2.  On the toolbar, click **New** to create a new line.

3.  In the **Calendar** field, enter a unique identifier of up to ten characters.

4.  On the toolbar, click **Copy calendar**.

5.  In the **From calendar** field, select the calendar to copy.

6.  In the **To calendar** field, select the calendar to copy the original calendar to.

7.  Optional: If you also want to copy properties, select the **Copy property** check box.

8.  Optional: If you also want to copy the Closed for pickup settings, select the **Copy Closed for pickup** check box.

9.  Click **OK** to save the calendar and close the form.

## See also

[Create working time templates](create-working-time-templates.md)

[Set up properties for operations resources](set-up-properties-for-operations-resources.md)

  


