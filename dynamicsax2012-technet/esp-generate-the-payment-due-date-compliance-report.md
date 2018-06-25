---
title: (ESP) Generate the payment due date compliance report
TOCTitle: (ESP) Generate the payment due date compliance report
ms:assetid: 082e55c1-10ce-4424-93f2-e47cf25af43d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ923096(v=AX.60)
ms:contentKeyID: 52075217
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Spain
- SSRS_Reports.Reports.DueDateCompliance_ES
- ES - 00004
- payment due date compliance
- payments due date compliance
---

# (ESP) Generate the payment due date compliance report [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can generate the Payments due date compliance report, which is a statistics report that contains information about the invoices that are paid during a period that you specify. The report displays the amounts that are paid based on the payment terms, as well as the amounts that are paid outside of the payment terms. The amounts that are paid using payment journals and promissory notes are included in the report.


> [!NOTE]
> <P>In AX 2012 R3 and cumulative update 7 or later for AX 2012 R2: The report includes the payments that are made by using promissory notes that have a status of <STRONG>Drawn</STRONG>, <STRONG>Remitted</STRONG>, or <STRONG>Honored</STRONG>.</P>



Use the **Spanish payments due date compliance report** form to generate the Payments due date compliance report.

1.  Click **General ledger** \> **Reports** \> **External** \> **Spanish payments due date compliance report**.

2.  On the **General** tab, in the **Current period** field group, in the **From** and **To** fields, select the starting and ending dates of the period that the report is generated for.

3.  In the **Comparative period** field group, in the **From** and **To** fields, select the starting and ending dates of the comparative period. For example, you can select the starting and ending dates of the previous fiscal period.

4.  Click **Select**, and then specify the criteria to select the vendor transactions, such as invoices, payments, and promissory note journals. Click **OK**.

5.  In the **Spanish payments due date compliance report** form, click **OK** to generate the report.

## See also

[(ESP) Set up due date limits to calculate invoice due dates](esp-set-up-due-date-limits-to-calculate-invoice-due-dates.md)

[(ESP) Spanish payment due date compliance report (DueDateCompliance\_ES)](esp-spanish-payment-due-date-compliance-report-duedatecompliance-es.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

