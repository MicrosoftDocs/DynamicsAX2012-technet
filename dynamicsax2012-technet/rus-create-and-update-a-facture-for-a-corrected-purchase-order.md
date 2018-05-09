---
title: (RUS) Create and update a facture for a corrected purchase order
TOCTitle: (RUS) Create and update a facture for a corrected purchase order
ms:assetid: a3355f81-27ac-4ebd-a2ac-0c258a532d2b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678557(v=AX.60)
ms:contentKeyID: 49387787
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Create and update a facture for a corrected purchase order 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In some cases, the accountant must issue a corrective invoice to correct errors and clarify VAT information. In Microsoft Dynamics AX, you can create documents to correct vendor invoices. In order to properly display corrected documents in the purchase book while processing corrected invoices and factures, you must specify the references to the corrected invoices, factures, and the VAT reporting periods.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts payable** \> **Setup** \> **Accounts payable parameters**.

2.  Click the **Number sequences** tab.

3.  In the **Number sequence code** field, select the number sequence code for the **Corrective invoice voucher** in the **Reference** field.

4.  Close the **Accounts payable parameters** form.

5.  Click **Accounts payable** \> **Common Forms** \> **Purchase Order Details** to open the **Purchase order** form.

6.  Press CTRL+N to create a purchase order and enter the required details.
    

    > [!NOTE]
    > <P>For more information, see "Create a purchase order" and "Purchase orders (form)" in the Applications and Business Processes Help.</P>



7.  Click **Posting** \> **Invoice** to open the **Posting invoice** form.

8.  Click the **Additional** tab, and then select the **Corrective document** check box.

9.  In the **Invoice** field, select the number of the invoice to be corrected.

10. In the **Invoice date** field, select the date of the corrected invoice.

11. Click **OK** to post the corrected invoice.

12. Click **Accounts payable** \> **Inquiries** \> **Journals** \> **Invoice journal**.
    

    > [!NOTE]
    > <P>The <STRONG>Corrective document</STRONG> check box is activated for the corrected invoice.</P>



13. Select the posted invoice and then click **Update facture** to open the **Update facture** form.

14. In the upper section of the form, in the **Facture** field, enter the facture number.

15. In the **Date of the registration** field, select the facture registration date.

16. In the **Facture date** field, select the facture creation date.
    

    > [!NOTE]
    > <P>This date is the same as the facture registration date. The field can be modified only when you select the <STRONG>Same as</STRONG> check box.</P>



17. Under the **Correction** field group, in the **Facture** field, select the number of the corrected facture.

18. In the **Facture date** field, select the date of the corrected facture.

19. In the **Corrected period** field, select the date of the corrected period.

20. In the lower section of the form, on the **Invoice** tab, select the **To facture** check box to specify the corrected invoice for which the facture is being created.

21. Click the **Invoice lines** tab and clear the **To facture** check box if you do not want to create a facture for that corrected invoice line.

22. Click **Posting** \> **Update** to update the facture.
    

    > [!NOTE]
    > <P>Click <STRONG>Accounts payable</STRONG> &gt; <STRONG>Inquiries</STRONG> &gt; <STRONG>Journals</STRONG> &gt; <STRONG>Facture</STRONG>. The reference to the corrected facture is displayed in the <STRONG>Correction</STRONG> field group on the <STRONG>General</STRONG> tab (upper pane). After the facture is updated, the corrected factures are incorporated into the existing purchase books, as determined by the date of the corrected period.</P>



## See also

[(RUS) Facture journal (form)](https://technet.microsoft.com/en-us/library/jj923567\(v=ax.60\))

[(RUS) Create and update a facture for a corrected credit note invoice](rus-create-and-update-a-facture-for-a-corrected-credit-note-invoice.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

