---
title: (THA, SAU, GBR, IRL) Set up a withholding tax settlement period and attach a withholding tax code
TOCTitle: (THA, SAU, GBR, IRL) Set up a withholding tax settlement period and attach a withholding tax code
ms:assetid: 0606980d-fb52-4358-aeab-1e2589fc960d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242109(v=AX.60)
ms:contentKeyID: 36055957
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Thailand
- settlement period
- withholding tax
---

# (THA, SAU, GBR, IRL) Set up a withholding tax settlement period and attach a withholding tax code [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you collect withholding taxes on behalf of the government, you must settle and pay the taxes at regular intervals called settlement periods. You can set up a withholding tax settlement period, and then attach one or more withholding tax codes.

## Create a fiscal calendar

1.  Click **General ledger** \> **Setup** \> **Fiscal calendars**.

2.  Click **New fiscal calendar** to open the **Enter fiscal calendar details** form.

3.  In the **Calendar** field, enter the identification of the fiscal calendar.

4.  In the **Description** field, enter a description for the calendar.

5.  In the **Start of fiscal year** field, select the starting date of the fiscal year.

6.  In the **End of fiscal year** field, select the ending date of the fiscal year.

7.  In the **Fiscal year name** field, enter a name for the fiscal year.

8.  In the **Length of period** field, enter the length of the fiscal calendar period.

9.  In the **Unit** field, select the unit of the fiscal calendar.

10. Click **Create** to create the fiscal calendar.

11. Close the form.

## Set up a withholding tax settlement period and attach a withholding tax code

1.  Click **General ledger** \> **Setup** \> **Withholding tax** \> **Withholding tax settlement periods**.

2.  Create a withholding tax settlement period.

3.  In the **Settlement period** field, enter a unique code to identify the withholding tax settlement period.

4.  In the **Description** field, enter a description of the withholding tax settlement period.

5.  In the **Authority** field, select the withholding tax authority to which taxes are reported and paid at the end of a withholding tax settlement period.

6.  In the **Terms of payment** field, select the terms of payment for the withholding tax payments.

7.  In the **Period interval** field, select the settlement period interval from the following options:
    
      - **Days**
    
      - **Months**
    
      - **Years**

8.  In the **Number of units** field, enter the number of period units to define the withholding tax settlement period. The length of each period that is created on the **Periods** tab is the period interval multiplied by the number of units.
    

    > [!NOTE]
    > <P>If you select <STRONG>Months</STRONG>, and then enter 3 in the <STRONG>Number of units</STRONG> field, three-month (quarterly) periods are created on the <STRONG>Periods</STRONG> tab.</P>



9.  In the **From date** field, select the first day of the first period in the withholding tax settlement period.
    

    > [!NOTE]
    > <P>After you create the first period, click <STRONG>New period</STRONG> to create the other periods. This ensures that all days are accounted for and that each day appears in only one period.</P>



10. In the **To date** field, select the last day of the period interval.

11. Close the form.

12. Click **General ledger** \> **Setup** \> **Withholding tax** \> **Withholding tax codes**.

13. Create a new withholding tax code, and then in the **Settlement period** field, select the withholding tax settlement period.

14. Close the form.

## See also

[(THA, SAU, GBR, IRL) Withholding tax settlement periods (form)](https://technet.microsoft.com/en-us/library/hh209377\(v=ax.60\))

[(THA, SAU, GBR, IRL) Set up a withholding tax code](tha-sau-gbr-irl-set-up-a-withholding-tax-code.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

