---
title: (ESP) Group cash payments by invoice year in Declaration 347
TOCTitle: (ESP) Group cash payments by invoice year in Declaration 347
ms:assetid: 2f90be1f-3819-4446-8903-9ab4af4eaa79
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn304971(v=AX.60)
ms:contentKeyID: 54899948
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.TaxReport347Table
- ES - 00003
- MsDynAx060.Forms.TaxReport347Table
---

# (ESP) Group cash payments by invoice year in Declaration 347 


_**Applies To:** Microsoft Dynamics AX 2012_

You can use the **Declaration 347** form to generate a Declaration 347 report for all customer transactions and vendor transactions. Before you generate the report, you can retrieve all of the cash payments that are received in a fiscal year based on the invoice date of the payments. The payments that are posted are transferred to the cash ledger accounts. If the invoice date of a payment is from a previous year, then the amount appears on the report for that previous year. You can specify the minimum amount for cash payments to include on the report. You can then group the cash payments based on the invoice year on the report. You can also generate a delta report to view the differences between the original report and the corrected report.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 3 for AX 2012.</P>



Complete the following tasks before you generate the Declaration 347 report:

1.  Set up the terms of payment. For more information, see [(ESP) Terms of payment (modified form)](https://technet.microsoft.com/en-us/library/jj910987\(v=ax.60\)).

2.  Set up the cash ledger account that is used to retrieve the cash payments. For more information, see [(ESP) Cash ledger accounts (form)](https://technet.microsoft.com/en-us/library/hh242856\(v=ax.60\)).

3.  Set up the sales tax group that is excluded from the Declaration 347 report. For more information, see [(ESP) 347 validation lists (form)](https://technet.microsoft.com/en-us/library/hh209436\(v=ax.60\)).

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

