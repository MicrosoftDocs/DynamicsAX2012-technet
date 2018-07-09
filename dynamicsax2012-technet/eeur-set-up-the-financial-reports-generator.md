---
title: (EEUR) Set up the financial reports generator
TOCTitle: (EEUR) Set up the financial reports generator
ms:assetid: 810045fe-1ff2-47e7-9017-ee9ba07fdd52
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ910986(v=AX.60)
ms:contentKeyID: 52075300
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (EEUR) Set up the financial reports generator [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use the Russian financial reports generator (FRG) to generate reports by using Microsoft Word and Microsoft Excel templates. The FRG is used to generate accounting report forms, tax declarations, and other reports for ledger transactions, budgets, and tax registers. The format of the FRG is determined in advance, and each cell is set up independently of the others.

1.  Click **General ledger** \> **Setup** \> **Financial reports generator** \> **Financial reports generator**.

2.  Press CTRL+N to create a report, and then in the **Report code** and **Description** fields, enter an identification number and a short description for the report.

3.  On the **General** tab, in the **Currency** field, select whether the report data is reported in the **Base currency** or the **Reporting currency**.

4.  In the **Period** field, select a date interval that the report is calculated for.
    

    > [!NOTE]
    > <P>The reporting period is calculated based on the date that is specified in <STRONG>Base date</STRONG> field in the <STRONG>Specify the parameters for the report</STRONG> form when the report is run.</P>



5.  In the **Data** field, select the data source for the report. For more information, see [(EEUR) Report (form)](https://technet.microsoft.com/en-us/library/jj911237\(v=ax.60\)).

6.  In the **Budget model** field, select a budget model number.
    

    > [!NOTE]
    > <P>This field is available only when you select <STRONG>Budget</STRONG> in the <STRONG>Data</STRONG> field.</P>



7.  In the **Output to** field, select whether the report is generated in the **Microsoft Office Word** or **Microsoft Office Excel** template.

8.  In the **File name** field, enter the file name and path where the report is saved.

9.  In the **Factor** field, enter a value that the transaction amounts are divided by for the report output. For example, you specify a factor of 1,000,000 and fractional part of 2 for a transaction amount of 3,523,123. In this case, the amount is divided by the factor as 3,523,123/1,000,000 = 3.523123. The amount 3.523123 is then rounded to two decimal places and displayed on the report as 3.52.

10. In the **Fractional part** field, enter the number of decimal places that is used for the amounts on the report.

11. On the **Type of transactions** tab, in the **Transaction usage** field, select the type of transaction to include on the report. For more information, see [(EEUR) Report (form)](https://technet.microsoft.com/en-us/library/jj911237\(v=ax.60\)).
    

    > [!NOTE]
    > <P>This tab is available when you select <STRONG>Transactions</STRONG> in the <STRONG>Data</STRONG> field.</P>



12. On the **Type of operation** tab, click **Add**, and then in the **Transaction type** field, select a transaction type.

13. On the **Operations/Tax** tab, click **Add**, and then in the **Posting layer** field, select a posting layer that has transactions to include on the report.

14. On the **Financial dimensions** tab, click **Add**, and then in the **Reference** field, select a dimension name.

15. In the **From** and **To** fields, select the starting and ending codes to specify the dimension range for the transactions that are included on the report.

16. Click **Open** to view the report in the specified template and to validate the setup of the template cells.

## See also

[(EEUR) Copy the financial reports generator settings](eeur-copy-the-financial-reports-generator-settings.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

