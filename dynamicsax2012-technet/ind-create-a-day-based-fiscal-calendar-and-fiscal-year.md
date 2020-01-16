---
title: (IND) Create a day-based fiscal calendar and fiscal year
TOCTitle: (IND) Create a day-based fiscal calendar and fiscal year
ms:assetid: 79f75b05-fe04-4cb9-9e85-029d6fd158c0
ms:mtpsurl: https://technet.microsoft.com/library/JJ677949(v=AX.60)
ms:contentKeyID: 49385913
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- year
- calendar
- (IND)
- india
- fiscal
- fiscal calendars
- fiscal years
audience: Application User
ms.search.region: India
---

# (IND) Create a day-based fiscal calendar and fiscal year 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Follow these steps to create a day-based fiscal calendar that includes one fiscal year. You can add other fiscal years later. For more information, see [Key tasks: Fiscal calendars, fiscal years, and periods](key-tasks-fiscal-calendars-fiscal-years-and-periods.md).

You should use a day-based fiscal calendar if you calculate fixed asset depreciation by using either the straight line percentage method or the reducing balance method.


> [!IMPORTANT]
> <P>When you create a fiscal year, the periods are automatically created, based on the length of the period and the number of period units that you specify. To modify the periods after the fiscal year is created, you must divide a period.</P>



1.  Click **General ledger** \> **Setup** \> **Fiscal calendars**.

2.  Click **New fiscal calendar**.

3.  Enter a name for the fiscal calendar, such as Day-based, and enter a description.

4.  In the **Calendar type** field, select **Day based**.

5.  Enter the starting and ending dates for the first fiscal year to add to the fiscal calendar. The default dates are January 1 and December 31. You can also create a fiscal year that starts in one calendar year and ends in another calendar year.
    

    > [!NOTE]
    > <P>If you add a fiscal year later, that fiscal year must start on the day after the previous fiscal year ended. For example, you create a fiscal year, 2012-13, that starts on July 1, 2012, and ends on June 30, 2013. The next fiscal year that you create must start on July 1, 2013.</P>



6.  Enter the length of the periods in the new fiscal year, and select the unit for the periods.
    
    For example, you enter a period length of 1, and you select **Months** in the **Unit** field. The fiscal year will include 12 periods, each being one month long. A period length of 2 and a unit of **Months** will create a fiscal year that has six two-month periods.

7.  Verify that the information is correct, and then click **Create**.

8.  In the **Fiscal calendars** form, in the **Days** field, enter the number of days for each period. This is also the number of days for which fixed asset depreciation will be calculated.

  


