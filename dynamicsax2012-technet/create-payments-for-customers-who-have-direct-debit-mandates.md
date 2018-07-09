---
title: Create payments for customers who have direct debit mandates
TOCTitle: Create payments for customers who have direct debit mandates
ms:assetid: 1a955849-0c18-4272-89e4-1ded346e1e33
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn269115(v=AX.60)
ms:contentKeyID: 54920067
ms.date: 04/27/2014
mtps_version: v=AX.60
f1_keywords:
- Classes.CustSumForPaym
- Classes.CustVendCreatePaymJournal_Cust
- Forms.CustTableListPage
- Forms.CustVendPaymentProcessingData
- direct debit
- Forms.LedgerJournalTransCustPaym
- Forms.CustTable
- Forms.LedgerJournalTable
- BE - 00019
- DE - 00015
- direct debit payments
- ES - 00023
- FR - 00019
- direct debit mandates
- IT - 00035
- NL - 00014
- GBL - 00003
- MsDynAx060.Forms.LedgerJournalTable
- MsDynAx060.Forms.CustTable
- MsDynAx060.Forms.LedgerJournalTransCustPaym
- MsDynAx060.Forms.CustTableListPage
- MsDynAx060.Forms.CustVendPaymentProcessingData
---

# Create payments for customers who have direct debit mandates [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create SEPA direct debit payments for customers who have invoices that use a method of payment that requires a mandate. This topic explains how to create a payment proposal for customers who have direct debit mandates. It also explains how you can verify and print mandate information after the payment is posted.


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed for Microsoft Dynamics AX 2012 R3, AX 2012 R2 with the hotfix in <A href="https://mbs2.microsoft.com/knowledgebase/kbdisplay.aspx?scid=kb%3ben-us%3b2902097">KB2902097</A>, and AX 2012 with the hotfix in <A href="https://mbs2.microsoft.com/knowledgebase/kbdisplay.aspx?scid=kb%3ben-us%3b2902097">KB2902097</A>.</P>



Depending on the version that you are using, you can generate electronic payment files for SEPA in the following formats:

  - In AX 2012 R3 or cumulative update 7 or later for AX 2012 R2: You can generate SEPA direct debit payment files in the ISO 20022 PAIN.008.001.02 XML file format for Belgium, Germany, Spain, France, Italy, and the Netherlands.

  - In AX 2012 R3, AX 2012 R2 with the hotfix in KB2902097, and AX 2012 with the hotfix in KB2902097: You can generate electronic payment files for SEPA direct debits in the PAIN.008.001.02 XML file format for Austria, and in the PAIN.008.003.02 XML file format for Germany.

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
<td><p>AX 2012 R3, AX 2012 R2, or AX 2012</p></td>
</tr>
<tr class="even">
<td><p><strong>Country/region</strong></p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: Austria, Belgium, Germany, Spain, France, Italy, or the Netherlands</p></td>
</tr>
<tr class="odd">
<td><p><strong>Related tasks</strong></p></td>
<td><ul>
<li><p>Set up direct debit mandates. For more information, see <a href="set-up-sepa-direct-debit-mandate.md">Set up SEPA direct debit mandate</a>.</p></li>
<li><p>Add direct debit mandate information for a customer account. For more information, see <a href="add-direct-debit-mandate-information-to-a-customer-account.md">Add direct debit mandate information to a customer account</a>.</p></li>
<li><p>Create a free text invoice for a customer who has a direct debit mandate. For more information, see <a href="enter-an-invoice-or-transaction-for-a-customer-who-has-a-direct-debit-mandate.md">Enter an invoice or transaction for a customer who has a direct debit mandate</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Create a payment proposal for customers who have direct debit mandates

You can use the **Payment journal** form to create a payment proposal for customers who have direct debit mandates.

To create a payment proposal, follow these steps:

1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Select a journal name, and then click **Lines**.

3.  Select a journal line, and then click **Payment proposal** \> **Create payment proposal**.

4.  In the **Customer payment proposal** form, click **Select**.

5.  In the **Customer payment proposal query** form, in the **Criteria** field, select the criteria for the customer transactions.

6.  To add restrictions to select documents by mandate scheme or payment frequency, in the upper pane, right-click the **Customer transactions** table in the tree and add the **Customer direct debit mandates** table. Enter criteria, and then click **OK**.

7.  In the **Customer payment proposal** form, enter other information for the payment proposal as needed, and then click **OK**.

8.  Click **Functions** \> **Generate payments**.

9.  In the **Generate payments** form, select **Payment method**, and then in the **Method of payment** field, select a method of payment that requires a mandate.

10. Select **Export payment using service**, and then in the **Payment format** field, select an export format such as **SEPADirectDebit** to generate payments by using the payment format.
    

    > [!NOTE]
    > <P>You can create payment formats for Application Integration Framework (AIF) services in the <STRONG>Outbound ports for electronic payments</STRONG> form.</P>



11. In the **Bank account** field, select the bank account for SEPA direct debit.

12. Click **OK** to open the **Payment processing data** form.

13. In the **Payment processing data** form, modify the information that is specific to the SEPA direct debit payment format.

14. In AX 2012 R3 and cumulative update 7 or later for AX 2012 R2: To generate the country-specific or region-specific version of the direct debit file, in the **Value** field, enter the two-digit country or region code. Leave this field blank to use the generic direct debit file format.

15. Select the **Control report** check box to print a control report for the electronic payment file.

16. Click **OK** to generate the electronic payment file in the format of the selected country.
    
    Payments are generated, and the payment status in the **Journal voucher** form changes to **Sent**.

17. Click **Post** \> **Post**. Payments are posted. The usage count for each customer mandate is incremented. If a payment is settled with two invoices, the usage count is incremented by two, even though only one payment is used. If a payment is settled for another legal entity, the usage count is updated in the invoice.

## Print the mandate information for customer transactions

To verify mandate information for customer transactions and print the mandate information, follow these steps:

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Double-click a customer account.

3.  On the **Direct debit mandates** FastTab, double-click a mandate to verify the mandate information. The usage count for the customer’s mandate is automatically updated when the payment is posted.

4.  To view the remaining invoices for the selected mandate, click **Print** \> **Notification report**.

5.  Click **OK** to print the mandate information.


> [!NOTE]
> <P>In the <STRONG>Customers</STRONG> form, you can click <STRONG>Transactions</STRONG> to view the customer transactions for the payment.</P>



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
<td><p>To generate payments for customers who have direct debit mandates, you must be a member of a security role that includes the <strong>Maintain customer payments</strong> (PaymCustomerPaymentsMaintain) duty.</p></td>
</tr>
</tbody>
</table>


## See also

[SEPA direct debit overview](sepa-direct-debit-overview.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

