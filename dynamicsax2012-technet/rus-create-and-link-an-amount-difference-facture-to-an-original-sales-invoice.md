---
title: (RUS) Create and link an amount difference facture to an original sales invoice
TOCTitle: (RUS) Create and link an amount difference facture to an original sales invoice
ms:assetid: 491c431d-cbae-4ffd-9b0b-685c47b79b4b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ853177(v=AX.60)
ms:contentKeyID: 50396458
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Create and link an amount difference facture to an original sales invoice 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the following procedures to create and link an amount difference facture to an original sales invoice.

## Create an amount difference facture for a sales order

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  To post a facture for a sales order, create the sales order, and then, on the **Setup** FastTab, select **Sales tax group** and **Item sales tax group**. For more information, see [(RUS) Create and update facture for a corrected sales order invoice or sales credit note](rus-create-and-update-facture-for-a-corrected-sales-order-invoice-or-sales-credit-note.md).

3.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.

4.  Create a journal, and then enter the required details. For more information, see [Journal header (form)](https://technet.microsoft.com/en-us/library/aa557917\(v=ax.60\)) and [Journal voucher - Customer payment journal (form)](https://technet.microsoft.com/en-us/library/aa556141\(v=ax.60\)).

5.  Click **Lines** to open the **Journal voucher** form.

6.  In the **Account** field, select the customer account that the sales invoice is posted for.

7.  Click **Functions** \> **Settlement** to open the **Settle open transactions** form.

8.  Select the **Mark** check box to mark the sales invoice line to be settled.

9.  Close the form.

10. Click **No** to retain the original journal amount.

11. Click **Post** \> **Post** to post the journal.

## Link an amount difference facture to an original sales invoice

1.  Click **Accounts receivable** \> **Inquiries** \> **Journals** \> **Invoice journal**.

2.  To open the **Update facture** form, select the invoice line for which to include the amount difference in the sales book, and then click **Create facture** \> **Update facture**.
    

    > [!NOTE]
    > <P>In the sales book, the facture date and facture number should be the same as the original facture.</P>



3.  In the lower pane, select the **To facture** check box to mark the facture to be updated.

4.  Click **Posting** \> **Update** to update the facture with the amount difference.

5.  Close the forms.

6.  Click **Accounts receivable** \> **Inquiries** \> **Journals** \> **Facture**.

7.  Select the posted facture, and then click the **Amount difference** tab.
    

    > [!NOTE]
    > <P>The source facture ID is displayed in the <STRONG>Facture source</STRONG> field.</P>



8.  Select the **Include in book** check box to update the amount difference facture in the sales book.

9.  Click **Print**.

10. Select the **Included only** check box to print the original facture with only the selected amount difference factures. If you clear this check box, all amount difference factures are printed with the original facture.

## See also

[(RUS) Create and link an amount difference facture to an original purchase invoice](rus-create-and-link-an-amount-difference-facture-to-an-original-purchase-invoice.md)

[(RUS) Journal voucher - Customer payment journal (modified form)](https://technet.microsoft.com/en-us/library/jj733240\(v=ax.60\))

[(RUS) Customer invoice journal (modified form)](https://technet.microsoft.com/en-us/library/jj711658\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

