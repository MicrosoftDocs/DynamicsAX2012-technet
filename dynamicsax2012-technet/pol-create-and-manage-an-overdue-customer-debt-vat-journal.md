---
title: (POL) Create and manage an overdue customer debt VAT journal
TOCTitle: (POL) Create and manage an overdue customer debt VAT journal
ms:assetid: a647a9b5-ec5d-46a7-9e54-28311173f115
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn753712(v=AX.60)
ms:contentKeyID: 62485056
ms.date: 06/14/2014
mtps_version: v=AX.60
f1_keywords:
- VAT
- Forms.CustOverdueVATJournalTable_W
- overdue customer debt
- overdue payment
- overdue payments
---

# (POL) Create and manage an overdue customer debt VAT journal 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create an overdue customer debt VAT journal to identify overdue customer invoice transactions for a reporting period. You can then correct overdue customer VAT payment transactions or reverse the corrected VAT transactions, if necessary. For more information, see [(POL) Overdue payments for VAT transactions](pol-overdue-payments-for-vat-transactions.md).

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
<tr class="odd">
<td><p><strong>Related setup task</strong></p></td>
<td><p>Set up parameters that are used to identify the invoice transactions that are included in the overdue debt VAT journal. For more information, see <a href="pol-set-up-overdue-debt-vat-parameters-for-vat-journals.md">(POL) Set up overdue debt VAT parameters for VAT journals</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Related transaction</strong></p></td>
<td><p>Create a customer payment journal. For more information, see <a href="https://technet.microsoft.com/en-us/library/aa556141(v=ax.60)">Journal voucher - Customer payment journal (form)</a>.</p></td>
</tr>
</tbody>
</table>


## Create and post an overdue customer debt VAT journal

Use the **Overdue debt VAT** list page to create an overdue customer debt VAT journal for a reporting period that you specify.

To perform this task, follow these steps:

1.  Click **Accounts receivable** \> **Periodic** \> **Overdue debt** \> **Overdue debt VAT**.

2.  On the **Action Pane**, on the **Overdue customer debt VAT journal** tab, click **New journal** to create a journal.

3.  In the **Customer overdue debt VAT calculation** form, in the **Date** field, specify the date when the debt amount is calculated. The date is used to calculate the reporting period of the journal in the **From date** and **To date** fields based on the parameters that you set up in the **Overdue debt journal calculation setup** form.

4.  Click **OK** to create the journal in the **Overdue debt VAT** list page. The journal contains a list of overdue VAT paid invoices and overdue VAT unpaid invoices for the reporting period.

5.  In the **Overdue debt VAT** list page, select the journal, and then click **Edit** to identify the overdue customer debt invoices for the reporting period.

6.  In the **Overdue customer debt VAT lines** form, on the **Overdue debt VAT journal lines** FastTab, verify the values in the **Paid amount** and **Paid tax amount** fields in the customer invoices.

7.  Select the **Exclude** check box to exclude customer invoices from the overdue debt list.
    

    > [!NOTE]
    > <P>You cannot exclude overdue customer invoices for which you have already posted input VAT corrections and made payments to the vendor.</P>



8.  Optional: On the **Overdue debt VAT journal header** FastTab, verify the cumulative overdue amount and the overdue tax amount of all overdue invoices that were not paid during the reporting period.

9.  Click **Post** to create a reverse transaction of the invoices that are included in the journal. In the **Overdue debt VAT** form, the **Posted** check box is selected for the journal.

## Correct or reverse an invoice with overdue customer payments

Use the **Overdue debt VAT** list page to correct or reverse an invoice that has overdue customer payments.

To perform this task, follow these steps:

1.  Click **Accounts receivable** \> **Periodic** \> **Overdue debt** \> **Overdue debt VAT**.

2.  In the **Overdue debt VAT** list page, select the journal that you want to correct, and then click **Edit**.

3.  In the **Overdue customer debt VAT lines** form, on the **Overdue debt VAT journal lines** FastTab, select the **Exclude** check box to exclude customer invoices from the overdue debt VAT list.

4.  On the **Action Pane**, in the **Post** group, click **Cancel**.
    

    > [!NOTE]
    > <P>You can only cancel the most recently posted journal.</P>



5.  In the **Cancel the posting of the overdue VAT journal** dialog box, perform one of the following actions:
    
    1.  Select the **Correction** check box to correct the selected invoices in the journal, and then click **OK**.
    
    2.  Clear the **Correction** check box to reverse the selected invoices in the journal, and then click **OK**.
    
    In the **Overdue debt VAT** list page, the **Canceled** check box is selected for the journal.

## Related tasks

[(POL) Create and manage an overdue vendor debt VAT journal](pol-create-and-manage-an-overdue-vendor-debt-vat-journal.md)

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
<td><p>To create and manage an overdue customer debt VAT journal, you must be a member of a security role that includes the following duties:</p>
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
<td><p><strong>Inquire about customer overdue debt VAT journals</strong></p></td>
<td><p>CustOverdueVATJournalInquire_W</p></td>
</tr>
<tr class="even">
<td><p><strong>Maintain customer overdue debt VAT journals</strong></p></td>
<td><p>CustOverdueVATJournalMaintain_W</p></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To create and manage an overdue customer debt VAT journal, you must be a member of a security role that includes the following privileges:</p>
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
<td><p><strong>Create customer overdue debt VAT journals</strong></p></td>
<td><p>CustOverdueVATJournalCreate_W</p></td>
</tr>
<tr class="even">
<td><p><strong>View customer overdue debt VAT journals</strong></p></td>
<td><p>CustOverdueVATJournalView_W</p></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

