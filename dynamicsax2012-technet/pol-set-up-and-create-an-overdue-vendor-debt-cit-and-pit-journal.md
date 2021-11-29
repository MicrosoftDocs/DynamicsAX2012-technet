---
title: (POL) Set up and create an overdue vendor debt CIT and PIT journal
TOCTitle: (POL) Set up and create an overdue vendor debt CIT and PIT journal
ms:assetid: 0e09506c-f82d-4423-9734-67301b60a15a
ms:mtpsurl: https://technet.microsoft.com/library/Dn532269(v=AX.60)
ms:contentKeyID: 59930769
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- vendor payments
- vendor payment
- Forms.VendParameters
- Poland
- CIT
- CIT and PIT
- Classes.VendOverdueCITPITJournalCreate_W
- Forms.OverdueJournalSettings_W
- Forms.VendOverdueCITPITJournalTable_W
- Forms.VendOverdueCITPITJournalTableListPage_W
- overdue debt
- overdue journal
- PIT
- PL - 00014
- SSRS_Reports.Reports.VendOverdueCITPITReport_W
- Tax adjustment
- Tax adjustments
- Tax cost adjustment
- Tax cost adjustments
- MsDynAx060.Forms.VendParameters
- MsDynAx060.Forms.OverdueJournalSettings_W
- MsDynAx060.Forms.VendOverdueCITPITJournalTable_W
- MsDynAx060.Forms.VendOverdueCITPITJournalTableListPage_W
audience: Application User
ms.search.region: Poland
---

# (POL) Set up and create an overdue vendor debt CIT and PIT journal 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can set up the parameters that are used to identify the transactions that are included in the overdue vendor debt Corporate Income Tax (CIT) and Personal Income Tax (PIT) journal. You can then create an overdue vendor debt CIT and PIT journal for a period that you specify. The journal contains the following information:

  - A list of overdue payments that require tax cost adjustments. You can manually adjust tax costs for these payments.

  - A list of payments that were overdue, for which tax cost was adjusted previously, and you made the payments to the vendors. You can reverse the tax cost adjustments for these payments.

You can exclude debts from the list of overdue payments. You can generate the Overdue CIT and PIT journal report that contains the details about the overdue payments and tax cost adjustments.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>



Follow the steps in this topic to set up parameters for overdue vendor debt CIT and PIT journals, and then create a journal.

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
<td><p>The primary address for the legal entity must be in the following countries/regions: Poland</p></td>
</tr>
</tbody>
</table>


## 1\. Set up parameters for overdue vendor debt CIT and PIT journals

Use the **Overdue debt journal calculation setup** form to set up parameters that are used to identify transactions for overdue vendor debt CIT and PIT journals.

To perform this task, follow these steps:

1.  Click **General ledger** \> **Setup** \> **Overdue debt** \> **Overdue debt journal calculation**.

2.  Click **New** or press CTRL+N to create a record.

3.  In the **Journal type** field, select **Vendor CIT and PIT journal** as the type of journal that uses this calculation setup.

4.  In the **Minimum number of days** field, enter the minimum number of days past the due date after which the transactions are included in the overdue vendor debt CIT and PIT journal.

5.  In the **Maximum number of days** field, enter the maximum number of days past the due date before which the transactions are included in the overdue vendor debt CIT and PIT journal.

6.  In the **Calculation type** field, select a method that is used to identify the transactions.
    
    Select from the following options:
    
      - **Due date** – The transactions are identified using the payment due date.
    
      - **Invoice date** – The transactions are identified using the shipment date.

7.  In the **Condition** field, select an operator that specifies the condition that is used to compare the dates for the calculation setup.

8.  In the **Payment term days** field, enter the number of days for the payment term.

9.  Select the **Validate** check box to validate transactions before settling them. If this check box is selected and an invoice is included in an existing overdue vendor debt CIT and PIT journal, then you cannot settle or unsettle the invoice with a payment. You must delete the overdue vendor CIT and PIT journal that the invoice is associated with before you settle or unsettle the invoice with a payment.

## 2\. Set up the dimension and number sequence for overdue vendor debt CIT and PIT journals

Use the **Accounts payable parameters** form to set up the dimension and number sequence that are used for overdue vendor debt CIT and PIT journals.

To perform this task, follow these steps:

1.  Click **Accounts payable** \> **Setup** \> **Accounts payable parameters**.

2.  Click **Ledger and sales tax**, and then in the **Ledger and sales tax** area, on the **Corporate Income Tax (CIT) and Personal Income Tax (PIT)** FastTab, in the **Dimension to calculate the CIT and PIT correction** field, select the dimension that is used to distribute overdue amounts in overdue vendor debt CIT and PIT journals.

3.  Click **Number sequences**, and then in the **Number sequences** area, in the **Number sequence code** field, select a number sequence code for the **Overdue debt CIT and PIT journal** reference.

## 3\. Create an overdue vendor debt CIT and PIT journal

Use the **Create overdue CIT and PIT journals** form to create an overdue vendor debt CIT and PIT journal for a period.

To perform this task, follow these steps:

1.  Click **Accounts payable** \> **Periodic** \> **Overdue debt** \> **Overdue vendor debt CIT and PIT journals**.

2.  Click **New journal** or press CTRL+N to create a journal.

3.  In the **Create overdue CIT and PIT journals** form, in the **Date** field, select the last date of the journal reporting period, and then verify the calculation type, from date, and to date based on the parameters that you set up.

4.  Click **OK** to create a journal in the **Overdue vendor debt CIT and PIT journal** form.

5.  In the **Overdue vendor debt CIT and PIT journal** form, verify the journal numbers, transaction details, overdue amounts, paid amounts, and transaction dates for the overdue vendor debts.
    
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
    <td><p><strong>Journal number</strong></p></td>
    <td><p>The identification number of the journal that is used for overdue debt.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Date</strong></p></td>
    <td><p>The transaction date.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Description</strong></p></td>
    <td><p>A brief description of the journal.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Approved</strong></p></td>
    <td><p>If this check box is selected, the journal is approved.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Overdue amount</strong></p></td>
    <td><p>The overdue debt amount in the accounting currency.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Paid amount</strong></p></td>
    <td><p>The paid debt amount, including the tax amount, for the previously reversed tax.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Vendor account</strong></p></td>
    <td><p>The account number of the vendor who is associated with the journal line.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Name</strong></p></td>
    <td><p>The name of the vendor who is associated with the journal line.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Invoice</strong></p></td>
    <td><p>The invoice number that the transaction is associated with.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Voucher</strong></p></td>
    <td><p>The voucher number that the transaction is associated with.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Due date</strong></p></td>
    <td><p>The due date of the transaction.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Exclude</strong></p></td>
    <td><p>Select this check box to exclude a debt from the list of overdue payments.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Registration number</strong></p></td>
    <td><p>The registration number of the vendor.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Number</strong></p></td>
    <td><p>The invoice number that the transaction is associated with.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Document date</strong></p></td>
    <td><p>The date of the document for which the transaction is created.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Document</strong></p></td>
    <td><p>The number of the document for which the transaction is created.</p></td>
    </tr>
    </tbody>
    </table>


You can click **Print report** to generate the **Overdue CIT and PIT journal report**, which contains the details about the overdue payments and tax cost adjustments.

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
<td><p>No configuration key is required for this task.</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>To set up and create an overdue vendor debt CIT and PIT journal, you must be a member of a security role that includes the following duties:</p>
<ul>
<li><p><strong>Inquire about overdue vendor debt CIT and PIT journals</strong> (VendOverdueCITPITJournalInquire_W)</p></li>
<li><p><strong>Maintain overdue vendor debt CIT and PIT journals</strong> (VendOverdueCITPITJournalMaintain_W)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To set up and create an overdue vendor debt CIT and PIT journal, you must be a member of a security role that includes the following privileges:</p>
<ul>
<li><p><strong>View overdue vendor debt CIT and PIT journals</strong> (VendOverdueCITPITJournalCreate_W)</p></li>
<li><p><strong>View vendor overdue debt CIT and PIT journals</strong> (VendOverdueCITPITJournalView_W)</p></li>
<li><p><strong>Generate overdue vendor debt CIT and PIT journal reports</strong> (VenndOverdueCITPITReportGenerate_W)</p></li>
</ul></td>
</tr>
</tbody>
</table>

  


