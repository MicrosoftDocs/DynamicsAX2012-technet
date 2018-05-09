---
title: (FRA) Setup to export financial data
TOCTitle: (FRA) Setup to export financial data
ms:assetid: 55498ff6-6eac-45f0-8d7f-137161b8d07e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg212802(v=AX.60)
ms:contentKeyID: 36057314
ms.date: 07/02/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.LedgerGDPdUTable
- Forms.LedgerGDPdUFieldWizard
- Forms.LedgerGDPdUGroup
- export data
- export financial data
- setup export
---

# (FRA) Setup to export financial data 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You must create definition groups to export data. Definition groups define the tables and formats that are used to export data.


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed in Microsoft Dynamics AX 2012 R3, AX 2012 R2 with hotfix <A href="https://mbs2.microsoft.com/knowledgebase/kbdisplay.aspx?scid=kb%3ben-us%3b2922493">KB2922493</A>, and AX 2012 with hotfix <A href="https://mbs2.microsoft.com/knowledgebase/kbdisplay.aspx?scid=kb%3ben-us%3b2922493">KB2922493</A>. The first section below applies to AX 2012 R2 and AX 2012 without these hotfixes. The second section includes information about the updated functionality.</P>



## Set up to export financial data in AX 2012 and AX 2012 R2

## Create data export definition groups

Use the **Data export definition groups** form to create definition groups.

1.  Click **General ledger** \> **Periodic** \> **Data export** \> **Data export definition groups**.

2.  Create a definition group.

3.  In the **Definition group** and **Name** fields, enter an identification code and name for the data export definition group.

## Create data export tables

Use the **Data export tables** form to define the data export table and file name for a definition group.

1.  Click **General ledger** \> **Periodic** \> **Data export** \> **Data export definition groups**.

2.  In the **Data export definition groups** form, select a definition group, and then click **Data export tables** to open the **Data export tables** form.

3.  Click **New** or press CTRL+N to create a record, and then in the **Data export table** and **File name** fields, enter a data export table name and a file name.

## Create data export fields

Use the **Data export fields** form to create data export fields and assign the tables and fields to extract the data from. The information from the fields is exported for a report.

1.  Click **General ledger** \> **Periodic** \> **Data export** \> **Data export definition groups**. Select or create a definition group, and then click **Data export tables**.

2.  In the **Data export tables** form, select or create a table record, and then click **Data export fields** to open the **Data export fields** form.

3.  Select the tables in the **All tables** list, and then click **\>** to move the selected tables to the **Selected tables** list.

4.  Select the tables in the **Tables related to the selected tables** list, and then click **\>** to move the selected tables to the **Selected tables** list, if required.

5.  Click **Next \>** to define the data export fields.

6.  Press CTRL+N to create a data export field.

7.  In the **Data export field** and **Description** fields, enter a field name and a description.

8.  In the **Table** field, select a table.

9.  In the **Field** field, select a field.

10. Select the **Primary key** check box to use the field as a primary key, if required.

11. Repeat steps 6 through 10 to add additional data export fields.

12. Click **Finish**.

13. In the **Data export tables** form, in the **Data export field for period** field, select a date field. The value in this field is evaluated when the transactions are included in the range of dates to be exported.

## Set up to export financial data in AX 2012 R3, AX 2012 R2 with hotfix KB2922493, and AX 2012 with hotfix KB2922493

## Create data export definition groups

Use the **Data export definition groups** form to create definition groups.

1.  Click **General ledger** \> **Periodic** \> **Data export** \> **Data export definition groups**.

2.  Create a definition group.

3.  In the **Definition group** and **Name** fields, enter an identification code and name for the data export definition group.

## Create data export tables

Use the **Data export tables** form to define the data export table and file name for a definition group. You can use a predefined query to create a data export table that is used to export financial transaction data from Microsoft Dynamics AX as a text file. When you use a predefined query for a data export table, the filtering details and sorting orders that are specified in the query are used to export the financial transaction data.

1.  Click **General ledger** \> **Periodic** \> **Data export** \> **Data export definition groups**.

2.  In the **Data export definition groups** form, select a definition group, and then click **Data export tables** to open the **Data export tables** form.

3.  Click **New** or press CTRL+N to create a record, and then in the **Data export table** and **File name** fields, enter a data export table name and a file name.
    
    –or–
    
    In AX 2012 R3: Click **Query** to use a predefined query to create a data export table.

## Create data export fields

Use the **Data export fields** form to create data export fields and assign the tables and fields to extract the data from. The information from the fields is exported for a report. You can use predefined methods for the data transformation when you export data from the tables and fields.

1.  Click **General ledger** \> **Periodic** \> **Data export** \> **Data export definition groups**. Select or create a definition group, and then click **Data export tables**.

2.  In the **Data export tables** form, select or create a table record, and then click **Data export fields** to open the **Data export fields** form.

3.  Select the tables in the **All tables** list, and then click **\>** to move the selected tables to the **Selected tables** list.

4.  Select the tables in the **Tables related to the selected tables** list, and then click **\>** to move the selected tables to the **Selected tables** list, if required.

5.  Click **Next \>** to define the data export fields.

6.  Press CTRL+N to create a data export field.

7.  In the **Data export field** and **Description** fields, enter a field name and a description.

8.  In the **Table** field, select a table.

9.  In the **Field** field, select a field.
    
    –or–
    
    In AX 2012 R3: In the **Method** field, select a method to use a predefined data transformation. Use the following table to decide which method to use.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Method name</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>deAbsoluteAccountingCurrencyAmount_FR</p></td>
    <td><p>Use this method to export the absolute amount in the accounting currency.</p></td>
    </tr>
    <tr class="even">
    <td><p>deDirection_FR</p></td>
    <td><p>Use this method to export the direction of accounting. This method displays D for debit amounts and C for credit amounts.</p></td>
    </tr>
    <tr class="odd">
    <td><p>deLedgerAccount_FR</p></td>
    <td><p>Use this method to export the main account for an entry.</p></td>
    </tr>
    <tr class="even">
    <td><p>deLedgerAccountName_FR</p></td>
    <td><p>Use this method to export the main account name for an entry.</p></td>
    </tr>
    <tr class="odd">
    <td><p>deEmptyValue_FR</p></td>
    <td><p>Use this method to export an empty value.</p></td>
    </tr>
    <tr class="even">
    <td><p>deJournalCode_FR</p></td>
    <td><p>Use this method to export the first five characters of the value in the <strong>SubledgerVoucher</strong> field.</p></td>
    </tr>
    <tr class="odd">
    <td><p>deJournalLib_FR</p></td>
    <td><p>Use this method to export the value in the <strong>JournalCategory</strong> field. If the <strong>JournalCategory</strong> field is blank, then this method exports the value in the <strong>Type</strong> field from the related <strong>TransactionLog</strong> record.</p></td>
    </tr>
    <tr class="even">
    <td><p>dePieceNum_FR</p></td>
    <td><p>Use this method to export the value in the <strong>DocumentNumber</strong> field. If the <strong>DocumentNumber</strong> field is blank, then this method exports the value in the <strong>SubledgerVoucher</strong> field.</p></td>
    </tr>
    <tr class="odd">
    <td><p>dePieceDate_FR</p></td>
    <td><p>Use this method to export the value in the <strong>DocumentDate</strong> field. If the <strong>DocumentDate</strong> field is blank, then this method exports the value in the <strong>AccountingDate</strong> field.</p></td>
    </tr>
    <tr class="even">
    <td><p>deEcritureLib_FR</p></td>
    <td><p>Use this method to export the value in the <strong>Text</strong> field. If the <strong>Text</strong> field is blank, then this method exports the value in the <strong>Txt</strong> field from the related <strong>TransactionLog</strong> record.</p></td>
    </tr>
    </tbody>
    </table>


10. Select the **Primary key** check box to use the field as a primary key, if required.

11. Repeat steps 6 through 10 to add additional data export fields.

12. Click **Finish**.

13. In the **Data export tables** form, in the **Data export field for period** field, select a date field. The value in this field is evaluated when the transactions are included in the range of dates to be exported.

## See also

[(FRA) Export financial transaction data to an archive file](fra-export-financial-transaction-data-to-an-archive-file.md)

[(DEU, FRA) Data export tables (form)](https://technet.microsoft.com/en-us/library/aa571461\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

