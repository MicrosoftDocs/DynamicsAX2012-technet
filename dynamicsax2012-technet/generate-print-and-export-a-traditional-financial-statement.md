---
title: Generate, print, and export a traditional financial statement
TOCTitle: Generate, print, and export a traditional financial statement
ms:assetid: ca3962e2-c4cc-4372-ac5d-2158cb758421
ms:mtpsurl: https://technet.microsoft.com/library/Aa572662(v=AX.60)
ms:contentKeyID: 36059331
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Generate, print, and export a traditional financial statement 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

After you set up a specific financial statement as described in [Design the rows and columns of a traditional financial statement](design-the-rows-and-columns-of-a-traditional-financial-statement.md), you can generate and print a traditional financial statement and export the results to various kinds of export files.


> [!NOTE]
> <P>This topic includes information about features that were added or changed for cumulative update 6 or later for Microsoft Dynamics AX 2012 R2. This information also applies to AX 2012 R3.</P>



To print financial statements, you can use Management Reporter, or you can use the traditional financial statements that are included with Microsoft Dynamics AX. For more information about how to print financial statements using Management Reporter, see [Management Reporter for Microsoft Dynamics ERP](http://go.microsoft.com/fwlink/?linkid=324762).

## Generate and print a specific traditional financial statement

Complete the following steps to print the selected traditional financial statement. For more information, see [Financial statement report (form)](https://technet.microsoft.com/library/aa585230\(v=ax.60\)).

The **Financial statement** form is available only when the **Financial statement (traditional)** configuration key is selected.

1.  Click **General ledger** \> **Reports** \> **Transactions** \> **Financial statement (traditional)**.

2.  In the **Financial statement** field, select the traditional financial statement definition to use for the printed statement. The default settings are displayed, but you can change them.

3.  In the **Output type** field, select **Microsoft Excel**.

4.  In the fields in the **Financial dimension sets** field group, select the primary dimension set and, if applicable, the secondary dimension set. Select the corresponding row definitions for the dimension sets.

5.  To print one traditional financial statement for each primary dimension set value, select the **Page break per primary dimension set** check box. A separate page is printed for each primary dimension set, and the lines are based on the secondary dimension set.
    
    Clear the **Page break per primary dimension set** check box to present the primary dimension set as lines in a single traditional financial statement, and the secondary dimension set as detailed information. In this case, any row definitions are also ignored.

6.  In the **Level** field group, you can define a part of the traditional financial statement row structure for printing. In the **From** and **To** fields, enter the first and the last rows to print.

7.  In the **End date** field, enter an ending date to modify the date interval that has been selected and override the date that is entered in the **To date** field on the **Columns** tab. For example, on March 5, the current quarter date interval includes all transactions posted up to and including March 5. You need figures for the closed months of the quarter, instead. Therefore, you enter February 28 as the ending date.

8.  In the **Reference date** field, enter a reference date for the period. This is the date that controls the report and adjusts the date intervals that are defined on the **Columns** tab. For example, the system date is February 1, 2014, and the current year date interval is used. You enter November 15, 2013, as the reference date. The current year is then automatically adjusted to 2013 instead of 2014.
    

    > [!NOTE]
    > <P>When you enter a value in this field, the <STRONG>End date</STRONG> field cannot be used. If you leave both this field and the <STRONG>End date</STRONG> field empty, the system date determines how the dates are adjusted. Dates that are entered manually in the <STRONG>From date</STRONG> and <STRONG>To date</STRONG> fields on the <STRONG>Columns</STRONG> tab are not affected by a reference date.</P>



9.  On the **Columns** tab, view or change the default values.

10. On the **Setup** tab, view or change the default print options.

11. Click **OK** to print the financial statement.

## Export a traditional financial statement

1.  Click **General ledger** \> **Reports** \> **Transactions** \> **Financial statement (traditional)**.
    
    The **Financial statement** form is available only when the **Financial statement (traditional)** configuration key is selected.

2.  In the **Financial statement** field, select the traditional financial statement to export.

3.  You can select more row details for the export. You can also limit the number of rows by using the **From** and **To** fields in the **Level** section.
    
    If you do not add more details, the default rows for the traditional financial statement are used. These are the rows that are created when the statement is set up.

4.  You can click **Select** to limit the traditional financial statement that is being exported.

5.  On the **Columns** tab, define the remaining details about the selected traditional financial statement:
    
    1.  To set a range of dates for the traditional financial statement, use the **Date interval code** field or enter dates in the **From date** and **To date** fields.
    
    2.  In the **Budget model** and **Include submodel** fields, select the relevant budget information.
    
    3.  To set up account and dimension ranges on a specific column for the export, click **Select**. The information in the export file results from the selections here and in step 4.

6.  On the **Financial statement** tab, in the **Output type** field, select **Export to**. An extension is added automatically to export files, such as for files that are created for country/region-specific file formats.

7.  Click **OK**. If the export is successful, you receive a message that the export file has been created, and you can access the file.
    

    > [!NOTE]
    > <P>If you selected an export file format that requires the columns to be strictly formatted, and the data does not comply with this format, the export job stops and you receive a message. In this case, correct the order and format of the columns that you defined for export so that they comply with the requirements. The formatting that you select for the export of a particular traditional financial statement is saved for the next export of a financial statement with the same selections of financial statement name, export format, primary dimension set, primary dimension set row definition, secondary dimension set, and secondary dimension set row definition. If you select a combination of parameters that has been used before, the appropriate formatting, if any, is applied automatically. You can revise the formatting before the export.</P>



## See also

[About traditional financial statements](about-traditional-financial-statements.md)

[Financial statement setup (form)](https://technet.microsoft.com/library/aa600912\(v=ax.60\))

  


