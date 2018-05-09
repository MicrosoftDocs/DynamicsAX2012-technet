---
title: (CZE) Generate the balance sheet report
TOCTitle: (CZE) Generate the balance sheet report
ms:assetid: a7d9ae32-a64c-4bb6-833e-b4b4ccf17dea
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677644(v=AX.60)
ms:contentKeyID: 49384946
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (CZE) Generate the balance sheet report 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Balance sheet** report to generate and print a balance sheet report for a specified period. You can specify the layout of the balance sheet report in the **Balance sheet definition** form. For more information, see [(CZE) Balance sheet definition (form)](https://technet.microsoft.com/en-us/library/jj710630\(v=ax.60\)).

1.  Click **General ledger** \> **Reports** \> **Transactions** \> **Balance sheet**.

2.  In the **Period start** and **End of period** fields, enter the starting date and ending date of the period that the report is generated for.

3.  In the **Declaring amounts** field, select how the amounts are rounded and displayed in the report, from the following options:
    
      - **1** – The declared amounts are rounded to the nearest whole number based on the rounding method that is selected in the **Rounding form** field in the **Balance sheet definition** form. For example, if you select **Normal** in the **Rounding form** field, CZK 1222.34 is rounded down to CZK 1222, and CZK 122.65 is rounded up to CZK 1223. If you select **Downward** in the **Rounding form** field, CZK 1222.34 is rounded down to CZK 1222. If you select **Rounding-up** in the **Rounding form** field, CZK 1222.34 is rounded up to CZK 1223.
    
      - **1000** – The declared amounts are rounded to the nearest thousand based on the rounding method that is selected in the **Rounding form** field in the **Balance sheet definition** form. For example, CZK 5471 rounded down to the nearest thousand is CZK 5000, and CZK 5471 rounded up to the nearest thousand is CZK 6000.

4.  Select the **Include opening balance** check box to include opening balances in the report.

5.  Click **OK** to generate the report.

## See also

[(CZE) Balance sheet report (LedgerBalanceSheet)](cze-balance-sheet-report-ledgerbalancesheet.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

