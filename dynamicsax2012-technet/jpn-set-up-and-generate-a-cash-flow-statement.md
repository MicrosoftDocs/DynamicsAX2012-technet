---
title: (JPN) Set up and generate a cash flow statement
TOCTitle: (JPN) Set up and generate a cash flow statement
ms:assetid: c4aa8754-db8c-4597-b719-1969bbefc314
ms:mtpsurl: https://technet.microsoft.com/library/JJ664967(v=AX.60)
ms:contentKeyID: 49386551
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- cash flow
audience: Application User
ms.search.region: Japan
---

# (JPN) Set up and generate a cash flow statement 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can set up cash flow statements to display cash inflow and outflow for a specified financial period. A cash flow statement includes the following information:

  - The cash inflow and outflow.

  - The cash amount at the beginning, and at the end of the financial period.

  - The changes in cash amount at the beginning, and at the end of the financial period.

The detailed cash flow statement also includes sales order transactions, production manufacturing, fixed asset investments, and common stock cash dividends. The cash flow statement retrieves the required information from the dimensions table, ledger table, ledger transactions, and the calculated cash flow from the transaction amounts.

Use the following procedures to set up and generate a cash flow statement in the Japanese format.

## Set up a cash flow statement

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

2.  Select the **JP financial report style** check box to generate the cash flow statement in the Japanese format.
    

    > [!NOTE]
    > <P>You must select the <STRONG>Asian legal report(s)</STRONG> check box to enable the <STRONG>JP financial report style</STRONG> check box.</P>



3.  Close the form.

4.  Click **General ledger** \> **Setup** \> **Financial statement (traditional)** \> **Financial statement (traditional)**.

5.  Create a financial statement for the cash flow. For more information, see [(JPN) Set up financial statements](jpn-set-up-financial-statements.md).

6.  In the **Category** field, select **Cash flow reports (JP)**.

7.  Close the form.

## Generate a cash flow statement

1.  Click **General ledger** \> **Reports** \> **Transactions** \> **Financial statement (traditional)**.

2.  In the **Financial statement** field, select the cash balance statement that you set up.

3.  In the **Primary dimension set** field, select the dimension set.

4.  Click the **Save to** tab, and then in the **File name** field, specify a file name for the cash balance statement.

5.  Click **OK** to generate the cash balance statement.

6.  Close the form.

After creating a cash flow statement, you can adjust the cash amount, and export to a file. For more information, see [Generate, print, and export a traditional financial statement](generate-print-and-export-a-traditional-financial-statement.md).

## See also

[(JPN) Create a Japanese financial statement](jpn-create-a-japanese-financial-statement.md)

[(JPN) Create row definitions for a Japanese financial statement](jpn-create-row-definitions-for-a-japanese-financial-statement.md)

[(JPN) Financial statement setup (modified form)](https://technet.microsoft.com/library/jj711076\(v=ax.60\))

  


