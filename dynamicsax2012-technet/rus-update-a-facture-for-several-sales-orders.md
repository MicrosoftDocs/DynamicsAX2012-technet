---
title: (RUS) Update a facture for several sales orders
TOCTitle: (RUS) Update a facture for several sales orders
ms:assetid: 11248845-21a7-4e67-a617-cebf1470295c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711397(v=AX.60)
ms:contentKeyID: 49387215
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Update a facture for several sales orders [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In general, only one invoice is included in each facture. However, sometimes it is necessary to include more than one invoice in a facture.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts receivable** \> **Periodic** \> **Sales update** \> **Invoice**.

2.  Select the invoice account, and then click **Update facture** to open the **Update facture** form.

3.  In the **Number sequence group** field, select the number sequence group to allocate different number sequences to different customers or vendors.
    

    > [!NOTE]
    > <P>The reference is used if an alternative document numbering is applied.</P>



4.  In the upper section of the form, in the **Date of the registration** field, select the facture registration date.

5.  In the **Facture date** field, select the facture creation date.
    

    > [!NOTE]
    > <P>This date is the same as the facture registration date. The field is can be modified only if you clear the <STRONG>Same as</STRONG> check box.</P>



6.  In the lower section of the form, on the **Invoice** tab, use the **To facture** check box to select the invoices for the facture.
    

    > [!NOTE]
    > <P>If you do not want to create a facture for a particular invoice line, click the <STRONG>Invoice lines</STRONG> tab and clear the <STRONG>To facture</STRONG> check box.</P>



7.  Click **Posting** \> **Update and print** to update and print the facture.
    
    –or–
    
    Click **Posting** \> **Update** to update a facture without printing.
    
    –or–
    
    Click **Posting** \> **Print** to print the facture without posting.
    

    > [!NOTE]
    > <P>Click <STRONG>Accounts receivable</STRONG> &gt; <STRONG>Inquiries</STRONG> &gt; <STRONG>History</STRONG> &gt; <STRONG>Invoice</STRONG>.</P>


  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

