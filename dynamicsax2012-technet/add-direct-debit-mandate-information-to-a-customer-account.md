---
title: Add direct debit mandate information to a customer account
TOCTitle: Add direct debit mandate information to a customer account
ms:assetid: c2f241a3-1fc8-43b0-b3aa-89dd63c06163
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn268416(v=AX.60)
ms:contentKeyID: 54916954
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- customer
- Forms.CustTableListPage
- direct debit
- Forms.CustTable
- SEPA
- mandate
---

# Add direct debit mandate information to a customer account 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Before you can draw Single Euro Payment Area (SEPA) direct debit payments for customers who have a mandate, you must enter information about the mandate. This topic explains how to add information about a direct debit mandate to a customer account, and how to print, scan, or cancel a mandate, if you need to.


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed for Microsoft Dynamics AX 2012 R3, AX 2012 R2 with the hotfix in <A href="https://mbs2.microsoft.com/knowledgebase/kbdisplay.aspx?scid=kb%3ben-us%3b2902097">KB2902097</A>, and AX 2012 with the hotfix in <A href="https://mbs2.microsoft.com/knowledgebase/kbdisplay.aspx?scid=kb%3ben-us%3b2902097">KB2902097</A>.</P>



The following illustration shows the process of adding information about direct debit mandates to a customer account. The numbers correspond to the procedures later in this topic.

![Add SEPA direct debit mandate to customer](images/Dn268416.SEPA_DD_Mandate_Add_Customer(AX.60).gif "Add SEPA direct debit mandate to customer")

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
<td><p>Microsoft Dynamics AX 2012 R3 or cumulative update 6 or later for AX 2012 R2, or AX 2012</p></td>
</tr>
<tr class="even">
<td><p><strong>Country/region</strong></p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: Austria, Belgium, Germany, Spain, France, Italy, or the Netherlands</p></td>
</tr>
<tr class="odd">
<td><p><strong>Set up task</strong></p></td>
<td><p>Set up SEPA direct debit mandates. For more information, see <a href="set-up-sepa-direct-debit-mandate.md">Set up SEPA direct debit mandate</a>.</p></td>
</tr>
</tbody>
</table>


## 1\. Add direct debit mandate information to a customer account

Before you can draw direct debit payments for customers who have a mandate, you must enter information about the mandate. Usually, only one mandate is in effect at a time for a customer. Therefore, a message is displayed if you try to enter a second mandate for the same customer.

To add direct debit mandate information to a customer account, follow these steps:

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Double-click on a customer name.

3.  On the **Action Pane**, click **Edit**.

4.  On the **Direct debit mandates** FastTab, click **Add**.

5.  Enter information about the mandate. Make the following selections.
    
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
    <td><p><strong>Default mandate ID</strong></p></td>
    <td><p>The identifier is automatically assigned.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Bank account</strong></p></td>
    <td><p>Select the customer’s bank account. The <strong>IBAN</strong> and <strong>SWIFT code</strong> fields must be filled in for the bank account if it is used for direct debits.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Signature date</strong></p></td>
    <td><p>Enter the date when the mandate was signed.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Mandate scheme</strong></p></td>
    <td><p>Select the type of mandate scheme. Select from the following options:</p>
    <ul>
    <li><p><strong>Core</strong> – The basic direct debit scheme, which can be used for businesses or consumers.</p></li>
    <li><p><strong>B2B</strong> – The business-to-business scheme, which can be used only for businesses.</p></li>
    <li><p><strong>COR1</strong> – The COR1 direct debit mandate scheme, which can be used for businesses or consumers.</p>
    <p>This COR1 direct debit mandate scheme is available only if AX 2012 R3, AX 2012 R2 with the hotfix in KB2902097, or AX 2012 with the hotfix in KB2902097 is installed.</p></li>
    </ul></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Payment frequency</strong></p></td>
    <td><p>Select how payments are made. Select from the following options.</p>
    <ul>
    <li><p><strong>Recurring</strong> – Mandates include multiple payments, such as installment plans or service agreements. Enter the number of payments in the <strong>Expected number of payments</strong> field.</p></li>
    <li><p><strong>One-time</strong> – Mandates include only one payment.</p></li>
    </ul></td>
    </tr>
    <tr class="even">
    <td><p><strong>Mandate status</strong></p></td>
    <td><p>The mandate status is <strong>Incomplete</strong> until you enter all the required fields. The status then changes to <strong>New</strong>.</p></td>
    </tr>
    </tbody>
    </table>


6.  Optional: Change the default entries for the following fields, if you have to.
    
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
    <td><p><strong>Days required for the first pre-notification</strong></p>
    <p><strong>Days required for recurring pre-notifications</strong></p></td>
    <td><p>Enter the number of days to allow for pre-notifications.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Days required for the first bank submission</strong></p>
    <p><strong>Days required for recurring bank submissions</strong></p></td>
    <td><p>Enter the number of days to allow for bank submissions.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Signature date</strong></p>
    <p><strong>Signature location</strong></p></td>
    <td><p>Enter the date and location where the mandate was signed. The expiration date is automatically calculated, based on the signature date.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Expected number of payments</strong></p></td>
    <td><p>For recurring payments, enter the expected number of payments. For one-time payments, enter 1.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Usage count</strong></p></td>
    <td><p>For new mandates, this number is zero (0).</p>
    <p>The count is automatically updated every time that a payment for an invoice is posted.</p>
    <p>If a payment is settled with two invoices, the usage count is increased by two, even though only one payment is used.</p>
    <p>If a payment is settled with an invoice in another legal entity, the usage count is updated in the legal entity of the invoice.</p></td>
    </tr>
    </tbody>
    </table>


7.  In the **Default mandate ID** field, select the default mandate to use for transactions. These transactions include customer invoices for sales orders, free text invoices, interest notes, collection letters, project invoices, and journal entries. Select the mandate reference that will be used for these transactions most of the time. If you need to, you can use the **Customer transactions** form to change the mandate reference for a transaction after it has been posted.

## 2\. Optional: Generate a mandate for the customer to sign and return

If your business process requires it, you can print a partially completed mandate form for your customer to fill out, sign, and return to you.

To generate a mandate for the customer to sign and return, follow these steps:

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Double-click on a customer name.

3.  On the **Direct debit mandates** FastTab, select a mandate, and then click **Print** \> **Mandate report**.

## 3\. Optional: Attach a scanned mandate to the customer account

If your customer has submitted a signed paper mandate form, you can scan it and attach it to the mandate for the customer’s account. For more information about how to scan and attach documents, see [Using document management](using-document-management.md).

To attach a scanned mandate to the mandate for the customer’s account, follow these steps:

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Double-click on a customer name.

3.  On the **Direct debit mandates** FastTab, select a mandate, and then click **Attachments**.

## 4\. Optional: Cancel a mandate

If a mandate is no longer needed, you can cancel it if it isn’t assigned to an open invoice.

To cancel a mandate, follow these steps:

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Double-click on a customer name.

3.  On the **Direct debit mandates** FastTab, select a mandate, and then click **More options** \> **Cancel mandate**.

## Next step

You have finished adding information about direct debit mandates to a customer account. You can enter an invoice for that customer. For more information, see [Enter an invoice or transaction for a customer who has a direct debit mandate](enter-an-invoice-or-transaction-for-a-customer-who-has-a-direct-debit-mandate.md).

## Related tasks

[Create payments for customers who have direct debit mandates](create-payments-for-customers-who-have-direct-debit-mandates.md)

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
<td><p>To add information about direct debit mandates to a customer account, you must be a member of a security role that includes the <strong>Maintain customer master</strong> (CustCustomersMaintain) duty.</p></td>
</tr>
</tbody>
</table>


## See also

[SEPA direct debit overview](sepa-direct-debit-overview.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

