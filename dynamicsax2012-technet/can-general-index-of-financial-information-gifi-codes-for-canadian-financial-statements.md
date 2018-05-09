---
title: (CAN) General Index of Financial Information (GIFI) codes for Canadian financial statements
TOCTitle: (CAN) General Index of Financial Information (GIFI) codes for Canadian financial statements
ms:assetid: 69e8a761-1faa-48fc-9cc1-638ae426c069
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa585796(v=AX.60)
ms:contentKeyID: 36057975
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (CAN) General Index of Financial Information (GIFI) codes for Canadian financial statements 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The General Index of Financial Information (GIFI) is a list of accounts and information that are found on financial statements. Each item on the GIFI account list has a unique code that you can match with ledger account numbers from your chart of accounts. For example, the GIFI code for cash is 1001.

You must use GIFI codes when you submit financial statement information to the Canada Revenue Agency (CRA) in both paper and electronic returns.


> [!NOTE]
> <P>For current information and regulations, visit <A href="http://www.cra-arc.gc.ca/menu-eng.html">Canada Revenue Agency</A>.</P>



You must complete the following tasks before you begin to use GIFI codes:

  - Set up dimensions based on your general ledger accounts by using the **Financial dimension sets** form. For more information, see [Financial dimension sets (form)](https://technet.microsoft.com/en-us/library/aa597282\(v=ax.60\)).

  - Create a row definition for your company financial statement. For more information, see [Design the row structure of a traditional financial statement](design-the-row-structure-of-a-traditional-financial-statement.md).

  - Set up financial statement information for your company by using the **Financial statement** form.

  - Download the binary file of GIFI codes from [CustomerSource](http://go.microsoft.com/fwlink/?linkid=84597).

Use the following procedures to import GIFI codes into Microsoft Dynamics AX, and then use them for financial reporting.

## Import GIFI codes from the binary file

Download the binary file of GIFI codes to your computer hard disk.

1.  In the Microsoft Dynamics AX list page, press CTRL+D to open the **AOT**.

2.  Expand the **Classes** node to select **GIFICodesToFinancialStatmentTemplate**.

3.  Right-click **GIFICodesToFinancialStatmentTemplate**, and then select **Open** to open the **Import GIFI codes** form.

4.  In the **File name** field, browse to the binary file of GIFI codes that contains the data to be imported.

5.  In the **Dimension set** field, select the financial dimension set that you set up for GIFI codes in the **Financial dimension sets** form.

6.  In the **Row definition** field, select the code for a financial statement row definition.

7.  Click **OK** to close the **Import GIFI codes** form.

8.  Click **General ledger** \> **Setup** \> **Financial statement (traditional)** \> **Row definition**.

9.  Select the row definition that you created, and then click **Structure designer** to open the **Structure designer** form.

10. In the **Structure designer** form, view the newly imported GIFI codes.

11. Close the forms to save your changes.

## Link ledger accounts to GIFI codes

1.  In the **Structure designer** form, select ledger accounts to link to GIFI codes. For information about linking ledger accounts to GIFI codes, see [Structure designer (form)](https://technet.microsoft.com/en-us/library/aa552297\(v=ax.60\)).

2.  When you have finished linking accounts to GIFI codes, close the **Structure designer** form.

## Create row definitions for financial statements that include GIFI codes

You must set up a row definition for each set of GIFI codes that you plan to use for financial statements. For example, to print a balance sheet that includes GIFI codes for ledger accounts, you must set up a definition with GIFI codes for the balance sheet. To print a profit and loss statement that includes GIFI codes, you must set up a definition with GIFI codes for the profit and loss statement.

1.  Use the **Row definition** form to create row definitions for a financial statement that includes GIFI codes.
    

    > [!NOTE]
    > <P>You must also import GIFI codes from the binary file and link them to your ledger accounts. For more information, see the <STRONG>Link ledger accounts to GIFI codes</STRONG> section.</P>



2.  In the **Row definition** form, click **Print** to print a row definition structure report.

3.  Verify the general ledger accounts and GIFI codes.

4.  Repeat steps 1 through 3 for each financial statement that includes GIFI codes.

## Create and print financial statement reports that include GIFI codes


> [!NOTE]
> <P>For general information about creating and printing financial statements, see <A href="generate-print-and-export-a-traditional-financial-statement.md">Generate, print, and export a traditional financial statement</A>.</P>



1.  Click **General ledger** \> **Reports** \> **Transactions** \> **Financial statement (traditional)**.

2.  Select a financial statement.

3.  Select a GIFI row definition in the **Primary dimension set** field for the financial statement.

4.  Enter additional information, as needed.

5.  Click **OK** .

6.  Verify the information in the financial statement.

7.  Repeat steps 1 through 6 for each financial statement that includes GIFI codes.

## Export a financial statement that includes GIFI codes to Microsoft Excel

You can create a Microsoft Excel worksheet to submit reports that include GIFI codes to the CRA. You can also submit a paper copy, or you can enter information from the worksheet on the CRA website. If you or your tax accountant uses tax software, refer to the software documentation for instructions about submitting financial statements.

1.  Click **General ledger** \> **Reports** \> **Transactions** \> **Financial statement (traditional)**.

2.  Enter GIFI code information in the **Financial statement** and **Primary dimension set** fields.

3.  In the **Output type** field, select **Export to**.

4.  Click the **Export to** tab, and then click **Setup**.

5.  In the **Available** column, select **CA\_GIFI**, and then move it into the **Selected** column.

6.  Close the **File format for the export of the financial statement** form.

7.  On the **Export to** tab, enter the export location and the name of the export file, such as C:\\CA\_GIFI Excel export.

8.  In the **File format** field, select **CA\_GIFI**.

9.  Click **OK** to close the form.

## See also

[Row definition (form)](https://technet.microsoft.com/en-us/library/aa557429\(v=ax.60\))

[Financial statement report (form)](https://technet.microsoft.com/en-us/library/aa585230\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

