---
title: (CHN) Generate an account matrix report
TOCTitle: (CHN) Generate an account matrix report
ms:assetid: 0b3a44d3-02b5-4921-bfdb-26b6ed13eaf8
ms:mtpsurl: https://technet.microsoft.com/library/JJ663992(v=AX.60)
ms:contentKeyID: 49384578
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- account
- Generate
- matrix
- (CHN)
- China
audience: Application User
ms.search.region: China (PRC)
---

# (CHN) Generate an account matrix report 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can generate an account matrix report to view subaccount information and transaction details for a selected range of dimensions for the account matrix. You can view the report in the Chinese format or in the horizontal format. Account matrix reports are used to view cash, bank, expense, and other ledger accounts that have several sublevel ledger accounts. You can configure Microsoft Dynamics AX to automatically print the **Matrix dimension** report on a recurring basis. For more information, see [Print or email a report on a recurring basis](print-or-email-a-report-on-a-recurring-basis.md).

## Set up an account matrix

Use the **Matrix account report** form to create an account matrix that defines the subaccounts for a ledger account. For example, to view the transaction details for available cash, you can create a new matrix account named Cash, and select ledger account **1001** and its sublevel ledger accounts, **100101**, **100102**, and **100103**.

1.  Click **General ledger** \> **Setup** \> **Reports (China)** \> **Matrix account report**.

2.  Click **New** to create a new account matrix.

3.  In the **Account matrix** field, enter a code for the account matrix.

4.  In the **Description** field, enter a description for the account matrix.

5.  On the **General** FastTab, in the **Format** field, select **Debit** or **Credit** for the subaccount. If you select **Debit**, the amount debited to the subaccount is displayed on the report. If you select **Credit**, the amount credited to the subaccount is displayed.

6.  In the **Main account** field, select a main account for the matrix.

7.  On the **Sublevel account** FastTab, click **Add** to create a sublevel account.

8.  In the **Main account** field, select the sublevel main account for the matrix. The main account name is displayed in the **Name** field.

## Generate the account matrix report

A **Matrix account report** contains information about a parent account and its subaccounts, and identifies their formats as debit or credit. The generated report displays the voucher date, voucher number, voucher text, debit or credit amounts, and account balance. The subaccounts are displayed as columns on the report.

1.  Click **General ledger** \> **Reports** \> **Reports (China)** \> **Matrix account report (China)**.

2.  In the **From date** and **To date** fields, select the starting and ending dates for the reporting period.
    

    > [!NOTE]
    > <P>If you do not specify a date range, the current date is used as the reporting date. If you specify only the starting date or ending date in the date range, the current date is used as the missing date in the range.</P>



3.  In the **Account matrix** field, select the reporting account matrix.

4.  In the **Transactions** field, select **Current**, **Operations**, or **Tax** as the transaction type.

5.  Click **OK** to generate the report.

## Generate the matrix report with dimension details

You can generate the matrix report with dimension details to view the transaction details for a selected range of dimensions for the account matrix in the horizontal Chinese format. This report sorts the credit and debit values for ledger transactions in multiple columns based on their financial dimensions, such as department, cost center, or purpose. You can view the transaction details of operation costs for several departments for the specified period.

1.  Click **General ledger** \> **Reports** \> **Reports (China)** \> **Matrix report with dimensions**.

2.  In the **Account matrix** field, select the reporting account matrix.

3.  In the **Dimension type** field, select **CostCenter**, **Department**, or **ExpensePurpose** as the type of dimension that is included in the account matrix.

4.  In the **From dimension** and **To dimension** fields, select the range of dimensions that the report is generated for.
    

    > [!NOTE]
    > <P>If you do not specify the dimension range, the report is generated for all dimensions. If you specify a value for either <STRONG>From dimension</STRONG> or <STRONG>To dimension</STRONG>, the first dimension that is defined is used as the missing <STRONG>From dimension</STRONG> value, and the last dimension that is defined is used as the missing <STRONG>To dimension</STRONG> value. If you specify a value for <STRONG>From dimension</STRONG> that is less than the <STRONG>To dimension</STRONG> value, the report is generated without validating the dimension values.</P>



5.  In the **From date** and **To date** fields, select the starting and ending dates of the reporting period.
    

    > [!NOTE]
    > <P>If you do not specify a date range, the current date is used as the reporting date. If you specify only the starting date or ending date in the date range, the current date is used as the missing date in the range.</P>



6.  Click **OK** to generate the report details.

## See also

[(CHN) Matrix account report (form)](https://technet.microsoft.com/library/jj664131\(v=ax.60\))

  


