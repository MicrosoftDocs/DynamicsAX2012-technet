---
title: (RUS) Create and update a facture for a corrected credit note invoice
TOCTitle: (RUS) Create and update a facture for a corrected credit note invoice
ms:assetid: 7d0f18a2-fc31-4e04-a4af-2ac658b5264e
ms:mtpsurl: https://technet.microsoft.com/library/JJ678396(v=AX.60)
ms:contentKeyID: 49387626
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Create and update a facture for a corrected credit note invoice 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



In some cases, you must use corrective credit notes and invoices to clarify VAT information and correct various types of errors. In Microsoft Dynamics AX, you can create documents that correct invoices and credit notes for customers. To properly reflect the corrected documents in the sales book at the corrected invoice and factures stage, you must specify references for corrected invoices, factures, and VAT reporting periods.

1.  Click **Accounts payable** \> **Setup** \> **Accounts payable parameters**.

2.  Click the **Number sequences** tab.

3.  In the **Number sequence code** field, select the number sequence code for **Corrective credit note voucher**.

4.  Close the **Accounts payable parameters** form.

5.  Click **Accounts payable** \> **Common Forms** \> **Purchase Order Details** to open the **Purchase order** form.

6.  Press CTRL+N to create a purchase order.
    

    > [!NOTE]
    > <P>For more information, see "Create a purchase order" in the Applications and Business Processes Help.</P>



7.  Click **Posting** \> **Invoice** to open the **Posting invoice** form.

8.  Click **OK** to post the invoice.

9.  In the **Purchase order** form, click **Functions** \> **Create credit note** to open the **Create credit note** form.

10. In the lower pane of the form, click the **Invoice** tab, and then select the **Mark** check box to select the line to be copied to the new order.

11. Click **OK** to create the credit note.

12. In the **Purchase order** form, click **Posting** \> **Invoice** to open the **Posting invoice** form.

13. On the **Additional** tab, select the **Corrective document** check box.

14. In the **Invoice** field, select the number of the corrected invoice.

15. In the **Invoice date** field, select the date to be displayed on the corrected invoice.
    

    > [!NOTE]
    > <P>The invoice number of the correction document is updated automatically.</P>



16. Click **OK** to post the credit note invoice.

17. Click **Accounts payable** \> **Inquiries** \> **Journals** \> **Invoice journal**.
    

    > [!NOTE]
    > <P>The <STRONG>Corrective document</STRONG> check box will be activated for the posted invoice.</P>



18. Click **Update facture** to open the **Update facture** form.

19. In the upper pane of the form, in the **Facture** field, enter the facture number.

20. In the **Date of the registration** field, select the facture registration date.

21. In the **Facture date** field, select the facture creation date.
    

    > [!NOTE]
    > <P>This date is the same as the facture registration date. The field can be modified only when you select the <STRONG>Same as</STRONG> check box.</P>



22. Under the **Correction** field group, in the **Facture** field, select the number of the corrected facture.

23. In the **Facture date** field, select the date of the corrected facture.

24. In the **Corrected period** field, select the date of the corrected period.

25. In the lower pane of the form, on the **Invoice** tab, select the **To facture** check box to specify the corrected invoice for which the facture will be created.
    

    > [!NOTE]
    > <P>If you do not want to create a facture for a particular corrected invoice line, click the <STRONG>Invoice lines</STRONG> tab and clear the <STRONG>To facture</STRONG> check box.</P>



26. Click **Posting** \> **Update** to update the facture.
    

    > [!NOTE]
    > <P>Click <STRONG>Accounts payable</STRONG> &gt; <STRONG>Inquiries</STRONG> &gt; <STRONG>Journals</STRONG> &gt; <STRONG>Facture</STRONG>. The reference to the corrected facture is displayed in the <STRONG>Correction</STRONG> field group on the <STRONG>General</STRONG> tab (upper pane).</P>



## See also

[(RUS) Update facture (form)](https://technet.microsoft.com/library/jj889412\(v=ax.60\))

[(RUS) Facture journal (form)](https://technet.microsoft.com/library/jj923567\(v=ax.60\))

  


