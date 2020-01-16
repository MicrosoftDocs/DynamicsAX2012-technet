---
title: (RUS) Create and link an amount difference facture to an original purchase invoice
TOCTitle: (RUS) Create and link an amount difference facture to an original purchase invoice
ms:assetid: 6978f1d9-ce6d-4129-9e5c-5e81ac483228
ms:mtpsurl: https://technet.microsoft.com/library/JJ853190(v=AX.60)
ms:contentKeyID: 50396471
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Create and link an amount difference facture to an original purchase invoice 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the following procedures to create and link an amount difference facture to an original purchase invoice.

## Create an amount difference facture for a purchase order

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  To post a facture for a purchase order, create the purchase order, and then, on the **Setup** FastTab, select **Sales tax group** and **Item sales tax group**. For more information, see [(RUS) Generate a facture for a purchase order](rus-generate-a-facture-for-a-purchase-order.md) and [(RUS) Create and update a facture for a corrected purchase order](rus-create-and-update-a-facture-for-a-corrected-purchase-order.md).

3.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

4.  Create a journal, and then enter the required details. For more information, see [Journal header (form)](https://technet.microsoft.com/library/aa557917\(v=ax.60\)) and [Journal voucher - Vendor payment journal (form)](https://technet.microsoft.com/library/aa599011\(v=ax.60\)).

5.  Click **Lines** to open the **Journal voucher** form.

6.  In the **Account** field, select the vendor account that the purchase invoice is posted for.

7.  Click **Functions** \> **Settlement** to open the **Settle open transactions** form.

8.  Select the **Mark** check box to mark the purchase invoice to be settled.

9.  Close the form.

10. Click **No** to retain the original journal amount.

11. Click **Post** \> **Post** to post the journal.

## Link an amount difference facture to an original purchase invoice

1.  Click **Accounts payable** \> **Inquiries** \> **Journals** \> **Invoice journal**.

2.  Select the invoice line for which to include the amount difference in the purchase book, and then click **Create facture** \> **Update facture** to open the **Update facture** form.

3.  In the **Facture** field, enter the facture number for the purchase invoice.

4.  Select the **To facture** check box to mark the facture to be updated.

5.  Click **Posting** \> **Update** to update the facture with the amount difference.

6.  Close the forms.

7.  Click **Accounts payable** \> **Inquiries** \> **Journals** \> **Facture**.

8.  Select the posted facture, and then click the **Amount difference** tab. The source facture ID is displayed in the **Facture source** field.

9.  Select the **Include in book** check box to update the amount difference facture in the purchase book.

10. Click **Print**.

11. Select the **Included only** check box to print the original facture with only the selected amount difference factures. If you clear this check box, you print the original facture with all of the amount difference factures.

12. Click **OK** to print the factures that include the amount difference.

13. The factures are processed and recorded in the **Purchase book** (**Incoming VAT processing**) form as separate lines.

## See also

[(RUS) Create and link an amount difference facture to an original sales invoice](rus-create-and-link-an-amount-difference-facture-to-an-original-sales-invoice.md)

[(RUS) Journal voucher - Vendor payment journal (modified form)](https://technet.microsoft.com/library/jj733511\(v=ax.60\))

[(RUS) Vendor invoice journal (modified form)](https://technet.microsoft.com/library/jj733211\(v=ax.60\))

  


