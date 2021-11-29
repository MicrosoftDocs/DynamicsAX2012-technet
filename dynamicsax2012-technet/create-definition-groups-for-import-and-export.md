---
title: Create definition groups for import and export
TOCTitle: Create definition groups for import and export
ms:assetid: 4dba7d56-469c-4124-8bc7-5f2928184255
ms:mtpsurl: https://technet.microsoft.com/library/Aa834357(v=AX.60)
ms:contentKeyID: 35132630
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Create definition groups for import and export 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Definition groups identify groups of tables that can be imported or exported when you use Microsoft Dynamics AX data import/export

Definition groups must be set up before you export data, but are not required when you import data. If you select a definition group when you import data, only table names in the definition group are used. All other settings, such as export criteria, are used only to export data.

Before you create a definition group, determine whether you are using the correct tool to import and export your data. In general, Microsoft Dynamics AX data import/export is used to move data from a staging environment to another environment. Microsoft Dynamics AX data import/export consists of a series of resource-intensive operations. Therefore, we recommend that you use it only during off-peak hours. For information about other tools that are used to import and export, see [Plan data import, export, and migration](plan-data-import-export-and-migration.md).

We recommend that you research which table groups to include in your definition group. The table groups that you select when you first create a definition group cannot be changed later. The default table groups are **Main**, **Parameter**, **Group**, **Framework**, and **Miscellaneous**. If you include all of these table groups, more than 2,000 tables are included in your definition group. For lists of the tables that are in included each table group, see [Table and table group reference](table-and-table-group-reference.md).

A definition group is typically created to export Application Integration Framework (AIF) endpoints.

This topic includes the following sections:

  - Create an empty definition group

  - Select tables for a definition group

  - Example: Create a definition group to export AIF endpoints


> [!NOTE]
> <P>Creating a definition group can be a query-intensive and processing-intensive process. For best performance, we recommend that you perform all tasks that are related to export and import during non-peak hours. These tasks include creating definition groups.</P>



## Create an empty definition group

1.  Click **System administration** \> **Common** \> **Data export/import** \> **Definition groups**. Click **New**.
    
    The **Create table definition group** form opens.

2.  Enter a name and description for the definition group.
    

    > [!NOTE]
    > <P>To reset the fields on all tabs to their original values, click <STRONG>Default</STRONG>. To clear all values on the <STRONG>Options</STRONG> and <STRONG>Include table groups</STRONG> tabs, click <STRONG>Clear</STRONG>.</P>



3.  Click the **Options** tab, and then select the following options to identify the types of data to export:
    
      - **Note** – Include notes about document management that were added in the Application Object Tree (AOT) by using the **Add notes** command, and that are stored in the DocuRef table.
    
      - **Include system tables**
    
      - **Include cross-reference tables**
    
      - **Include database log tables**
    
      - **Include shared tables**

4.  Click the **Include table groups** tab, and then select the table groups to include in the definition group. The following table lists the types of table groups that you can select. For a detailed list of all tables in a table group, see [Table and table group reference](table-and-table-group-reference.md).
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Framework</strong></p></td>
    <td><p>Include the tables that are used by the underlying Microsoft Dynamics AX framework. These tables are created during installation, and they are not associated with configuration keys.</p>
    <p>An example is ReleaseUpdateBulkCopy.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Group</strong></p></td>
    <td><p>Include the tables that are used to categorize the tables that are in the <strong>Main</strong> table group.</p>
    <p>Examples include tables for bank groups, pricing groups, commission groups, item groups, and addresses.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Main</strong></p></td>
    <td><p>Include the principal or master tables that contain data for central business objects. These tables typically contain static, base information.</p>
    <p>Examples include CustTable and VendTable.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Miscellaneous</strong></p></td>
    <td><p>Include tables that have not been otherwise categorized.</p>
    <p><strong>Miscellaneous</strong> is the default type of table group for a new table.</p>
    <p>Examples include tables for methods of payment, web portals, asset setup, states, and transactions.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Parameter</strong></p></td>
    <td><p>Include the tables that contain parameters or setup information for tables that are in the <strong>Main</strong> table group.</p>
    <p>Examples include CustParameters and VendParameters.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Reference</strong></p></td>
    <td><p>Include tables that contain reference data.</p>
    <p>An example is Currency.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Transaction</strong></p></td>
    <td><p>Include tables that contain transaction data.</p>
    <p>Examples include CustTrans and VendTrans.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Transaction header</strong></p></td>
    <td><p>Include tables that categorize the tables in the <strong>Transaction line</strong> table group.</p>
    <p>There is a one-to-many relationship between a <strong>Transaction header</strong> table and <strong>Transaction line</strong> tables.</p>
    <p>An example is SourceDocumentHeader.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Transaction line</strong></p></td>
    <td><p>Include tables that contain transaction data.</p>
    <p>An example is SourceDocumentLine.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Worksheet</strong></p></td>
    <td><p>Include tables that contain information that has to be validated and made into transactions.</p>
    <p>An example is DocuRef.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Worksheet header</strong></p></td>
    <td><p>Include tables that categorize <strong>Worksheet line</strong> tables.</p>
    <p>There is a one-to-many relationship between a <strong>Worksheet header</strong> table and <strong>Worksheet line</strong> tables.</p>
    <p>An example is SalesTable.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Worksheet line</strong></p></td>
    <td><p>Include tables that contain information that is validated and made into transactions.</p>
    <p>Unlike the data that is contained in tables that are in the <strong>Transaction</strong> table group, the data in <strong>Worksheet line</strong> tables is temporary.</p>
    <p>An example is SalesLine.</p></td>
    </tr>
    </tbody>
    </table>


## Select tables for a definition group

1.  Click **System administration** \> **Common** \> **Data export/import** \> **Definition groups**. Click **Select tables**.
    
    The **Select tables** form opens. This form lists all of the tables that are in the definition group. These tables belong to the table groups that you selected when you created the definition group.

2.  Change the data that is included in the definition group, by performing one or more of the procedures listed below.

## Remove tables from a definition group

To remove any tables that you do not want to include in the definition group, select the tables, and then click **Remove**.

## Add tables to a definition group

To add tables that you want to include, select the tables, and then click **Add**.

## Set export criteria

Specify the types of records to export from a table by setting export criteria.


> [!NOTE]
> <P>Exporting data by using a definition group that includes criteria can be a resource-intensive process. Therefore, we recommend that you export data by setting criteria only during off-peak hours.</P>



1.  Select a table in the list.

2.  Click **Apply criteria** to make the **Export criteria** button available, and then click **Export criteria**.

3.  Use the **Inquiry** form to filter the records that are exported from the table. For more information, see [Inquiry (form)](https://technet.microsoft.com/library/aa575929\(v=ax.60\)).

## Add related tables to a definition group

You can add tables that have primary key relationships or foreign key relationships to one of the tables in the definition group. The related tables may not belong to the table groups that you selected when you created the definition group.

A table relationship level indicates how closely a table is related to the selected table. For example, if you select related tables for VendTable, VendTable has one relationship level with TaxVatNumTable through CompanyInfo. Because of the single relationship level, both VendTable and TaxVatNumTable have a relationship with CompanyInfo. VendTable has two relationship levels with LogisticsAddressCountryRegion through TaxVatNumTable. Because of the two relationship levels, VendTable has a relationship with TaxVatNumTable, and TaxVatNumTable has a relationship with LogisticsAddressCountryRegion. There are often multiple relationship paths between related tables. Therefore, the same tables may appear with different relationship levels as you work with those tables.


> [!NOTE]
> <P>Working with related tables can be a resource-intensive process. If a table has many related tables, the <STRONG>Analyzing related tables</STRONG> message may be displayed when the system retrieves relationship information.</P>



1.  Select a table in the list.

2.  Select **Specify related tables** to make the **Select related tables** button available, and then click **Select related tables**.

3.  Use the **Select related tables** form to filter the related tables that are included in the definition group. In this form, you can specify how many table relationship levels to include in the definition group.
    
    For more information, see [Select related tables (form)](https://technet.microsoft.com/library/hh227577\(v=ax.60\)).

## Example: Create a definition group to export AIF endpoints

A definition group is frequently used to move AIF endpoints from one environment to another. Use the following procedure to create a definition group that includes all incoming ports and endpoints, together with their related artifacts.

1.  Click **System administration** \> **Common** \> **Data export/import** \> **Definition groups**. Click **New**.

2.  Enter a name and description for the definition group.

3.  Click **Clear** to clear all values that are on the **Options** and **Include table groups** tabs, and then click **OK**.

4.  Click **Select tables**. In the **Name of table** list, click **AIFPort**.

5.  Select **Apply criteria** and **Specify related tables** to make the **Export criteria** and **Select related tables** buttons available.

6.  Optional: Click **Select related tables**. In the **Select related tables** form, keep the **Select table relationship levels to include:** field set to the default value of three . Click the **Select all tables in list** check box, and then click **Close**.

7.  Close the **Select tables** form.

8.  Optional: Click **Export criteria**. In the **Criteria** field, select the name of port to export tables for, and then click **OK**.

You can use the definition group to export the tables that are related to the AIF endpoints from one system, and then import them to another system. For more information about how to export and import, see [Export data to another instance of Microsoft Dynamics AX](export-data-to-another-instance-of-microsoft-dynamics-ax.md) and [Import data from another instance of Microsoft Dynamics AX](import-data-from-another-instance-of-microsoft-dynamics-ax.md).


> [!IMPORTANT]
> <P>If you are importing AIF or services-related tables, such as AifInboundPort, do not select <STRONG>Update existing record</STRONG> during the import process.</P>



## See also

[Create table definition group (form)](https://technet.microsoft.com/library/hh208980\(v=ax.60\))

[Import data from another instance of Microsoft Dynamics AX](import-data-from-another-instance-of-microsoft-dynamics-ax.md)

[Export data to another instance of Microsoft Dynamics AX](export-data-to-another-instance-of-microsoft-dynamics-ax.md)

  


