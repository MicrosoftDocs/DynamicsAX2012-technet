---
title: (CHN) Set up a matrix and generate a dimension matrix report
TOCTitle: (CHN) Set up a matrix and generate a dimension matrix report
ms:assetid: b2aed1fb-79ff-40e7-8007-3a7e1adf8d56
ms:mtpsurl: https://technet.microsoft.com/library/JJ664102(v=AX.60)
ms:contentKeyID: 49384687
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- matrix
- dimension
- Chinese reports
- Chinese vouchers
- subdimensions
audience: Application User
ms.search.region: China (PRC)
---

# (CHN) Set up a matrix and generate a dimension matrix report 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use the **Matrix dimension report** form to set up a dimension matrix that defines the sublevel dimensions for the selected dimension type. You can then generate the **Matrix dimension** report to view transaction details for the selected sublevel dimensions in the Chinese or horizontal format.

## Set up a matrix of dimensions and sublevel dimensions

Use the **Matrix dimension report** form to set up a matrix for the Department, Cost Center, or ExpensePurpose dimension type.

1.  Click **General ledger** \> **Setup** \> **Reports (China)** \> **Matrix dimension report**.

2.  Click **New** to create a dimension matrix.

3.  In the **Dimension matrix** field, enter the code for the dimension matrix.

4.  In the **Description** field, enter a description for the dimension matrix.

5.  On the **General** FastTab, in the **Dimension name** field, select Department, Cost center, or ExpensePurpose as the dimension type.

6.  In the **Format** field, select **Debit** or **Credit** for the selected dimension. If you select **Debit**, the debit amount for the selected dimension is displayed on the report. If you select **Credit**, the credit amount is displayed.

7.  On the **Sublevel account** FastTab, click **Add** to create a sublevel dimension for the specified dimension type.

8.  In the **Dimension value** field, select the sublevel dimension for the matrix.

## Generate the Matrix dimension report

The **Matrix dimension** report displays the voucher date, voucher number, voucher text, and the total account balance for the specified dimension matrix. You can configure Microsoft Dynamics AX to automatically print the **Matrix dimension** report for you on a recurring basis. For more information, see [Print or email a report on a recurring basis](print-or-email-a-report-on-a-recurring-basis.md).

1.  Click **General ledger** \> **Reports** \> **Reports (China)** \> **Matrix dimension**.

2.  In the **From date** and **To date** fields, select the starting and ending dates of the reporting period.

3.  In the **Account** field, select a main account number that the report is to be generated for.

4.  In the **Dimension matrix** field, select the reporting dimension matrix.

5.  In the **Transactions** field, select **Current**, **Operations**, or **Tax** as the transaction type.

6.  Click **OK** to generate the report.

## See also

[(CHN) Dimension matrix report (form)](https://technet.microsoft.com/library/jj663994\(v=ax.60\))

  


