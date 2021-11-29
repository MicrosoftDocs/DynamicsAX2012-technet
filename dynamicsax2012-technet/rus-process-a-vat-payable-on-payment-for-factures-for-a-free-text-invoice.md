---
title: (RUS) Process a VAT payable on payment for factures for a free text invoice
TOCTitle: (RUS) Process a VAT payable on payment for factures for a free text invoice
ms:assetid: 34b32b24-2330-45e4-a42b-20f61d129435
ms:mtpsurl: https://technet.microsoft.com/library/JJ665268(v=AX.60)
ms:contentKeyID: 49387357
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Process a VAT payable on payment for factures for a free text invoice 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  Press CTRL+N to create a free text invoice, and enter the required details.
    

    > [!NOTE]
    > <P>For more information, see "Create a free text invoice" in the Applications and Business Processes Help.</P>



3.  Click the **Invoice** tab. Select the **VAT on payment** check box to configure accounting parameters for outgoing VAT from facture payments.

4.  Click **Posting** \> **Free text invoice** to open the **Post free text invoice** form.

5.  Click **OK** to post the free text invoice.

6.  Press CTRL+S or close the form.

7.  Click **Accounts receivable** \> **Inquiries** \> **Journals** \> **Invoice journal**.
    

    > [!NOTE]
    > <P>The <STRONG>VAT on payment</STRONG> check box will be activated for the posted free text invoice.</P>



8.  In the **Invoice Journal** form, click **Update facture** to open the **Update facture** form.

9.  In the upper section of the form, in the **Number sequence group** field, select the number sequence group to allocate different number sequences to different customers or vendors.
    

    > [!NOTE]
    > <P>The reference is used if an alternative document numbering is applied.</P>



10. In the **Date of the registration** field, select the facture registration date.

11. In the **Facture date** field, select the facture date.
    

    > [!NOTE]
    > <P>This field is available only if the <STRONG>Same as</STRONG> check box is cleared.</P>



12. In the lower pane of the form, on the **Invoice** tab, use the **To facture** check box to select the invoice or invoices for the facture.
    

    > [!NOTE]
    > <P>If you do not want to create a facture for a particular invoice line, click the <STRONG>Invoice lines</STRONG> tab and then clear the <STRONG>To facture</STRONG> check box.</P>



13. Click **Posting** \> **Update and print** to update and print the facture.
    
    –or–
    
    Click **Posting** \> **Update** to update the facture without printing.
    
    –or–
    
    Click **Posting** \> **Print** to print the facture without posting.


> [!NOTE]
> <P>If the <STRONG>VAT on payment</STRONG> check box is activated, the invoices will comply with the rules that were in effect prior to January 1, 2006.</P>
> <P>The part of the facture settled with the payment is displayed in the <STRONG>Sales book (Outgoing VAT processing)</STRONG> form.</P>


  


