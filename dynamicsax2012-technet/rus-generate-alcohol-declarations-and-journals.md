---
title: (RUS) Generate alcohol declarations and journals
TOCTitle: (RUS) Generate alcohol declarations and journals
ms:assetid: 3993b5ae-f8d8-4ba1-8be9-7be1546eb72a
ms:mtpsurl: https://technet.microsoft.com/library/Dn494963(v=AX.60)
ms:contentKeyID: 60513661
author: Khairunj
ms.date: 05/06/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.SalesTableListPage
- Forms.PurchTableListPage
- Forms.SalesTable
- Forms.CustInvoiceJournal
- Forms.PurchTable
- Forms.VendEditInvoice
- Russia
- Forms.AlcoholDailyJournalTable_RU
- Forms.AlcoholDailyTransMovement_RU
- Forms.AlcoholDeclarationJournalTable_RU
- Forms.AlcoholDeclarationJournalTrans_RU
- alcohol declaration
- RU - 00126
- Alcohol declaration journal
- Alcohol declaration journals
- Russian federation
- alcohol journals
- RU - 00055
- alcohol declarations
- alcohol journal
- Daily journal
- alcohol production
- alcohol turnover
- Daily journals
- alcohol production turnover
audience: Application User
ms.search.region: Russia
---

# (RUS) Generate alcohol declarations and journals 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

After you set up parameters for alcohol declarations and journals, you can create and post customer transactions or vendor transactions for alcoholic items. You can create an alcohol declaration and a daily alcohol production turnover journal that contain details about sales, purchases, and the movement of items between company divisions. This information can be classified based on the customer type, vendor type, or alcohol production type.

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Version</strong></p></td>
<td><p>Microsoft Dynamics AX 2012 R2 with cumulative update 7 or later</p></td>
</tr>
<tr class="even">
<td><p><strong>Country/region</strong></p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: Russia</p></td>
</tr>
<tr class="odd">
<td><p><strong>Related setup task</strong></p></td>
<td><p>Set up parameters for alcohol declarations and journals. For more information, see <a href="rus-set-up-parameters-for-alcohol-declarations-and-journals.md">(RUS) Set up parameters for alcohol declarations and journals</a>.</p></td>
</tr>
</tbody>
</table>


## 1\. Create and post a purchase order for alcoholic items

Use the **Purchase order** form to create and post a purchase order for alcoholic items. When you post the purchase order, you can use the **Alcohol license** field to specify the vendor’s alcohol license number.

To create and post the purchase order, follow these steps:

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Create a purchase order. For more information, see [(RUS) Create and post a purchase order based on an inventory profile](rus-create-and-post-a-purchase-order-based-on-an-inventory-profile.md).

3.  On the **Action pane**, on the **Invoice** tab, in the **Generate** action group, click **Invoice**.

4.  On the **Lines** FastTab, in the **Alcohol license** field, select the alcohol license to use for the invoice line. You can modify the vendor’s alcohol license for an invoice line by using the **Invoice journal** form.

5.  Post the purchase order.

## 2\. Create and post a sales order for alcoholic items

Use the **Sales order** form to create and post a sales order for alcoholic items. When you post the sales order, you can use the **Alcohol license** field to specify the customer’s alcohol license.

To create and post the sales order, follow these steps:

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Create a sales order. For more information, see [(RUS) Create and post a sales order based on an inventory profile](rus-create-and-post-a-sales-order-based-on-an-inventory-profile.md).

3.  On the **Action pane**, on the **Invoice** tab, in the **Journals** action group, click **Invoice**.

4.  In the **Invoice journal** form, on the **Lines** tab, in the **Alcohol license** field, select the alcohol license for the invoice line, and then close the form.

5.  Post the sales order. For more information, see [(RUS) Post a customer invoice for a sales order](rus-post-a-customer-invoice-for-a-sales-order.md).

## 3\. Create an alcohol declaration

After you post the invoices for alcohol transactions, you can use the **Alcohol declaration journal** form to create an alcohol declaration. Before you generate the alcohol declaration, you must change the session date in Microsoft Dynamics AX to the last date of the period to create the declaration for.

To create the alcohol declaration, follow these steps:

1.  Click **Inventory management** \> **Journals** \> **Alcohol declaration** \> **Alcohol declaration journal**.

2.  Click **New** to create a record.

3.  In the **Journal number** and **Journal** fields, enter the identification number and a description of the journal.

4.  In the **Period type** field, select **Quarter** or **Year**.

5.  In the **Period number** field, enter the quarter that the declaration is created for.
    

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>Quarter</STRONG> in the <STRONG>Period type</STRONG> field.</P>



6.  In the **Reporting year** field, enter the year that the declaration is created for.

7.  Click **Lines** to open the **Alcohol declaration journal lines** form, and then click **Yes** to automatically create journal lines for the alcohol declaration.

8.  Click **Separate divisions**, and then click **New** to create a line.

9.  Select the **Mark** check box to include journal lines in the declaration.

10. In the **Separate division ID** field, select the company division to assign to the journal line.

11. In the **Status** field, select **Calculated** or **Not calculated**.

12. Click **Print**, and then click the option to specify which alcohol declarations to print. Use the following table to decide what to print.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Option</p></th>
    <th><p>Considerations</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Print current</strong></p></td>
    <td><p>Click this option to print the alcohol declaration for the current line.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Print all</strong></p></td>
    <td><p>Click this option to print the alcohol declaration for all of the lines.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Print all selected</strong></p></td>
    <td><p>Click this option to print the alcohol declaration for the lines for which the <strong>Mark</strong> check box is selected.</p></td>
    </tr>
    </tbody>
    </table>


You can also include a corrective alcohol declaration to correct a declaration that was incorrectly processed for a previous period. You can enter the details of the corrective alcohol declaration in the following fields.

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
<td><p><strong>Corrected period</strong></p></td>
<td><p>Enter the quarter that the corrective declaration is included for.</p></td>
</tr>
<tr class="even">
<td><p><strong>Corrected year</strong></p></td>
<td><p>Enter the year for the quarter that you entered in the <strong>Corrected period</strong> field.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Correction number</strong></p></td>
<td><p>Enter the journal number of the declaration to correct.</p></td>
</tr>
</tbody>
</table>


## 4\. Create a daily journal of alcohol production turnover

Use the **Daily journal of alcohol production turnover** form to create a daily journal for alcohol production turnover.

To create the daily journal of alcohol production turnover, follow these steps:

1.  Click **Inventory management** \> **Journals** \> **Alcohol declaration** \> **Journal of alcohol production turnover**.

2.  Click **New** to create a record.

3.  In the **Date** field, enter the date to generate the daily journal for.

4.  In the **Separate division ID** field, select the separate company division to include in the daily journal.

5.  In the **Journal type** field, select the journal type to include in the daily journal.

6.  In the **Status** field, select **Calculated** or **Not calculated**.

7.  Click **Print** \> **Print current** to print the daily journal of alcohol production turnover.

## Next step

You have finished creating and posting invoices for alcohol production and sales, and creating the alcohol declaration. You can now generate an electronic document for an alcohol declaration. For more information, see [(RUS) Set up and generate an electronic document for an alcohol declaration](rus-set-up-and-generate-an-electronic-document-for-an-alcohol-declaration.md).

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.


<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Configuration keys</strong></p></td>
<td><p>Ensure that you select the <strong>Trade</strong> (LogisticsBasic) configuration key</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>To perform this task, you must be a member of a security role that includes the duties that are described in the following table.</p>
<div class="caption">
</div>
<div class="tableSection">
<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Duty</p></th>
<th><p>Name</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Enable alcohol declaration process</strong></p></td>
<td><p>AlcoholDeclarationProcessEnable_RU</p></td>
</tr>
<tr class="even">
<td><p><strong>Inquire into alcohol declaration data</strong></p></td>
<td><p>AlcoholDeclarationDataInquire_RU</p></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To perform this task, you must be a member of a security role that includes the privileges that are described in the following table.</p>
<div class="caption">

</div>
<div class="tableSection">
<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Privilege</p></th>
<th><p>Name</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Maintain alcohol declaration data</strong></p></td>
<td><p>AlcoholDeclarationMaintain_RU</p></td>
</tr>
<tr class="even">
<td><p><strong>View alcohol declaration data</strong></p></td>
<td><p>AlcoholDeclarationView_RU</p></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
</tbody>
</table>

  


