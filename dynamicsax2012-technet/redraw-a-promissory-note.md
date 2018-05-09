---
title: Redraw a promissory note
TOCTitle: Redraw a promissory note
ms:assetid: d271c356-9af6-4d29-b459-b249bdd71559
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa551040(v=AX.60)
ms:contentKeyID: 36966741
ms.date: 06/18/2014
mtps_version: v=AX.60
---

# Redraw a promissory note 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the **Redraw promissory note journal** form to redraw a promissory note that has already been honored by your bank. A new transaction is created that has a **Redrawn** status for the honored promissory note.


> [!NOTE]
> <P>To complete the promissory note cycle, you must remit and settle the redrawn promissory note. For more information, see <A href="remit-a-promissory-note.md">Remit a promissory note</A> and <A href="settle-a-promissory-note.md">Settle a promissory note</A>.</P>
> <P>You cannot redraw a promissory note that has been closed.</P>



1.  Click **Accounts payable** \> **Journals** \> **Promissory notes** \> **Redraw promissory note journal**.

2.  Create a journal.

3.  On the **Promissory note** tab, you can select the bank account that was used when the promissory note was remitted.

4.  If you have already settled the promissory note with the invoice, select the **Protest settlements** check box, and then select whether to create the new transaction as an open payment or as an invoice.

5.  Click **Lines**.

6.  In the **Journal voucher** form, select the vendor account for the invoice, and then click **Functions** \> **Select settled promissory notes**.

7.  In the **Mark** column, select the check box for the honored transaction.

8.  Close the form to transfer the transaction to a journal line.

9.  In the **Journal voucher** form, click **Post** \> **Post**.
    
    A new line is created for the promissory note. The line has a **Redrawn** status, and a sequence number of 2 or greater. This line is shown in the **Promissory note journal** inquiry form. In the **Promissory note statistics** inquiry form, the number in the **History of redrawn documents** row is increased, and the number in the **Honored documents** row is decreased.
    
    When the journal is posted, the bank summary account is debited, and the remitted promissory notes summary account is credited.
    
    (ESP) Conditional sales tax is canceled when you redraw a promissory note that is settled for a customer invoice on which conditional sales tax is applied. You can verify whether the conditional sales tax is canceled for the payment in the **Voucher transactions** form.
    

    > [!NOTE]
    > <P>If you receive a message that mentions posting restrictions, you might be set up to post only journals that you created. For more information, see <A href="https://technet.microsoft.com/en-us/library/hh227598(v=ax.60)">Posting restrictions (form)</A>.</P>



## See also

[Settle a promissory note](settle-a-promissory-note.md)

[Create and validate journals and journal lines](create-and-validate-journals-and-journal-lines.md)

[Journal header (form)](https://technet.microsoft.com/en-us/library/aa557917\(v=ax.60\))

[Promissory note statistics (form)](https://technet.microsoft.com/en-us/library/aa550186\(v=ax.60\))

[About payment types](about-payment-types.md)

[Print copies of payments as non-negotiable checks](print-copies-of-payments-as-non-negotiable-checks.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

