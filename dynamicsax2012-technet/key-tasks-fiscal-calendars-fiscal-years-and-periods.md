---
title: 'Key tasks: Fiscal calendars, fiscal years, and periods'
TOCTitle: 'Key tasks: Fiscal calendars, fiscal years, and periods'
ms:assetid: 149a5222-97df-404f-be70-c1ade1daf663
ms:mtpsurl: https://technet.microsoft.com/library/Hh242146(v=AX.60)
ms:contentKeyID: 36056056
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- fiscal calendar
- period
- access level
- closing period
- fiscal year
- Ledger calendar
- module access level
- on hold
- period status
audience: Application User
ms.search.region: Global
---

# Key tasks: Fiscal calendars, fiscal years, and periods 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Fiscal calendars contain fiscal years, and fiscal years contain periods. A fiscal calendar is a grouping of one or more fiscal years that is used for financial activity. You can create fiscal calendars that are independent of your legal entity and that can be selected and shared by multiple legal entities. You can use the **Fiscal calendars** form to create and delete fiscal calendars and fiscal years. You can also create and change the periods that are part of a fiscal year.


> [!NOTE]
> <P>A fiscal calendar must be selected in the <STRONG>Ledger</STRONG> form for every legal entity. After a fiscal calendar is selected, you can set up period statuses and permissions in the <STRONG>Ledger calendar</STRONG> form for any of the periods that are part of a fiscal year. For more information about how to select fiscal calendars for legal entities, see <A href="select-a-fiscal-calendar-for-a-ledger.md">Select a fiscal calendar for a ledger</A>. For more information about how to set up period statuses and permissions, see <A href="about-fiscal-calendars-fiscal-years-and-periods.md">About fiscal calendars, fiscal years, and periods</A> and <A href="specify-which-users-can-post-to-a-period.md">Specify which users can post to a period</A>.</P>



## What do you want to do?

Learn more about...

Create a fiscal calendar and fiscal year

Add a fiscal year to an existing fiscal calendar

Create a closing period

Divide a period

Delete a fiscal year

Delete a fiscal calendar

Delete a period

Find form help

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About fiscal calendars, fiscal years, and periods](about-fiscal-calendars-fiscal-years-and-periods.md)

[Select a fiscal calendar for a ledger](select-a-fiscal-calendar-for-a-ledger.md)

[Specify which users can post to a period](specify-which-users-can-post-to-a-period.md)

## Create a fiscal calendar and fiscal year

Follow these steps to create a fiscal calendar that includes one fiscal year. You can add other fiscal years later.


> [!IMPORTANT]
> <P>When you create a fiscal year, the periods are automatically created, based on the length of the period unit and the number of period units that you specify. To create a period after the fiscal year is created, you must divide a period.</P>



1.  Click **General ledger** \> **Setup** \> **Fiscal calendars**.

2.  Click **New fiscal calendar**.

3.  Enter a name for the fiscal calendar, such as Standard, JanuaryToDecember, or CalendarYear, and enter a description.

4.  Enter the starting and ending dates for the first fiscal year that will be added to the fiscal calendar. The default dates are January 1 and December 31. You can also create a fiscal year that starts in one calendar year and ends in another calendar year.
    

    > [!IMPORTANT]
    > <P>If you add a fiscal year later, that fiscal year must start on the day after the previous fiscal year ended. For example, you create a fiscal year of 2012-13 that starts on July 1, 2012, and ends on June 30, 2013. The next fiscal year that you create must start on July 1, 2013.</P>



5.  Enter the name of the fiscal year that you are creating.

6.  Enter the length of the period and select the unit for the periods in the new fiscal year.
    
    For example, you enter a period length of 1 and you select **Months** in the **Unit** field. The fiscal year will include 12 periods, each being one month long. A period length of 2 and a unit of **Months** will create a fiscal year that has six two-month periods.

7.  Verify that the information is correct, and then click **Create**.

Back to top

## Add a fiscal year to an existing fiscal calendar

You can add an unlimited number of fiscal years to a fiscal calendar that has already been created.

When a fiscal calendar includes multiple fiscal years, the starting and ending dates of the fiscal years cannot overlap. Also, you cannot have gaps between the ending date of one fiscal year and the starting date of the next fiscal year.

1.  Click **General ledger** \> **Setup** \> **Fiscal calendars**.

2.  In the left pane, select the fiscal calendar that you want to add a fiscal year to.

3.  Click **New fiscal year**.

4.  Enter an ending date for the new fiscal year. The starting date for the new fiscal year is the day after the ending date of the previous fiscal year. For example, the 2012-13 fiscal year starts on July 1, 2012, and ends on June 30, 2013. The new fiscal year of 2013-14 that you create starts on July 1, 2013. You cannot change the starting date.

5.  Enter the name of the fiscal year.

6.  Specify period information:
    
      - Select the **Copy from last fiscal year** check box to have this fiscal year use the same periods as the previous fiscal year in this fiscal calendar.
        

        > [!NOTE]
        > <P>Do not select this check box if either the previous fiscal year or the new fiscal year is a leap year. If you select this check box, any periods that include the month of February will not match the previous fiscal year.</P>

    
      - If you want the new fiscal year to have different periods than the previous fiscal year, enter the length of the period and select the unit for the periods in the new fiscal year. For example, you enter a period length of 1 and you select **Months** in the **Unit** field. This creates a fiscal year with 12 periods, each being one month long. A period length of 2 and a unit of **Months** will create a fiscal year that has six two-month periods.

7.  Click **Create**.

Back to top

## Create a closing period

A closing period is used to separate general ledger transactions that are generated when a fiscal year is closed. When the closing transactions are in one fiscal period, it is easier to create financial statements that either include or exclude different types of closing entries. If a fiscal year is divided into 12 fiscal periods, the closing period is usually the 13th period. However, a closing period can be created from any period that has a status of **Open**.

When you create a closing period, select a period that has a status of **Open** and that has the dates that you want to use. The new closing period will copy the starting and ending dates from the existing period. The original period will continue to exist. For example, you select Period 12, which is the last period in the fiscal year, and that has dates of August 1 through August 31. You enter a name for the closing period, such as Close. After you create the new closing period, you now have the original period and the closing period. Both have dates that start on August 1 and end on August 31.


> [!NOTE]
> <P>You can view the period status on the <STRONG>Periods</STRONG> tab in the <STRONG>Ledger calendar</STRONG> form. For more information, see <A href="https://technet.microsoft.com/library/hh242506(v=ax.60)">Ledger calendar (form)</A>.</P>



1.  Click **General ledger** \> **Setup** \> **Fiscal calendars**.

2.  In the left pane, select the fiscal calendar and fiscal year that you will add the closing period to.

3.  In the **Periods** grid, select the period with the dates that you want to use.

4.  Click **Create closing period**.

5.  Enter a name for the closing period. The name must be unique in the fiscal calendar and fiscal year.

6.  Click **Create**.

Back to top

## Divide a period

If a period has a status of **Open**, you can divide the period into two periods. You might want to do this if you have to change the dates for a period. When you divide a period, the original period is deleted, and the following two periods are created:

  - The first period uses the starting date and name of the original period. The ending date is one day before the starting date that you enter for the second period.

  - The second period uses the starting date that you enter in the **Period start** field. The ending date is the ending date of the original period.

For example, you want to divide Period 1, which starts on January 1 and ends on June 30. You want a second period, Period 2, which starts on April 1. After you divide Period 1, the following two periods exist:

  - Period 1 starts on January 1 and ends on March 31.

  - Period 2 starts on April 1 and ends on June 30.

<!-- end list -->

1.  Click **General ledger** \> **Setup** \> **Fiscal calendars**.

2.  In the left pane, select the fiscal calendar and fiscal year that includes the period to divide.

3.  In the **Periods** grid, select the period to divide.

4.  Click **Divide period**.

5.  Enter a starting date and a name for the second period. The name must be unique in the fiscal calendar and fiscal year.

6.  Click **Divide**.

Back to top

## Delete a fiscal year

You can delete fiscal years that are not needed or that were set up with incorrect information. When you delete a fiscal year, the periods in that fiscal year are also deleted. The following restrictions apply when you delete a fiscal year:

  - You must delete fiscal years in sequential order, starting with the fiscal year that was most recently created.

  - The fiscal year cannot be part of a budget cycle time span.

  - No periods in the fiscal year can include financial transactions.

  - The fiscal year cannot include source document lines that have not been journalized for the fiscal calendar that is assigned in the **Ledger** form.

<!-- end list -->

1.  Click **General ledger** \> **Setup** \> **Fiscal calendars**.

2.  In the left pane, select the fiscal year to delete.

3.  In the upper pane, click **Delete**.

Back to top

## Delete a fiscal calendar

When you delete a fiscal calendar, the fiscal years that are included in the fiscal calendar are also deleted. See the above restrictions in “Delete a fiscal year” for when a fiscal year can be deleted.

The following restrictions apply when you delete a fiscal calendar:

  - The fiscal calendar cannot be the selected fiscal calendar for the ledger in the **Ledger** form.

  - The fiscal calendar cannot be assigned to a budget cycle time span in the **Budget cycle time spans** form. For more information, see [Budget cycle time spans (form)](https://technet.microsoft.com/library/hh227604\(v=ax.60\)).

  - The fiscal calendar cannot be assigned to fixed asset depreciation books or value models in the **Depreciation books** or **Value models** forms. For more information, see [Value models setup (form)](https://technet.microsoft.com/library/aa582567\(v=ax.60\)) or [Depreciation books setup (form)](https://technet.microsoft.com/library/aa597721\(v=ax.60\)).

<!-- end list -->

1.  Click **General ledger** \> **Setup** \> **Fiscal calendars**.

2.  In the left pane, select the fiscal calendar to delete.

3.  In the upper pane, click **Delete**.

Back to top

## Delete a period

You can delete a period if it is not a closing period, and if it does not include financial transactions.

When you delete a period, the period is actually merged with the period immediately before it. For example, Period 2 is February 1 to February 28, and Period 3 is March 1 to March 31. If you delete Period 3, Period 2 becomes February 1 to March 31.

1.  Click **General ledger** \> **Setup** \> **Fiscal calendars**.

2.  In the left pane, select the fiscal calendar and fiscal year that includes the period to delete.

3.  In the **Periods** grid, select the period to delete.

4.  In the lower pane, click **Delete**.

Back to top

## Find form help

[Fiscal calendars (form)](https://technet.microsoft.com/library/hh209283\(v=ax.60\))

[Ledger (form)](https://technet.microsoft.com/library/hh209331\(v=ax.60\))

[Ledger calendar (form)](https://technet.microsoft.com/library/hh242506\(v=ax.60\))

  


