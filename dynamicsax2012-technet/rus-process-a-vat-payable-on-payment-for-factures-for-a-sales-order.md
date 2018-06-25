---
title: (RUS) Process a VAT payable on payment for factures for a sales order
TOCTitle: (RUS) Process a VAT payable on payment for factures for a sales order
ms:assetid: dadcb50d-d25e-4d4b-9c75-f2fb11fcd826
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711680(v=AX.60)
ms:contentKeyID: 49388003
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Process a VAT payable on payment for factures for a sales order [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.
    

    > [!NOTE]
    > <P></P>



2.  Click **Posting** \> **Invoice** to open the **Posting invoice** form.

3.  Click the **Additional** tab and select the **VAT on payment** check box to configure accounting parameters for outgoing VAT from facture payments.

4.  Click **OK** to post the sales invoice.

5.  Press CTRL+S or close the form.

6.  Click **Accounts receivable** \> **Inquiries** \> **History** \> **Invoice**.
    

    > [!NOTE]
    > <P>The <STRONG>VAT on payment</STRONG> check box will be activated for the posted sales invoice.</P>



7.  In the **Invoice Journal** form, click **Update facture** to open the **Update facture** form.

8.  In the upper section of the form, in the **Number sequence group** field, select the number sequence group to allocate different number sequences to different customers or vendors.
    

    > [!NOTE]
    > <P>The reference is used if an alternative document numbering is applied.</P>



9.  In the **Date of the registration** field, select the facture registration date.

10. In the **Facture date** field, select the facture date.
    

    > [!NOTE]
    > <P>This field is available only if the <STRONG>Same as</STRONG> check box is cleared.</P>



11. In the lower section of the form, on the **Invoice** tab, select the **To facture** check box invoice or invoices under which a facture will be created.
    

    > [!NOTE]
    > <P>If you do not want to create a facture for a particular invoice line, click the <STRONG>Invoice lines</STRONG> tab and then clear the <STRONG>To facture</STRONG> check box.</P>



12. Click **Posting** \> **Update and print** to update and print the facture.
    
    –or–
    
    Click **Posting** \> **Update** to update a facture without printing.
    
    –or–
    
    Click **Posting** \> **Print** to print the facture without posting.


> [!NOTE]
> <P>Invoices with the <STRONG>VAT on payment</STRONG> check box activated will take into account the rules that were effective before January 1, 2006. The part of the facture settled with the payment is displayed in the <STRONG>Sales book (Outgoing VAT processing)</STRONG> form.</P>


  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

