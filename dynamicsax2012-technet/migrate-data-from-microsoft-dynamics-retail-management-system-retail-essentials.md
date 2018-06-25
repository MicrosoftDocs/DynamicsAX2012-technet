---
title: Migrate data from Microsoft Dynamics Retail Management System (Retail essentials)
TOCTitle: Migrate data from Microsoft Dynamics Retail Management System (Retail essentials)
ms:assetid: ab056d98-0ca0-49ea-a616-a24728431b5d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn736933(v=AX.60)
ms:contentKeyID: 62200411
ms.date: 01/07/2015
mtps_version: v=AX.60
f1_keywords:
- MsDynAx060.Forms.RetailRMSMigrationParameters
---

# Migrate data from Microsoft Dynamics Retail Management System (Retail essentials) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Retail essentials provides a data import feature that is optimized to import data from Microsoft Dynamics Retail Management System (RMS). RMS is a retail system from Microsoft that is a precursor to Retail essentials. The data import feature is built on top of the Data Import/Export Framework for Microsoft Dynamics AX 2012 and uses Data Import/Export Framework entities to migrate data.

## What data is migrated?

The data import feature helps you move core data, such as information about customers and products, from RMS to Retail essentials. The following default entities are provided for RMS data migration:

  - Customers

  - Products

  - Stores

  - Employees

  - Inventory

  - Vendors

  - Prices and discounts

  - Taxes

With the release of Microsoft Dynamics AX 2012 R3 Cumulative Update 8, RMS entities that contain transactional or historical data are migrated to Retail essentials. The transactions can be viewed in the **Retail sales** and **Retail store transactions** forms. Entry status for all migrated transactions is marked as posted.

The following RMS tables and fields are mapped to the indicated fields in the RetailTransactionTable in Retail Essentials.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>RMS table</strong></p></td>
<td><p><strong>Field name</strong></p></td>
<td><p><strong>Field name</strong></p></td>
</tr>
<tr class="even">
<td><p>BATCH</p></td>
<td><p>OpeningTime</p></td>
<td><p>SHIFTDATE</p></td>
</tr>
<tr class="odd">
<td><p>BATCH</p></td>
<td><p>RegisterId</p></td>
<td><p>TERMINAL</p></td>
</tr>
<tr class="even">
<td><p>BATCH</p></td>
<td><p>RegisterId</p></td>
<td><p>CREATEDONPOSTERMINAL</p></td>
</tr>
<tr class="odd">
<td><p>BATCH</p></td>
<td><p>RegisterId</p></td>
<td><p>BATCHTERMINALID</p></td>
</tr>
<tr class="even">
<td><p>CURRENCY</p></td>
<td><p>ExchangeRate</p></td>
<td><p>EXCHRATE</p></td>
</tr>
<tr class="odd">
<td><p>JOURNAL</p></td>
<td><p>TransactionType</p></td>
<td><p>TYPE</p></td>
</tr>
<tr class="even">
<td><p>SHIPTO</p></td>
<td><p>Address</p></td>
<td><p>LOGISTICSPOSTALADDRESS</p></td>
</tr>
<tr class="odd">
<td><p>TENDER</p></td>
<td><p>CurrencyId</p></td>
<td><p>CURRENCY</p></td>
</tr>
<tr class="even">
<td><p>TENDERENTRY</p></td>
<td><p>COUNT(TransactionNumber)</p></td>
<td><p>NUMBEROFPAYMENTLINES</p></td>
</tr>
<tr class="odd">
<td><p>TRANSACTION</p></td>
<td><p>(Total - SalesTax) * (-1)</p></td>
<td><p>NETAMOUNT</p></td>
</tr>
<tr class="even">
<td><p>TRANSACTION</p></td>
<td><p>(Total) * (-1)</p></td>
<td><p>GROSSAMOUNT</p></td>
</tr>
<tr class="odd">
<td><p>TRANSACTION</p></td>
<td><p>BatchNumber</p></td>
<td><p>SHIFT</p></td>
</tr>
<tr class="even">
<td><p>TRANSACTION</p></td>
<td><p>BatchNumber</p></td>
<td><p>BATCHID</p></td>
</tr>
<tr class="odd">
<td><p>TRANSACTION</p></td>
<td><p>CashierID</p></td>
<td><p>STAFF</p></td>
</tr>
<tr class="even">
<td><p>TRANSACTION</p></td>
<td><p>Comment</p></td>
<td><p>COMMENT_</p></td>
</tr>
<tr class="odd">
<td><p>TRANSACTION</p></td>
<td><p>CustomerID</p></td>
<td><p>CUSTACCOUNT</p></td>
</tr>
<tr class="even">
<td><p>TRANSACTION</p></td>
<td><p>StoreID</p></td>
<td><p>STORE</p></td>
</tr>
<tr class="odd">
<td><p>TRANSACTION</p></td>
<td><p>StoreID</p></td>
<td><p>CHANNEL</p></td>
</tr>
<tr class="even">
<td><p>TRANSACTION</p></td>
<td><p>Time</p></td>
<td><p>TRANSDATE</p></td>
</tr>
<tr class="odd">
<td><p>TRANSACTION</p></td>
<td><p>Time</p></td>
<td><p>TRANSTIME</p></td>
</tr>
<tr class="even">
<td><p>TRANSACTION</p></td>
<td><p>Time</p></td>
<td><p>BUSINESSDATE</p></td>
</tr>
<tr class="odd">
<td><p>TRANSACTION</p></td>
<td><p>Total</p></td>
<td><p>PAYMENTAMOUNT</p></td>
</tr>
<tr class="even">
<td><p>TRANSACTION</p></td>
<td><p>TransactionNumber</p></td>
<td><p>TRANSACTIONID</p></td>
</tr>
<tr class="odd">
<td><p>TRANSACTIONENTRY</p></td>
<td><p>COUNT(TransactionNumber)</p></td>
<td><p>NUMBEROFITEMLINES</p></td>
</tr>
<tr class="even">
<td><p>TRANSACTIONENTRY</p></td>
<td><p>SUM(Cost)</p></td>
<td><p>COSTAMOUNT</p></td>
</tr>
<tr class="odd">
<td><p>TRANSACTIONENTRY</p></td>
<td><p>SUM(FullPrice) - SUM(Price)</p></td>
<td><p>DISCAMOUNT</p></td>
</tr>
<tr class="even">
<td><p>TRANSACTIONENTRY</p></td>
<td><p>SUM(Quantity)</p></td>
<td><p>NUMBEROFITEMS</p></td>
</tr>
</tbody>
</table>


## What data is not migrated

Entities that represent RMS functionality that is significantly different in Retail essentials are not migrated. The following entities and functionality are not included in RMS data migration:

  - Reason codes

  - Customer tax groups

  - Roles and privileges

  - Reports

  - Custom fields in migrated entities

  - Store-specific data (any data that is created at a store but not in the headquarters database)

  - Configuration parameters for administrative functions, such as database backup

  - Integration with third-party accounting software

If you want to migrate other entities that are not included by default, or if you want to support custom fields in migrated entities, follow these steps:

1.  Create or modify a target table so that it has the same fields as the entity. For instructions, see [How to: Create Tables](https://technet.microsoft.com/en-us/library/aa882181\(v=ax.60\)).

2.  Create a custom Data Import/Export Framework entity for the RMS entity, based on the table from step 1. For instructions, see [Create a custom target entity for the Data import/export framework (DIXF, DMF)](create-a-custom-target-entity-for-the-data-import-export-framework-dixf-dmf.md).

3.  Migrate data by using the custom entity. For instructions, see [Migrating data using the Data import/export framework (DIXF, DMF)](migrating-data-using-the-data-import-export-framework-dixf-dmf.md).

## Prepare for data migration

Before you can migrate data from RMS to Retail essentials, the Microsoft Dynamics AX Data Import/Export Framework must be present in your Retail essentials installation. Additionally, you must finalize the data in RMS and then make this data available to Microsoft Dynamics AX.

For information about how to add the Data Import/Export Framework to your Retail essentials installation, see [Install Retail essentials at headquarters](install-retail-essentials-at-headquarters.md). After the Data Import/Export Framework is installed, you must configure it. For instructions, see [Install the Data import/export framework (AX 2012 R3)](install-the-data-import-export-framework-ax-2012-r3.md).

To prepare RMS data for migration, follow these steps:

1.  Make sure that all transactions in RMS have been posted. Use one of these options:
    
      - Open the RMS headquarters database in Microsoft SQL Server Management Studio. Open a new query, and run the following command.
        
            select [Document Status], count(*) [Number of Docs] from ReceivablesTransactions 
            group by [Document Status]
            order by [Document Status]
        
        The **Number of Docs** count should be 0 (zero) for every **Document Status** value except **Posted**.
    
      - Open the **ReceivablesTransactions** view, and make sure that all records have a **Document Status** value of **Posted**.

2.  Make a backup of the headquarters database. For instructions, see [Create a Full Database Backup](http://technet.microsoft.com/en-us/library/ms187510.aspx).

3.  Remove access to the headquarters database by setting the database to single-user mode. For instructions, see [Set a Database to Single-user Mode](http://go.microsoft.com/fwlink/?linkid=395213%26clcid=0x409).

4.  Run SQL queries to validate the RMS data and make sure that the data doesn’t have any issues that make it unusable in Microsoft Dynamics AX. We recommend that you check for the following issues:
    
      - Duplicate item IDs
    
      - Blank item IDs
    
      - Item IDs that contain more than 20 characters
    
      - Items that have a blank bar code
    
      - Items that have duplicate bar codes
    
      - Bar codes that include an asterisk (\*)
    
      - Duplicate supplier codes
    
      - Blank supplier codes
    
      - Duplicate customer account numbers
    
      - Blank customer account numbers


> [!NOTE]
> <P>The bar code information is stored in the Alias table in the RMS headquarters database.</P>



If you find any of these issues, you must manually correct the data before you continue with the data migration.

## Migrate data

To migrate RMS data to Retail essentials, follow these steps:

1.  Create an Open Database Connectivity (ODBC) data source to connect to the headquarters database.

2.  Add the ODBC data source to the Data Import/Export Framework.

3.  Configure RMS migration parameters, such as the language and currency.

4.  Initialize the RMS migration entities.

5.  Import the RMS data.

## Create an ODBC data source

To import data from your Retail essentials installation to the RMS headquarters database, you must have an ODBC connection. To create an ODBC connection, follow these steps:

1.  Click **Start** (for Windows 7) or **Search** (for Windows 8), and then enter ODBC in the search box.

2.  Click the **ODBC Data sources** application to open it.

3.  On the **System DSN** tab, click **Add**.

4.  Select the ODBC driver for SQL Server, and then click **Finish**.

5.  Enter a name and description for this connection, and then select the SQL Server instance that hosts the RMS headquarters database. If the server name does not appear in the **Server** field, type it. Click **Next**.

6.  Modify the authentication type or accept the default values, and then click **Next**.

7.  Select **Change the default database to**, and then select the RMS headquarters database in the associated field. If the database name does not appear in the field, type it. Click **Next**.

8.  On the next page of the wizard, accept the default values, and then click **Finish**.

9.  Click **Test Data Source** to validate that the new connection works. If the connection does not work, check the parameters for the connection, and then try again. When the connection works, click **OK**.

## Add the ODBC data source to the Data Import/Export Framework

To add the ODBC data source for the RMS headquarters database to the Data Import/Export Framework, follow these steps:

1.  In Retail essentials, open the **Area Page**.

2.  In **Data Synchronization**, expand **Setup**, expand **Data import export framework**, and then click **Source data formats**.

3.  Click **New**.

4.  In the **Source name** column, enter a name for the data source.

5.  Click **Type**, and then select **ODBC**.

6.  In the **DSN** section, in the **DSN type** field, select System DSN. In the **DSN location** field, select Client. In the **Name** field, select the name of the ODBC connection that you previously created.

7.  Click **Validate** to make sure that the account that is used by the Data Import/Export Framework can connect to the DSN name. If validation fails, check your parameters, and then try again.

8.  Close the form.

## Configure RMS migration parameters

Microsoft Dynamics AX uses the RMS migration parameters to determine some general configuration values for the RMS data, such as the language and currency. To configure RMS migration parameters, follow these steps:

1.  In Retail essentials, open the **Area Page**.

2.  In **Data Synchronization**, expand **Setup**, expand **Data import export framework**, and then click **RMS migration parameters**.

3.  Select the language, country/region, currency, default time zone, and unit values that map to the default values for these parameters in your RMS data. When you have finished, click **Close**.

## Initialize the RMS migration entities

Initialization creates the required Data Import/Export Framework entities and processing groups for your RMS data. To initialize the RMS migration entities, follow these steps:

1.  In Retail essentials, open the **Area Page**.

2.  In **Data Synchronization**, expand **Setup**, expand **Data import export framework**, and then click **Initialize RMS migration entities**.

## Import the data

You must first import the data from the RMS headquarters database to a staging table. You can then migrate the data from the staging table to the target table.

1.  In Retail essentials, open the **Area Page**.

2.  In **Data Synchronization**, expand **Setup**, expand **Data import export framework**, and then click **Processing group**.
    
    The **Processing group** form displays six processing groups, as follows:
    
      - Level 0 Taxes
    
      - Level 1 Stores
    
      - Level 2 Parties
    
      - Level 3 Products
    
      - Level 4 Inventory
    
      - Level 5 Prices and discounts

3.  Select the first processing group, **Level 0 Taxes**, and then click **Entities**. In the **Select entities for processing group** form, examine the list of entities. Determine if the ODBC source data format that you created is selected in the **Source data format** field for all the entities.
    
      - If the source data format that you created is selected for all entities, go to step 4.
    
      - If the source data format that you created is not selected for all entities, select the first entity, change the source data format, and then click **Generate source mapping**. Repeat this step for the remaining entities in the list.

4.  Optional: If you want to see how the RMS data is mapped to the staging table for an entity, select the entity, and then click **Modify source mapping**.

5.  Close the **Select entities for processing group** form.

6.  Select the first processing group again, and then click **Get staging data**.

7.  In the **Create a job ID for the staging data job** form, record the job ID that is generated, and then click **OK**.

8.  In the **Staging data execution form** form, click **Run**.

9.  In the **Staging** form, change any job execution parameters as you require, and then click **OK**. The import process can take several minutes to an hour or more, depending on the volume of data.

10. For the same processing group, click **Copy data to target**.

11. In the **Select a job ID to run** form, in the **Job ID** field, select the job ID that you recorded in step 7, and then click **OK**.

12. In the **Target data execution** form, click **Run**.

13. In the **Target** form, change any job execution parameters as you require, and then click **OK**. The migration process can take several minutes to an hour or more, depending on the volume of data.

14. Repeat steps 3 through 13 for the remaining processing groups, in the order in which they appear in the **Processing group** form.

When you have finished the import process for all processing groups, the RMS migration to Retail essentials is completed.

## Post-migration tasks

After the RMS data is migrated, you must follow these steps to make the RMS data available in Retail essentials.

1.  Post all inventory movement journals. This step provides the starting quantities for the products that are on hand.

2.  Post price/discount agreement journals. This step posts discounts in the system to make them active.

3.  Set payments type for cash. This step maps the migrated cash tender to the cash type in Microsoft Dynamics AX.

4.  Set up Microsoft Dynamics AX 2012 for Retail stores for the stores that are migrated from RMS.

## Post Inventory Movement journals

To post all inventory movement journals, follow these steps:

1.  In Retail essentials, open the **Area Page**, and then click **Inventory management** \> **Counting**.

2.  For each open journal, click **Validate**, and then click **Post**. When you have finished, click **Close**.

## Post Price/Discount Agreement journals

To post price/discount agreement journals, follow these steps:

1.  In Retail essentials, open the **Area Page**, and then click **Merchandising**.

2.  Expand **Pricing and discounts**, and then click **Price/discount agreement journals**.

3.  In the **Price/discount agreement journals** form, in the **Show** field, select Open.

4.  Select the first journal, and then click **Lines**.

5.  In the **Journal lines, price/discount agreement** form, click **Post**.

6.  In the **Price/discount journal posting** form, change any job execution parameters as you require, and then click **OK**.

7.  Repeat steps 4 through 6 for each open journal, and then close the **Price/discount agreement journals** form.

## Set payments type for cash

To set up a payment type for cash, follow these steps:

1.  In Retail essentials, open the **Area Page**, and then click **Channels**.

2.  Expand **Setup**, expand **POS**, and then click **Button grids**.

3.  Select the **Payments** button grid, and then click **Designer**.

4.  Right-click the **Pay cash quick** button, and then click **Button properties**.

5.  Change the value of the **Payment type** field to Cash, and then click **OK**.

## Create Retail stores

For information about how to create a Retail store for each store that is migrated from RMS, see the topics in [Setting up retail stores (Retail essentials)](setting-up-retail-stores-retail-essentials.md).

## See also

[Retail essentials (Retail essentials)](retail-essentials-retail-essentials.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

