---
title: (POL) Set up overdue debt VAT parameters for VAT journals
TOCTitle: (POL) Set up overdue debt VAT parameters for VAT journals
ms:assetid: c22b9e36-df1f-4096-b523-9ae750cb6f9f
ms:mtpsurl: https://technet.microsoft.com/library/Dn716014(v=AX.60)
ms:contentKeyID: 62200257
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Poland
---

# (POL) Set up overdue debt VAT parameters for VAT journals 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Follow the steps in this topic to set up the following information for overdue debt value-added tax (VAT) journals:

  - Offset accounts to post reversed incoming and outgoing VAT

  - Number sequences for overdue debt VAT journals

  - Parameters that are used to identify the invoice transactions that are included in the overdue debt VAT journal

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
<td><ul>
<li><p>Set up sales tax codes for standard and reduced VAT. For more information, see <a href="set-up-and-use-sales-tax-codes.md">Set up and use sales tax codes</a>.</p></li>
<li><p>Set up a sales tax type for overdue debt VAT journals. For more information, see <a href="pol-set-up-vat-types.md">(POL) Set up VAT types</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## 1\. Set up a ledger posting group for overdue debt VAT journals

Use the **Ledger posting groups** form to set up a ledger posting group that contains the offset accounts to which the reversed incoming and outgoing taxes are posted.

To perform this task, follow these steps:

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Ledger posting groups**.

2.  Select or create a ledger posting group. For more information, see [Ledger posting groups (form)](https://technet.microsoft.com/library/aa598801\(v=ax.60\)).

3.  On the **General** tab, in the **Offset reversed incoming tax** field, select the offset account to post the reversed incoming tax to.

4.  In the **Offset reversed outgoing tax** field, select the offset account to post the reversed outgoing tax to.

## 2\. Set up number sequences for overdue vendor debt VAT journals

Use the **Accounts payable parameters** form to set up number sequences for overdue vendor debt VAT journals.

To perform this task, follow these steps:

1.  Click **Accounts payable** \> **Setup** \> **Accounts payable parameters**.

2.  Click **Number sequences**, and then in the **Number sequences** area, in the **Number sequence code** field, select a number sequence code for the following references:
    
      - **Journal number for overdue debt VAT**
    
      - **Overdue debt VAT voucher**

## 3\. Set up number sequences for overdue customer debt VAT journals

Use the **Accounts receivable parameters** form to set up number sequences for overdue customer debt VAT journals.

To perform this task, follow these steps:

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  Click **Number sequences**, and then in the **Number sequences** area, in the **Number sequence code** field, select a number sequence code for the following references:
    
      - **Journal number for overdue debt VAT**
    
      - **Overdue debt VAT voucher**

## 4\. Set up the parameters to identify overdue invoice transactions in overdue debt VAT journals

Use the **Overdue debt journal calculation setup** form to set up parameters that are used to identify overdue invoice transactions that are included in the overdue debt VAT journals.

To perform this task, follow these steps:

1.  Click **General ledger** \> **Setup** \> **Overdue debt** \> **Overdue debt journal calculation**.

2.  In the **Overdue debt journal calculation setup** form, click **New** or press CTRL+N to create a record.

3.  In the **Journal type** field, select **Customer VAT journal** or **Vendor VAT journal**.

4.  In the **Minimum number of days** field, enter the minimum number of days past the due date after which the transactions are included in the overdue debt VAT journal.

5.  In the **Maximum number of days** field, enter the maximum number of days past the due date before which the transactions are included in the overdue debt VAT journal.

6.  In the **Calculation type** field, select **Due date** or **Invoice date** to indicate the date that is used to identify overdue invoice transactions.

7.  Select the **Validate** check box to validate transactions before settling them to ensure that the total overdue debt amount is the same as it was on the date when the last overdue debt VAT journal was created.


> [!NOTE]
> <P>You must leave the <STRONG>Condition</STRONG> and <STRONG>Payment term days</STRONG> fields blank.</P>



## Related tasks

[(POL) Post VAT transactions](pol-post-vat-transactions.md)

[(POL) Set up and create an overdue vendor debt CIT and PIT journal](pol-set-up-and-create-an-overdue-vendor-debt-cit-and-pit-journal.md)

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
<td><p>To set up overdue debt calculation for VAT transactions, you must be a member of a security role that includes the following duties:</p>
<div class="caption">
</div>
<div class="tableSection">
<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Duty</p></th>
<th><p>Name</p></th>
<th><p>Procedure</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Inquire about customer overdue debt VAT journals</strong></p></td>
<td><p>CustOverdueVATJournalInquire_W</p></td>
<td><p>View customer overdue debt VAT journals</p></td>
</tr>
<tr class="even">
<td><p><strong>Maintain customer overdue debt VAT journals</strong></p></td>
<td><p>CustOverdueVATJournalMaintain_W</p></td>
<td><p>Create customer overdue debt VAT journals</p>
<p>View customer overdue debt VAT journals</p>
<p>Post overdue debt VAT journals</p></td>
</tr>
<tr class="odd">
<td><p><strong>Inquire about vendor overdue debt VAT journals</strong></p></td>
<td><p>VendOverdueVATJournalInquire_W</p></td>
<td><p>View vendor overdue debt VAT journals</p></td>
</tr>
<tr class="even">
<td><p><strong>Maintain vendor overdue debt VAT journals</strong></p></td>
<td><p>VendOverdueVATJournalMaintain_W</p></td>
<td><p>Create vendor overdue debt VAT journals</p>
<p>View vendor overdue debt VAT journals</p>
<p>Post overdue debt VAT journals</p></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To set up overdue debt calculation for VAT transactions, you must be a member of a security role that includes the following privileges:</p>
<div class="caption">

</div>
<div class="tableSection">
<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Privilege</p></th>
<th><p>Name</p></th>
<th><p>Procedure</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Create customer overdue debt VAT journals</strong></p></td>
<td><p>CustOverdueVATJournalCreate_W</p></td>
<td><p>Open Journal form</p>
<p>Open Counting form</p>
<p>Open journal list page</p>
<p>Switch journal to edit mode</p>
<p>View totals on journal</p>
<p>Open setup form</p>
<p>Create new debt journal</p></td>
</tr>
<tr class="even">
<td><p><strong>View customer overdue debt VAT journals</strong></p></td>
<td><p>CustOverdueVATJournalView_W</p></td>
<td><p>Open Journal form</p>
<p>Open Counting form</p>
<p>Open journal list page</p>
<p>Switch journal to edit mode</p>
<p>View totals on journal</p>
<p>Open setup form</p>
<p>Create new debt journal</p>
<p>Create new debt journal</p></td>
</tr>
<tr class="odd">
<td><p><strong>Create vendor overdue debt VAT journals</strong></p></td>
<td><p>VendOverdueVATJournalCreate_W</p></td>
<td><p>Open Journal form</p>
<p>Open Counting form</p>
<p>Open journal list page</p>
<p>Switch journal to edit mode</p>
<p>View totals on journal</p>
<p>Open setup form</p>
<p>Create new debt journal</p></td>
</tr>
<tr class="even">
<td><p><strong>View vendor overdue debt VAT journals</strong></p></td>
<td><p>VendOverdueVATJournalView_W</p></td>
<td><p>Open Journal form</p>
<p>Open Counting form</p>
<p>Open journal list page</p>
<p>Switch journal to edit mode</p>
<p>View totals on journal</p>
<p>Open setup form</p></td>
</tr>
<tr class="odd">
<td><p><strong>Post overdue debt VAT journals</strong></p></td>
<td><p>OverdueVATJournalPost_W</p></td>
<td><p>Post journal of overdue debt</p>
<p>Cancel posting of journal of overdue debt</p></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
</tbody>
</table>

  


