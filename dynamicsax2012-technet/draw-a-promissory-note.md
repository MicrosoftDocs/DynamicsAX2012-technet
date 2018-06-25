---
title: Draw a promissory note
TOCTitle: Draw a promissory note
ms:assetid: 5da88792-b3a2-4268-b125-f0bae015d5ed
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa549102(v=AX.60)
ms:contentKeyID: 36655930
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- promissory notes
- promissory note
---

# Draw a promissory note [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can draw a promissory note automatically or in a journal. A promissory note always is based on an open vendor transaction that has a status of **Invoiced** on the **All purchase orders** list page.


> [!NOTE]
> <P>If the <STRONG>Public sector</STRONG> configuration key is selected, the payment proposal process interacts with the posting invoice in an additional way. You can distribute the payment of an invoice to multiple vendor bank accounts. In the <STRONG>Vendor invoice</STRONG> form, you can select multiple bank accounts and allocate a percentage to each bank account. Based on the vendor bank accounts that you select, single or multiple open transactions are created for the invoice. You can create payments for each journal line without creating a partial payment for each vendor bank account.</P>



When you draw a promissory note, it appears as an open vendor transaction for the vendor in the **Vendor transactions** form. (Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**. Select a vendor account. On the **Action Pane**, click **Transactions**.) You can identify a promissory note transaction by viewing the **Note ID**, **Status**, **Sequence number**, and **Remittance number** fields on the **Overview** tab, and the **Company** and **Vendor** bank account fields on the **Payment** tab.


> [!NOTE]
> <P>When you transfer transactions to a journal, the way that due dates are handled depends on how you select the transactions. Click <STRONG>Accounts receivable</STRONG> &gt; <STRONG>Journals</STRONG> &gt; <STRONG>Payments</STRONG> &gt; <STRONG>Payment journal</STRONG>. Click <STRONG>Lines</STRONG>. You can click <STRONG>Payment proposal</STRONG> &gt; <STRONG>Create payment proposal</STRONG> to select transactions by using a query that is set up to select the total number of payments that are due as of a specific date. If you use a payment proposal, the date that you enter in the <STRONG>Total payment date</STRONG> field is used for all transferred transactions. If you select transactions manually in the <STRONG>Settle open transactions</STRONG> form, the latest due date of the selected transactions is used.</P>



## Draw a promissory note automatically

You can automatically draw promissory notes for vendor invoices that are posted for a method of payment. To enable this functionality, select the **Create and post draw journal automatically when posting invoices** check box in the **Methods of payment - vendors** form. For more information, see [Methods of payment - vendors (form)](https://technet.microsoft.com/en-us/library/aa618565\(v=ax.60\)).

## Draw a promissory note in a journal

To manually draw promissory notes for a method of payment, make sure that the **Create and post draw journal automatically when posting invoices** check box in the **Methods of payment - vendors** form is cleared.

1.  Click **Accounts payable** \> **Journals** \> **Promissory notes** \> **Draw promissory note journal**.

2.  Create a journal, and then click **Lines**.

3.  Select the vendor account for the invoice, and then click **Functions** \> **Settlement**.

4.  Select the **Mark** check box for an open transaction.

5.  Close the **Settle open transactions** form.

6.  Click **Post** \> **Post**.
    
    A promissory note and a related line that has a status of **Drawn** and a sequence number of 1 or greater is shown in the **Promissory note journal** inquiry form. In the **Promissory note statistics** inquiry form, the number of promissory notes for the **Drawn and invoice-confirmed documents** status is increased.
    
    When the journal is posted, the vendor summary account is debited and the promissory note summary account is credited.

## Print a promissory note document

You can draw and then print a promissory note document to send to a vendor. You can create promissory note documents in a draw promissory note journal. The process of generating promissory note documents is like generating checks. For more information, see [Make a payment by check](make-a-payment-by-check.md).

1.  Click **Accounts payable** \> **Journals** \> **Promissory notes** \> **Draw promissory note journal**.

2.  Create a journal.

3.  On the **Promissory note** tab, select a bank account that has a layout for promissory note documents set up, and then click **Lines**.
    

    > [!NOTE]
    > <P>You can select from only active bank accounts.</P>



4.  Select the vendor account for the invoice, and then click **Functions** \> **Settlement**.

5.  Select the **Mark** check box for an open transaction, and then close the form.
    

    > [!NOTE]
    > <P>To transfer open transactions to the journal, click <STRONG>Payment proposal</STRONG> &gt; <STRONG>Proposal by due date</STRONG>.</P>



6.  Click **Functions** \> **Generate payments**.

7.  Select a promissory note document method of payment, and then click **Dialog**.

8.  In the **Promissory note document** form, enter the first number for the promissory note and the number of blank promissory notes, and then click **OK**.

9.  In the **Generate payments** form, click **OK** to print the promissory note document.

10. Verify that the promissory note document information is correct.
    

    > [!NOTE]
    > <P>To cancel the promissory note document, click <STRONG>Functions</STRONG> &gt; <STRONG>Cancel promissory note document</STRONG>. The status of the promissory note changes to <STRONG>Canceled</STRONG>. You can see the status in the <STRONG>Promissory notes</STRONG> form, which is opened from the <STRONG>Bank accounts</STRONG> form.</P>



11. Click **Post** \> **Post**.
    

    > [!NOTE]
    > <P>If you cannot post and you receive a message that mentions posting restrictions, you might be set up to post only journals that you created. For more information, see <A href="https://technet.microsoft.com/en-us/library/hh227598(v=ax.60)">Posting restrictions (form)</A>.</P>



## See also

[About payment types](about-payment-types.md)

[Remit a promissory note](remit-a-promissory-note.md)

[Redraw a promissory note](redraw-a-promissory-note.md)

[Create and validate journals and journal lines](create-and-validate-journals-and-journal-lines.md)

[Make a payment by check](make-a-payment-by-check.md)

[Methods of payment - vendors (form)](https://technet.microsoft.com/en-us/library/aa618565\(v=ax.60\))

[Promissory note statistics (form)](https://technet.microsoft.com/en-us/library/aa550186\(v=ax.60\))

[Specify when a vendor bank account is active](specify-when-a-vendor-bank-account-is-active.md)

[Select invoices to pay on behalf of multiple legal entities](select-invoices-to-pay-on-behalf-of-multiple-legal-entities.md)

[Print copies of payments as non-negotiable checks](print-copies-of-payments-as-non-negotiable-checks.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

