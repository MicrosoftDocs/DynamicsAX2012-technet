---
title: (RUS) Update a facture for invoices created in an invoice journal
TOCTitle: (RUS) Update a facture for invoices created in an invoice journal
ms:assetid: 4c8438c2-02cc-496d-8d50-f9ef9323fe97
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ665360(v=AX.60)
ms:contentKeyID: 49387448
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Update a facture for invoices created in an invoice journal 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice journal**.

2.  Press CTRL+N to create a new line, and enter the required details.
    

    > [!NOTE]
    > <P>For more information, see "Invoice journal lines (form)" in the Applications and Business Processes Help.</P>



3.  In the **Sales tax group** field, select the sales tax group to determine the tax.

4.  In the **Item sales tax group** field, select the item sales tax group to determine the tax.

5.  Click the **Invoice** tab. In the **Posting profile** field, select the posting profile code to determine the ledger account for the debt.

6.  In the **Invoice** field, enter the invoice number.

7.  Click **Post** \> **Post** to post the journal.

8.  Click **Accounts payable** \> **Inquiries** \> **Journals** \> **Invoice journal**.
    

    > [!NOTE]
    > <P>For these posted invoices, the <STRONG>Purchase order</STRONG> field remains empty.</P>



9.  Select the posted invoice for which you want to update the facture, and then click **Update facture** to open the **Update facture** form.

10. In the upper section of the form, in the **Facture** field, enter the facture number.

11. In the **Date of the registration** field, select the facture registration date.

12. In the **Facture date** field, select the facture creation date.
    

    > [!NOTE]
    > <P>This date is the same as the facture registration date. The field can be modified only if you clear the <STRONG>Same as</STRONG> check box.</P>



13. In the lower section of the form, on the **Invoice** tab, select the **To facture** check box for the invoice or invoices for the facture.
    

    > [!NOTE]
    > <P>If you do not want to create a facture for a particular invoice line, click the <STRONG>Invoice lines</STRONG> tab and clear the <STRONG>To facture</STRONG> check box.</P>



14. Click **Posting** \> **Update and print** to post and print the facture.
    
    –or–
    
    Click **Posting** \> **Update** to update the facture without printing.
    
    –or–
    
    Click **Posting** \> **Print** to print the facture without posting.
    

    > [!NOTE]
    > <P>Click <STRONG>Accounts payable</STRONG> &gt; <STRONG>Inquiries</STRONG> &gt; <STRONG>Journals</STRONG> &gt; <STRONG>Facture</STRONG>.</P>



## See also

[(RUS) Facture journal (form)](https://technet.microsoft.com/en-us/library/jj923567\(v=ax.60\))

  


