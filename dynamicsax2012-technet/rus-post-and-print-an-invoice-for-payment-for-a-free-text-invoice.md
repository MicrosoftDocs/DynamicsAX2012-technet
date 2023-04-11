---
title: (RUS) Post and print an invoice for payment for a free text invoice
TOCTitle: (RUS) Post and print an invoice for payment for a free text invoice
ms:assetid: 012c9ca3-2098-4d05-90a0-8689878dd35c
ms:mtpsurl: https://technet.microsoft.com/library/JJ711339(v=AX.60)
ms:contentKeyID: 49387157
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Post and print an invoice for payment for a free text invoice 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

With the Invoice for payment for free text invoices function, you can use the **Posting invoice for payment** form to post and print a free text invoice for payment. After posting, the invoices are displayed in the **Journal of invoices for payment** form. You can post as many invoices for payment as necessary.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  Click the **Number sequences** tab.

3.  In the **Number sequence code** field, select the number sequence code for the invoice for payment reference type in the **Reference** field.

4.  Press CTRL+S or close the form.

5.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

6.  Press CTRL+N to create a free text invoice, and enter the required details.
    

    > [!NOTE]
    > <P>For more information, see "Create a free text invoice" and "Free text invoice (form)" in the Applications and Business Processes Help.</P>



7.  Click **Post** \> **Invoice for payment** to open the **Posting invoice for payment** form.
    

    > [!NOTE]
    > <P>If the free text invoice, or the facture for the free text invoice, has already been posted, the <STRONG>Invoice for paymen</STRONG>t option is not available.</P>



8.  In the **Print** field, select **Current** to print each invoice as it is updated, or select **After** to print after all of the invoices have been updated.

9.  Select the **Print** check box to print the invoice for payment after posting.

10. Select the **Print in national currency** check box to print the invoice for payment in national currency.

11. Select the **Use print management destination** check box to print the invoice for payment using print management destinations. Clear the check box to use the default printer settings.
    

    > [!NOTE]
    > <P>For more information, see "Set up print management for a transaction" and "Print management setup (form)" in the Applications and Business Processes Help.</P>



12. Click the **Officials** tab.

13. In the **Employee name** field, select the name of the responsible official from the list of company employees with the corresponding position title.

14. In the **Title** field, select the job title of the employee for the corresponding employee.
    

    > [!NOTE]
    > <P>Use the <STRONG>Officials</STRONG> form to set up the default officials to be listed on the invoice for payment.</P>



15. Click the **Other** tab. In the **Comments** field, enter a comment for the invoice for payment.

16. Click **OK** to post and print the invoice for payment.
    

    > [!NOTE]
    > <P>Click <STRONG>Accounts receivable</STRONG> &gt; <STRONG>Common</STRONG> &gt; <STRONG>Free text invoices</STRONG> &gt; <STRONG>All free text invoices</STRONG>. Click <STRONG>Related information</STRONG> &gt; <STRONG>Invoice for payment</STRONG> to view the posted invoice. Or click <STRONG>Accounts receivable</STRONG> &gt; <STRONG>Inquiries</STRONG> &gt; <STRONG>Journals</STRONG> &gt; <STRONG>Invoice for payment</STRONG>.</P>
    > <P>You can also use the <STRONG>Journal of invoice for payment</STRONG> form to print the invoice for payment.</P>



## See also

[(RUS) Posting invoice for payment (form)](https://technet.microsoft.com/library/jj665307\(v=ax.60\))

[(RUS) Journal of invoices for payment (form)](https://technet.microsoft.com/library/jj733219\(v=ax.60\))

  


