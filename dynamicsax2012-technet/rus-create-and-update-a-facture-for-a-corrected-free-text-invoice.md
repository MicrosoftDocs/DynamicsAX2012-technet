---
title: (RUS) Create and update a facture for a corrected free text invoice
TOCTitle: (RUS) Create and update a facture for a corrected free text invoice
ms:assetid: e3f84a24-f897-4e48-a8f0-3551ffcf17da
ms:mtpsurl: https://technet.microsoft.com/library/JJ711704(v=AX.60)
ms:contentKeyID: 49388027
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (RUS)
- Russia
- corrected invoice
- Update facture
audience: Application User
ms.search.region: Russia
---

# (RUS) Create and update a facture for a corrected free text invoice 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to create and update a facture for a corrected free text invoice. In some cases, you must use corrective credit notes and invoices to clarify information about value-added tax (VAT) and to correct errors. You can create documents that correct invoices and credit notes for customers. Before the sales book can reflect the corrected documents at the stage for corrected invoices and factures, you must specify references for corrected invoices, factures, and VAT reporting periods.

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  Click the **Number sequences** link.

3.  Select number sequence codes for the following references:
    
      - **Corrective free text invoice**
    
      - **Corrective free text credit note**
    
      - **Corrective free text invoice voucher**
    
      - **Corrective free text credit note voucher**
    
      - **Corrective facture**

4.  Close the form.

5.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

6.  Double-click the free text invoice you want to correct.

7.  Click **Cancel** \> **Correct invoice** to open the **Create corrected invoice** form.

8.  In the **Reason code** field, select a code that specifies the reason for the correction.

9.  In the **Comments** field, enter additional information about the correction that you are making to the free text invoice.

10. In the **Canceling invoice date** field, select or enter the date of the canceling invoice.

11. Select the **Create canceling invoice only** check box to create only the canceling invoice. For example, to cancel the original invoice without creating a new invoice to replace it, select this check box.

12. Click **Create corrected invoice** to create a corrected invoice for the selected free text invoice. The invoice date of the corrected free text invoice must be within the period for the open sales book. You can view the related invoices, and navigate between the parent invoice and the related corrected invoices.

13. Click **Post** to open the **Post free text invoice** form.

14. Click **OK** to post the free text invoice.

15. Click **Accounts receivable** \> **Inquiries** \> **History** \> **Invoice**.
    

    > [!NOTE]
    > <P>The <STRONG>Corrective document</STRONG> check box is selected for the corrected invoice only if the check box was selected when the invoice line was posted.</P>



16. Select the corrected free text invoice, and then click **Create facture** \> **Update facture** to open the **Update facture** form.

17. In the **Facture** field, select the facture number of the corrected facture.
    

    > [!NOTE]
    > <P>The <STRONG>Corrective document</STRONG> field for the new invoice is updated with the original invoice date and number.</P>



18. In the **Facture date** field, select the date of the corrected facture.

19. In the **Corrected period** field, select the date of the corrected period.

20. On the **Invoice** tab, select the **To facture** check box to specify the corrected invoice that you are creating the facture for.
    

    > [!NOTE]
    > <P>If you do not want to create a facture for a corrected invoice line, click the <STRONG>Invoice lines</STRONG> tab, and then clear the <STRONG>To facture</STRONG> check box.</P>



21. Click **Posting** \> **Update** to update the corrected facture.


> [!NOTE]
> <P>The corrected facture is displayed in the <STRONG>Facture journal</STRONG> form. After you update the sales book lines, the information for the corrected facture is displayed in the <STRONG>Correction</STRONG> field group in the <STRONG>Sales book lines</STRONG> form.</P>



## See also

[(RUS) Sales book lines (form)](https://technet.microsoft.com/library/jj911234\(v=ax.60\))

[(RUS) Create and update facture for a corrected sales order invoice or sales credit note](rus-create-and-update-facture-for-a-corrected-sales-order-invoice-or-sales-credit-note.md)

  


