---
title: (CZE) Generate the ledger statement report
TOCTitle: (CZE) Generate the ledger statement report
ms:assetid: 2f2a6860-cc0f-411c-83ad-a89ab0aaa393
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677496(v=AX.60)
ms:contentKeyID: 49384800
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Czech Republic
---

# (CZE) Generate the ledger statement report 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Ledger statement** report to generate and print a ledger statement report for a specified period. You can specify the layout of the ledger statement report in the **Ledger statement definition** form. For more information, see [(CZE) Ledger statement definition (form)](https://technet.microsoft.com/en-us/library/jj710663\(v=ax.60\)).

1.  Click **General ledger** \> **Reports** \> **Transactions** \> **Ledger statement**.

2.  In the **Period start** and **End of period** fields, enter the starting date and ending date of the period that the report is generated for.

3.  In the **Declaring amounts** field, select how the amounts are rounded and displayed in the report, from the following options:
    
      - **1** – The declared amounts are rounded to the nearest whole number based on the rounding method that is selected in the **Rounding form** field in the **Ledger statement definition** form. For example, if you select **Normal** in the **Rounding form** field, CZK 1222.34 is rounded down to CZK 1222, and CZK 122.65 is rounded up to CZK 1223. If you select **Downward** in the **Rounding form** field, CZK 1222.34 is rounded down to CZK 1222. If you select **Rounding-up** in the **Rounding form** field, CZK 1222.34 is rounded up to CZK 1223.
    
      - **1000** – The declared amounts are rounded to the nearest thousand based on the rounding method that is selected in the **Rounding form** field in the **Ledger statement definition** form. For example, CZK 5471 rounded down to the nearest thousand is CZK 5000, and CZK 5471 rounded up to the nearest thousand is CZK 6000.

4.  Click **OK** to generate the report.

## See also

[(CZE) Ledger statement report (LedgerStatement)](cze-ledger-statement-report-ledgerstatement.md)

  


