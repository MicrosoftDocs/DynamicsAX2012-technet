---
title: (EEUR) Create and copy report cells
TOCTitle: (EEUR) Create and copy report cells
ms:assetid: 3f32622b-a725-4869-b4f6-1da2c6618aa7
ms:mtpsurl: https://technet.microsoft.com/library/JJ910972(v=AX.60)
ms:contentKeyID: 52075296
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- copy report cells
- create report cells
audience: Application User
ms.search.region: Czech Republic, Estonia, Hungary, Latvia, Lithuania, Poland, Russia
---

# (EEUR) Create and copy report cells 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use the Russian Financial reports generator (FRG) to generate a report by using a Microsoft Excel template. If the template is created without specialized names for cells, you can create cells in an Excel template that uses the standard Excel cell names, such as A1 and B2. The report data is updated in the first worksheet in the Excel template.

To generate data in the other worksheets in the template, use the following cell naming format: Worksheet name in Excel template\!cell number. For example, a cell can be named form A1\!s42.

## Create report cells

1.  Click **General ledger** \> **Setup** \> **Financial reports generator** \> **Financial reports generator**.

2.  Select a report line, and then click **Setup**.

3.  In the **Requisite** field, select the cell requisite for the electronic report.
    

    > [!NOTE]
    > <P>This field is available only for Russia, and only when you select a document template in the <STRONG>Template</STRONG> field in the <STRONG>Report</STRONG> form.</P>



4.  In the **Cell** and **Description** fields, enter the cell name from the template and a short description for the report cell.

5.  In the **Line type** field, select the data source for the report.

6.  In the **Period** field, select the voucher calculation period.

7.  Select the **Manual data input** check box to enter cell values manually when you generate the report.

8.  In the **By default** field, enter the default amount value for the cell.

9.  Click the **General** tab, and then in the **Budget model** field, select a budget model number.
    

    > [!NOTE]
    > <P>This field is available only when you select <STRONG>Budget</STRONG> in the <STRONG>Line type</STRONG> field.</P>



10. Click the **Type of transactions** tab to enter parameters to filter transactions by.
    

    > [!NOTE]
    > <P>This tab is available only when you select <STRONG>Transactions</STRONG>, <STRONG>Constant</STRONG>, or <STRONG>Function query</STRONG> in the <STRONG>Line type</STRONG> field.</P>



11. In the **Transaction usage** field, select the type of transaction to include on the report, from the following options:
    
      - **All** – All of the transactions are used to create the report.
    
      - **Only reversing entry** – Only transactions that are reversed are used to create the report.
    
      - **Without reversing entry** – All transactions except the transactions that are reversed are used to create the report.

12. Click the **Type of operation** tab to enter information to filter transactions by transaction type.

13. Click **Add**, and then in **Transaction type** field, select a transaction type.

14. Click the **Operations/Tax** tab to enter information to filter transactions by accounting type.

15. Click **Add**, and then in the **Posting layer** field, select a posting layer that has transactions to include in the report. Select from the following options:
    
      - **Current** – Transactions that are posted to the **Current** posting layer are included.
    
      - **Operations** – Transactions that are posted to the **Current** or **Operations** posting layer are included.
    
      - **Tax** – Transactions that are posted to the **Current** or **Tax** posting layer are included.
    
      - **Operations minus tax** – Transactions that are posted to the **Operations** posting layer, minus the transactions that are posted to the **Tax** posting layer, are included.
    
      - **Only operations** – Transactions that are posted to the **Operations** posting layer are included.
    
      - **Only tax** – Transactions that are posted to the **Tax** posting layer are included.
    
      - **Operations plus tax** – Transactions that are posted to the **Operations** or **Tax** posting layer are included.
    
      - **Total** – Transactions that are posted to the **Current**, **Operations**, and **Tax** posting layers are included.

16. Click the **Tax registers** tab, and then in the **Register code** and **Register field** fields, select a tax register number and a name.
    

    > [!NOTE]
    > <P>This tab is available only for Russia, and only when you select <STRONG>Register</STRONG> in the <STRONG>Line type</STRONG> field.</P>



17. Click the **Financial dimensions** tab to specify a dimension name and dimension range to filter transactions by financial dimensions.

18. Click **Add**, and then in the **Reference** field, select a dimension name.

19. In the **From** and **To** fields, select the starting and ending codes for the dimension range for the transactions that are included on the report.

## Copy report cell settings

You can copy the report cell settings from one legal entity to another. The report cells are updated in the target legal entity so that they are the same as the fields in the source legal entity, with the same names that are used when the report is set up.

In the **Period** and **Data** fields on the **General** tab in the **Report** form, you specify the period and data source for the report. In the **Field setup** form, you specify the period and data source for report cells. For example, if the period for cell A1 is set to **January**, and the period for the report is set to **March**, then all of the report cells are updated with the data for **March**, and cell A1 is updated with data for **January**.

1.  Click **General ledger** \> **Setup** \> **Financial reports generator** \> **Financial reports generator**.

2.  Select a line, and then click **Setup**.

3.  Select a report cell line, and then click **Functions** \> **Copy**.

4.  In the **Source report** field group, in the **Company** field, select the legal entity whose report settings are to be copied.

5.  In the **Report code**, select the report code to copy.

6.  In the **Cell** field, select the cell that is to be copied from the report.

7.  In the **Target report** field group, in the **Company** field, select the legal entity that the report settings are copied to.

8.  In the **Report code**, select the report code that the report settings are copied to.

9.  In the **Cell** field, select the cell that the cell settings are copied to.
    

    > [!NOTE]
    > <P>If you have already specified settings for the target cell, those settings are overwritten.</P>



10. Click **OK** to copy a cell, all of its settings, and cell operations from the source report to the target report.

## See also

[(EEUR) Field setup (form)](https://technet.microsoft.com/library/jj910976\(v=ax.60\))

[(EEUR) Financial report generator parameters copying (form)](https://technet.microsoft.com/library/jj911006\(v=ax.60\))

  


