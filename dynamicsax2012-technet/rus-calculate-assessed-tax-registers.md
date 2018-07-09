---
title: (RUS) Calculate assessed tax registers
TOCTitle: (RUS) Calculate assessed tax registers
ms:assetid: 4ded2990-bc43-4c87-a1dd-f3a7fe021987
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ665370(v=AX.60)
ms:contentKeyID: 49387458
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (RUS)
- Russia
- assessed tax
---

# (RUS) Calculate assessed tax registers [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The calculation of property tax includes all fixed assets for which a code for the assessed tax type is entered in the fixed assets book. The only exceptions are fixed assets that have a status of **Scheduled**. The calculation includes all fixed assets that are written off or sold during the accounting period. If a fixed asset is written off or sold in the middle of the accounting period, the property tax calculation includes the month during which the write-off or sale is completed.

The tax base for the property tax is calculated based on the annual average taxable property value for the full calendar year. Accounting periods are one quarter, six months, or nine months of the calendar year.

The annual average taxable property value in a tax accounting period is calculated as follows:

(Net book values on the first day of each month + Net book values on the first day of the month after the tax accounting period) / (Number of months in the tax accounting period) + 1

You can calculate the property tax registers by using the following periodic tax registers:

  - **Cost calculation** – Calculate the net book value of fixed assets that are owned, as of the first day of each month in the accounting period. For each fixed asset, you must indicate whether the asset belongs to real property, tax-exempt property, or distributed or dispersed property.

  - **Totals of net book value calculation** – Calculate the totals based on the net book value in the calculation register. The totals for the net book value of real property and tax-exempt property are calculated separately.

  - **Assessed tax** – Calculate the average value of taxable and tax-exempt property, the distributed shares for extended assets, the tax base, the advance payment total for the accounting period, or the tax total for the year by using the data from the **Totals of net book value calculation** register.

<!-- end list -->

1.  Click **Fixed assets (Russia)** \> **Journals** \> **Tax register journal**.

2.  Create a new journal.

3.  In the **Journal batch number** field, enter the unique number of the tax register journal.

4.  In the **Period types**, **Period number**, and **Years** fields, indicate the period that the journal is created for.

5.  Click **Lines** to create lines in the periodic register journal.

6.  Select the **Cost calculation** register line, and then click **Calculate current**.

7.  Select the **Totals of net book value calculation** register line, and then click **Calculate current**.

8.  Select the **Assessed tax** register line, and then click **Calculate current**.
    

    > [!NOTE]
    > <P>After calculation, the status of the registers is set to <STRONG>Calculated</STRONG> in the <STRONG>Status</STRONG> field.</P>



9.  Select the **Approved** check box to approve the register.

10. In the **Worker** field, view or modify the code of the employee who approved the register.

11. Click **Register lines** to view the register lines after the calculation is completed.

When you create the journal for a year in the assessed tax register, the total of the advance payments that were paid for the previous accounting periods is calculated. If the journals for these periods were not created, the advance payment total for the previous accounting periods can be entered manually.

## See also

[(RUS) Tax register journal (form)](https://technet.microsoft.com/en-us/library/jj856114\(v=ax.60\))

[(RUS) Register journal lines (form)](https://technet.microsoft.com/en-us/library/jj839663\(v=ax.60\))

[(RUS) Set up the calculation of assessed tax](rus-set-up-the-calculation-of-assessed-tax.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

