---
title: (IND) Set up a day-based calendar
TOCTitle: (IND) Set up a day-based calendar
ms:assetid: 8462b285-8939-45b0-aa5c-a501fa0fe4ba
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677977(v=AX.60)
ms:contentKeyID: 49385940
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (IND)
- India
- day-based calendar
- Set up a day-based calendar
- Set up calendar
audience: Application User
ms.search.region: India
---

# (IND) Set up a day-based calendar 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Fiscal calendars contain fiscal years, and fiscal years contain periods. A fiscal calendar is a group of one or more fiscal years that is used for financial activity. You can create fiscal calendars that are independent of your legal entity and that can be selected and shared by multiple legal entities. You can use the **Fiscal calendars** form to create and delete fiscal calendars and fiscal years. You can also create and change the periods that are part of a fiscal year.

Fixed assets depreciation must be calculated based on the actual number of days in the month. A day-based calendar must be set up to attach to the relevant fixed asset value model.

Follow these steps to create a day-based fiscal calendar that includes one fiscal year. You can add other fiscal years later.


> [!NOTE]
> <P>The <STRONG>Companies Act depreciation</STRONG> check box must be selected in the <STRONG>Fixed assets parameters</STRONG> form to create a day-based calendar.</P>



1.  Click **General ledger** \> **Setup** \> **Fiscal calendars**.

2.  Click **New fiscal calendar**.

3.  Enter a name for the fiscal calendar and enter a description.

4.  In the **Calendar type** field, select **Day based**.

5.  Enter the starting and ending dates for the first fiscal year that will be added to the fiscal calendar. The default dates are January 1 and December 31. You can also create a fiscal year that starts in one calendar year and ends in another calendar year.
    

    > [!NOTE]
    > <P>If you add a fiscal year later, that fiscal year must start on the day after the previous fiscal year ended. For example, you create a fiscal year that starts on July 1, 2012, and ends on June 30, 2013. The next fiscal year that you create must start on July 1, 2013.</P>



6.  Enter the name of the fiscal year that you are creating.

7.  Enter the length of the period and select the unit for the periods in the new fiscal year.
    
    For example, to create a day-based calendar, you enter a period length of **1** and you select **Months** in the **Unit** field. The fiscal year will include 12 periods, each being one month long. In the **Periods** area of the form, in the **Days** field, you will enter the actual number of days in each month.

8.  Verify that the information is correct, and then click **Create**.

## See also

[(IND) Attach a day-based calendar to a fixed asset value model](ind-attach-a-day-based-calendar-to-a-fixed-asset-value-model.md)

  


