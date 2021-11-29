---
title: Import and create one-time vendors and invoices (Public sector)
TOCTitle: Import and create one-time vendors and invoices (Public sector)
ms:assetid: 5ed26477-32df-4a8d-9e37-aa851c8287df
ms:mtpsurl: https://technet.microsoft.com/library/Dn762313(v=AX.60)
ms:contentKeyID: 63384521
author: Khairunj
ms.date: 04/01/2019
mtps_version: v=AX.60
f1_keywords:
- invoices
- vendors
- Forms.SysOperationTemplateForm
- vendor invoices
- create vendors
- one-time vendor
- import invoices
- import vendors
audience: Application User
ms.search.region: Denmark, France
---

# Import and create one-time vendors and invoices (Public sector) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

You might have a situation where you have to create multiple invoices for new vendors with whom you have no regular relationship. If neither approval nor a purchase order is required, you can quickly create invoices at the same time as you create records for the vendors. For example, you might want to support vendor payments for jury duty, registration payments, and customer refunds or other payments where master vendor records do not exist.


> [!NOTE]
> <P>This feature is available only if Microsoft Dynamics AX 2012 R3 Cumulative Update 8 is installed, and if the <STRONG>Public Sector</STRONG> configuration key is selected.</P>



To create multiple one-time vendors and invoices, you first create a file that contains the vendor and invoice information, and then import it into a staging table in AX 2012 R3 CU8. Then you process the imported file and generate the invoices. The import file must be in CSV format (comma-separated values).

Typically you create the data file in spreadsheet format and save it in CSV format. Each field label in the following table is equivalent to a column heading in a spreadsheet, and each spreadsheet row contains the data for each applicable column.

Because commas are used to separate the fields in a CSV file, do not use commas in the text of an entry. For example, if you want to specify a company name of “Smith, Smith, and Jones,” enter it as “Smith Smith and Jones”.

  - For any fields in this form that you don’t enter new values into, the newly created vendor accounts will use values from the one-time vendor profile that is referenced in the **Accounts payable parameters** form. For example, if the one-time vendor profile in the parameters form has a method of payment set to **Check**, then the one-time vendors you are adding will have that method of payment set.

  - The **One-time supplier** Accounts Payable number sequence is used to assign the one-time vendor accounts and must not be set to **Continuous** for this service. For more information about how to set up number sequences, see [Set up number sequences](set-up-number-sequences.md).

  - Invoices are generated in a draft state. Before creating payment proposals for payment, you must post the invoices.

  - You can also quickly create a single one-time vendor and invoice. For more information, see [Create a one-time vendor and invoice (Public sector)](create-a-one-time-vendor-and-invoice-public-sector.md).

[Follow this link to download a sample CSV file.](https://www.microsoft.com/en-us/download/details.aspx?id=58104)


> [!NOTE]
> <P>This file is provided in English only. If you translate the file, the label text in the CSV file must match your translation of the field labels in the following tables.</P>



The following tables show the fields that the import file must contain.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Vendor section</p></th>
<th><p> </p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Field</strong></p></td>
<td><p><strong>Details</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Record type</strong></p></td>
<td><p><strong>Person</strong>/<strong>Organization</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>First name</strong></p></td>
<td><p>(If record type is <strong>Person</strong>)</p></td>
</tr>
<tr class="even">
<td><p><strong>Middle name</strong> (Optional)</p></td>
<td><p>(If record type is <strong>Person</strong>)</p></td>
</tr>
<tr class="odd">
<td><p><strong>Last name</strong></p></td>
<td><p>(If record type is <strong>Person</strong>)</p></td>
</tr>
<tr class="even">
<td><p><strong>Vendor name</strong></p></td>
<td><p>(If record type is <strong>Organization</strong>)</p></td>
</tr>
<tr class="odd">
<td><p><strong>Group</strong></p></td>
<td><p>10-character limit</p></td>
</tr>
<tr class="even">
<td><p><strong>Country/region</strong></p></td>
<td><p>10-character limit</p></td>
</tr>
<tr class="odd">
<td><p><strong>ZIP/postal code</strong></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Street</strong></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>City</strong></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>City</strong></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Federal tax ID</strong> (Optional)</p></td>
<td><p>(U.S.-only) 1099 number</p></td>
</tr>
<tr class="even">
<td><p><strong>Tax ID type</strong></p></td>
<td><p>(U.S.-only) Values can be <strong>Unknown</strong>, <strong>Employer Identification Number</strong>, <strong>Social Security Number</strong>, <strong>Individual Taxpayer Identification Number</strong>, or <strong>Adopted Tax Payer Identification Number</strong>.</p>
<div class="alert">

> [!NOTE]
> <P>If no <STRONG>Federal tax ID</STRONG> is provided, the Tax ID type should have a value of <STRONG>Unknown</STRONG>.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Bank account</strong> (Optional)</p></td>
<td><p>Bank account name</p></td>
</tr>
<tr class="even">
<td><p><strong>Bank account number</strong></p></td>
<td></td>
</tr>
<tr class="odd">
<td><p><strong>Routing number</strong> (Optional)</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>SWIFT code</strong> (Optional)</p></td>
<td><p>Also known as BIC (Bank identifier code)</p></td>
</tr>
<tr class="odd">
<td><p><strong>IBAN</strong> (Optional)</p></td>
<td><p>International bank account number; 34-character limit</p></td>
</tr>
</tbody>
</table>


<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Invoice section</p></th>
<th><p> </p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Field</strong></p></td>
<td><p><strong>Details</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Invoice number</strong></p></td>
<td><p>Invoice number; 20-character limit</p></td>
</tr>
<tr class="odd">
<td><p><strong>Invoice description</strong> (Optional)</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Posting date</strong> (Optional)</p></td>
<td><p>Date format</p></td>
</tr>
<tr class="odd">
<td><p><strong>Invoice date</strong></p></td>
<td><p>Date format</p></td>
</tr>
<tr class="even">
<td><p><strong>Due date</strong> (Optional)</p></td>
<td><p>Date format</p></td>
</tr>
<tr class="odd">
<td><p><strong>Line number</strong></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Item number</strong> (Optional)</p></td>
<td><p>20-character limit</p>
<div class="alert">

> [!NOTE]
> <P>If you provide no item number, you must provide values in the <STRONG>Procurement category</STRONG> and <STRONG>Procurement category hierarchy</STRONG> fields. If no procurement category and procurement category hierarchy values are provided, you must provide an item number.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Item name</strong> (Optional)</p></td>
<td><p>60-character limit</p></td>
</tr>
<tr class="even">
<td><p><strong>Procurement category hierarchy</strong> (Optional)</p></td>
<td><div class="alert">

> [!NOTE]
> <P>If you provide a value for this field, the <STRONG>Procurement category</STRONG> field is also required.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Procurement category</strong> (Optional)</p></td>
<td><div class="alert">

> [!NOTE]
> <P>If you provide a value for this field, the <STRONG>Procurement category hierarchy</STRONG> field is also required.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Quantity</strong> (Optional)</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Unit</strong> (Optional)</p></td>
<td><p>10-character limit</p></td>
</tr>
<tr class="even">
<td><p><strong>Line net amount</strong></p></td>
<td><p>Decimals allowed</p></td>
</tr>
<tr class="odd">
<td><p><strong>Unit price</strong> (Optional)</p></td>
<td><p>Decimals allowed</p></td>
</tr>
<tr class="even">
<td><p><strong>Reservation line</strong> (Optional)</p>
<div class="alert">

> [!NOTE]
> <P>If the file you import has a <STRONG>Unit price</STRONG> column but you have not enabled general budget reservations, an error message will appear, stating that the number of columns is not valid. You’ll then need to either enable general budget reservations or remove the column from the file.</P>


</div></td>
<td><div class="alert">

> [!NOTE]
> <P>General budget reservations are available only if the <STRONG>Public Sector</STRONG> configuration key is selected and if Microsoft Dynamics AX 2012 R3 Cumulative Update 8 is installed with the following hotfix: KB3047235</P>


</div></td>
</tr>
</tbody>
</table>


<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Distributions section</p></th>
<th><p> </p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Field</strong></p></td>
<td><p><strong>Details</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Number</strong></p></td>
<td><p>Accounting distribution line number</p></td>
</tr>
<tr class="odd">
<td><p><strong>Financial Dimensions</strong></p></td>
<td><p>[!NOTE]</p>
  <p>If the file you import has financial dimensions, you need to include all of the financial dimensions with the proper naming, otherwise an error message will appear stating that the ledger dimension is invalid. You’ll then need to either correct the financial dimensions or remove the columns from the file.</p></td>
</tr>
<tr class="even">
<td><p><strong>Percent</strong></p></td>
<td><p>Decimals allowed</p></td>
</tr>
</tbody>
</table>


## Import and process multiple one-time vendors and invoices

Use the following steps to create multiple one-time vendors and invoices.

1.  Click **Accounts payable \> Area page \> Periodic \> Import one-time vendors and invoices**.
    

    > [!WARNING]
    > <P>Importing a new file overwrites any records that have been imported but not processed, and the invoices for those vendors will not be created. To check whether unprocessed records exist, click <STRONG>Cancel</STRONG>, and then click <STRONG>Process one-time vendors and generate invoices</STRONG>. Then continue with the following step.</P>



2.  In the **Import one-time vendors and invoices** form, in the **File name** field, specify the file that contains the vendor and invoice information.

3.  In the **Account structure** list, select the account structure you want to assign to the imported invoice ledger accounts.

4.  Click **Import**. The vendor and invoice information is imported.
    
    If there are errors, a report will be printed. Correct any listed entries in the import file, and then reimport the file.

5.  When the report is satisfactory, click **Close**.

6.  Click **Accounts payable \> Area page \> Periodic \> Process one-time vendors and generate invoices**.

7.  Under **Parameters**, select whether you want to process vendor records for vendors who already have a record in your system.
    

    > [!IMPORTANT]
    > <P>If you choose not to process duplicate vendors, the related invoices will not be processed either. You can manually create an invoice by using the information in the CSV file.</P>
    > <P>Microsoft Dynamics AX looks for duplicate vendor names or Federal tax IDs.</P>



8.  Optional: You can modify the batch process that will run. Click the **Batch** tab, and then change any settings you want.

9.  Click **Process**.
    
    An Infolog message appears when the process has run successfully

10. Optional: You can use AX reports to view and print a list of the added one-time vendors and invoices by creation date.

## See also

[Key tasks: Vendor invoices](key-tasks-vendor-invoices.md)

  


