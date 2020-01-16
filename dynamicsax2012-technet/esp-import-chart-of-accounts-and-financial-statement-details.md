---
title: (ESP) Import chart of accounts and financial statement details
TOCTitle: (ESP) Import chart of accounts and financial statement details
ms:assetid: 976e181c-b069-49c9-84c8-3b965c717b11
ms:mtpsurl: https://technet.microsoft.com/library/Hh209413(v=AX.60)
ms:contentKeyID: 36058670
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Import
- Spain
- chart of account
- financial statement
audience: Application User
ms.search.region: Spain
---

# (ESP) Import chart of accounts and financial statement details 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In accordance with 2008 regulatory requirements, all Spanish companies are required to comply with a new chart of accounts standard. In addition, the regulations require changes to all mandatory official reports, including Balance sheet, Income and Expenses, and Cash Flow. Instead of manually creating the new chart of accounts and financial statements based on these requirements, you can download the templates for the chart of accounts and financial statements, modify them based on your company's requirements, save them as text files, and then import them into Microsoft Dynamics AX


> [!NOTE]
> <P>We recommend that you use Management Reporter for Microsoft Dynamics ERP to create, maintain, deploy, and view financial reports. Management Reporter lets you design financial reports based on ledger accounts and financial dimensions, drill down to transaction-level detail, and use web-based report viewing.</P>
> <P>For more information about how to print financial reports by using Management Reporter, see <A href="http://go.microsoft.com/fwlink/?linkid=324762">Management Reporter for Microsoft Dynamics ERP</A>.</P>



## Import general ledger accounts

To import the new or updated general ledger accounts, you must first download the template that contains the general ledger accounts. During the import process, a check is made to verify whether the account in the template already exists with the same account number in Microsoft Dynamics AX. If you attempt to import an account that already exists with the same number, the import process ends.

1.  Download the templates for chart of accounts and the totaling accounts. These Microsoft Excel files can contain a set of accounts or the entire chart of accounts.

2.  Update the Excel files based on your company’s requirements.

3.  Save these Excel files as MS-DOS text files.

4.  Click **General ledger** \> **Setup** \> **Chart of accounts** \> **Import main accounts**.

5.  In the **Chart of accounts** field, select the chart of accounts to which you want to import the general ledger accounts.

6.  In the **Main accounts** field, specify the path and name of the text file that contains the list of general ledger accounts to be imported.

7.  In the **Totals** field, specify the path and name of the text file to be imported. This file contains a list of totaling accounts for a general ledger account of the type **Total**.

8.  Click **OK** to import the files.
    

    > [!NOTE]
    > <P>When you import the file in the <STRONG>Totals</STRONG> field, the general ledger account in the file must be available in Microsoft Dynamics AX and the account type must be <STRONG>Total</STRONG>.</P>



## Import financial statements

Based on the regulatory requirements, the following reports have been updated:

  - Balance (standard)

  - Balance (summary)

  - Balance (small-medium)

  - Losses and gains (standard)

  - Losses and gains (summary)

In addition, the following reports have been added to Microsoft Dynamics AX:

  - Status of incomes and wastes (standard)

  - Status of incomes and wastes (summary)

  - Cash flow report

To import these new and updated reports:

1.  Download the **Financial dimension sets**, **Row definition**, **Row structure**, **Financial statement**, and **Column definition** templates for each report.

2.  Update the Microsoft Excel files based on your company’s requirements. For more information, see [Setting up traditional financial statements](setting-up-traditional-financial-statements.md)

3.  Save these Excel files as MS-DOS text files.
    

    > [!NOTE]
    > <P>In the text file imported in the <STRONG>Row structure</STRONG> field, you can design the structure of each row in a financial statement. For more information, see <A href="design-the-row-structure-of-a-traditional-financial-statement.md">Design the row structure of a traditional financial statement</A> and <A href="design-the-rows-and-columns-of-a-traditional-financial-statement.md">Design the rows and columns of a traditional financial statement</A>. The <STRONG>Row ID</STRONG> column in this file is a unique code that identifies every row in the file. The value in this field is used to calculate formulas for the financial statements. For example, for row 23, specify the <STRONG>Type</STRONG> as <STRONG>Calculation</STRONG> and the <STRONG>Calculation expression</STRONG> as “#24 + #21”. This indicates that the value for row 23 is derived by adding the values in rows 24 and 21.</P>



4.  Click **General ledger** \> **Setup** \> **Financial statement (traditional)** \> **Import financial statement definitions**.

5.  In the **Financial dimension sets** field, specify the path and file name of the dimension set text file.

6.  In the **Row definition** field, specify the path and file name of the row definitions text file.

7.  In the **Row structure** field, specify the path and file name of the row structure text file.

8.  In the **Financial statement** field, specify the path and file name of the financial statement template.

9.  In the **Column definition** field, specify the path and file name of the column definitions text file.

10. Click **OK** to import the text files.

## See also

[(ESP) Import financial statement definition (form)](https://technet.microsoft.com/library/hh209564\(v=ax.60\))

  


