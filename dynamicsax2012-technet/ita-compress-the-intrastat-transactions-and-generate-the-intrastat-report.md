---
title: (ITA) Compress the Intrastat transactions and generate the Intrastat report
TOCTitle: (ITA) Compress the Intrastat transactions and generate the Intrastat report
ms:assetid: e629e4da-db15-4a01-8611-6d2c286a20b5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh227455(v=AX.60)
ms:contentKeyID: 36059798
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Italy
- compress
- Intrastat transactions
---

# (ITA) Compress the Intrastat transactions and generate the Intrastat report 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can compress an Intrastat declaration for the transaction currency. All invoice amounts must be reported in the transaction currency even if the transaction currency is different from your default currency. If there are multiple invoices for the same customer or vendor, the transactions can be compressed for the transaction currency and displayed as a single line in the Intrastat report.

Use the following procedures to set up Intrastat parameters, compress Intrastat transactions, and then generate the Intrastat report.

## Set up Intrastat parameters

Use the **Foreign trade parameters** form to set up compression for the transactions in the Intrastat report. For more information, see [Intrastat (form)](https://technet.microsoft.com/en-us/library/aa619055\(v=ax.60\)).

1.  Click **Organization administration** \> **Setup** \> **Foreign trade** \> **Foreign trade parameters**.

2.  Click **Compress** to open the **Compression of Intrastat** form.

3.  Select **Currency** from the **Available** pane and move it to the **Selected** pane.

4.  Click **OK**.

5.  Close the form to save your changes.

## Compress transactions and generate the Intrastat report

You can generate the Intrastat report that contains the compressed transactions in an ASCII file.

1.  Click **Organization administration** \> **Periodic** \> **Foreign trade** \> **Intrastat**.

2.  Click **Transfer IT** to open the **Selection** form.

3.  Select the **Customer invoice** and **Vendor invoice** check boxes, and then click **OK** to transfer all customer and vendor transactions to the **Intrastat** form.

4.  Click the **General** tab, and select the **Compress** check box to compress the Intrastat transaction.

5.  Click **Output** \> **Diskette IT**.

6.  In the **File name** field, specify the path and file name to generate the Intrastat report.

7.  In the **Diskette** field, enter the reference number for the diskette.

8.  In the **Start date** and **End date** fields, select the starting and ending dates of the reporting period.

9.  Select the **Import** check box to include the import transactions, or select the **Export** check box to include the export transactions in the Intrastat report.

10. Select the **Only corrections** check box to include only corrected transactions in the Intrastat report.

11. Click **OK** to generate the Intrastat report as an ASCII file.

12. Close the form to save your changes.

## See also

[About Intrastat](about-intrastat.md)

[Compression of Intrastat (form)](https://technet.microsoft.com/en-us/library/aa584795\(v=ax.60\))

[(ITA) Make diskette for Intrastat in Italian layout (class form)](https://technet.microsoft.com/en-us/library/aa587754\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

