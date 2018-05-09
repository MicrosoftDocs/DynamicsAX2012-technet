---
title: (RUS) Create and update facture for a corrected sales order invoice or sales credit note
TOCTitle: (RUS) Create and update facture for a corrected sales order invoice or sales credit note
ms:assetid: 3e0a6604-c400-4480-bff6-e27e9e923592
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ665309(v=AX.60)
ms:contentKeyID: 49387398
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Create and update facture for a corrected sales order invoice or sales credit note 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



In some cases, you must use corrective credit notes and invoices to clarify VAT information and correct various types of errors. In Microsoft Dynamics AX, you can create documents that correct invoices and credit notes for customers. To properly reflect the corrected documents in the sales book at the corrected invoice and factures stage, you must specify references for corrected invoices, factures, and VAT reporting periods.

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  Click the **Number sequences** tab.

3.  In the **Number sequence code** field, select the number sequence code for **Corrective facture**, **Corrective sales invoice**, **Corrective sales credit note**, **Corrective sales invoice voucher**, **Corrective sales credit note voucher**, **Corrective invoice (M-15) (syst. ID)**, **Corrective invoice (M-15)**, and **Corrective bill of lading** in the **Reference** field.

4.  Press CTRL+S or close the form.

5.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

6.  Press CTRL+N to create a sales order, and enter the required details.
    

    > [!NOTE]
    > <P>For more information, see "Create a sales order" and "Sales orders (form)" in the Applications and Business Processes Help.</P>



7.  Click **Posting** \> **Invoice** to open the **Posting invoice** form.

8.  Click the **Additional** tab, and select the **Corrective document** check box to create a corrective sales order invoice.

9.  In the **Invoice** field, select the invoice to be corrected.
    

    > [!NOTE]
    > <P>If the corrected document is created using <STRONG>Functions</STRONG> &gt; <STRONG>Create credit note</STRONG>, then the number of the corrective document is updated automatically.</P>
    > <P>For more information, see "Creating and using credit notes" and in the Applications and Business Processes Help.</P>



10. In the **Invoice date** field, select the date to be displayed in the corrected invoice.

11. Click **OK** to post the invoice.

12. Click **Accounts receivable** \> **Inquiries** \> **Journals** \> **Invoice journal**.
    

    > [!NOTE]
    > <P>The <STRONG>Corrective document</STRONG> check box is activated for the corrected invoice.</P>



13. Select the corrected sales invoice, and then click **Update facture** to open the **Update facture** form.

14. In the **Facture** field, under the **Correction** field group, select the facture number of the corrected facture.

15. In the **Facture date** field, select the date of the corrected facture.

16. In the **Corrected period** field, select the date of the corrected period.

17. On the **Invoice** tab in the lower section of the form, select the **To facture** check box to specify the corrected invoice that the facture is being created for.
    

    > [!NOTE]
    > <P>If you do not want to create a facture for a particular corrected invoice line, click the <STRONG>Invoice lines</STRONG> tab and clear the <STRONG>To facture</STRONG> check box.</P>



18. Click **Posting** \> **Update** to update the corrected facture.


> [!NOTE]
> <P>The corrected facture is displayed in the <STRONG>Facture journal</STRONG> form, and its reference is shown in the <STRONG>Correction</STRONG> field group. After you update the sales book lines, the corrected facture and the information in the <STRONG>Correction</STRONG> field group are reflected in the <STRONG>Sales book lines</STRONG> form.</P>


  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

