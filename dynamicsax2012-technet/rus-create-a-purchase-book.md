---
title: (RUS) Create a purchase book
TOCTitle: (RUS) Create a purchase book
ms:assetid: 468d621b-5b1c-4159-ac1a-600f7553bcbf
ms:mtpsurl: https://technet.microsoft.com/library/JJ665339(v=AX.60)
ms:contentKeyID: 49387427
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Create a purchase book 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

A purchase book is a tax accounting document. In a purchase book, you can record vendor factures, factures on returns and credit notes to vendors, factures on advance reports from advance holders, factures on customer prepayments, and corrected tax transaction factures.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Organization administration** \> **Setup** \> **Organization** \> **Legal entities**.

2.  Click the **Statutory reporting** FastTab and, in the **Report Folder** field, specify the folder that contains the purchase book template.

3.  Close the form.

4.  Click **Accounts payable** \> **Setup** \> **Accounts payable parameters**.

5.  Click **Number sequences**, and in the **Number sequence code** field, select the number sequence for the reference type **Purchase book**.

6.  Close the form.

7.  Click **Accounts payable** \> **Periodic** \> **Purchase book** \> **Purchase books journal**.. A list of previously created purchase books is displayed in the form.

8.  Create a new purchase book.
    

    > [!NOTE]
    > <P>The <STRONG>New</STRONG> button is available only if all books that are listed in the form are closed. The <STRONG>Code</STRONG> field is updated automatically based on the purchase book numbering sequence.</P>



9.  In the **Name** field, enter a name for the book.

10. Click **Update** to open the **Purchase book** form.
    

    > [!NOTE]
    > <P>You can only update an open book.</P>



11. In the **To date** field, select the end date of the settlement period for which the purchase book is updated.
    

    > [!NOTE]
    > <P>When you create the first book, you can set only the end date. The dates cannot be edited for later books. The <STRONG>From date</STRONG> and <STRONG>To date</STRONG> fields are determined by the tax settlement period.</P>



12. Select the **Close the book** check box to close the book after the update.

13. Click **OK** to create a new purchase book. The lines of the purchase book are refreshed, and the closing date is saved in the **Closed date** field of the book in the **Purchase books journal** form.
    

    > [!NOTE]
    > <P>Click <STRONG>Delete</STRONG> to delete a purchase book. Only the last book can be deleted regardless of whether it is closed or not.</P>



14. Click **Print** \> **Purchase book** to print the purchase book in the internal report.
    

    > [!NOTE]
    > <P>In the <STRONG>Purchase books journal</STRONG> form, click <STRONG>Lines</STRONG> to open the <STRONG>Purchase book lines</STRONG> form to verify purchase book line details.</P>


  


