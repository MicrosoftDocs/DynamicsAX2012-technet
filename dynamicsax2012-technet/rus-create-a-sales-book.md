---
title: (RUS) Create a sales book
TOCTitle: (RUS) Create a sales book
ms:assetid: 2ec1b8bf-2e8d-4002-89d6-71574192bf8b
ms:mtpsurl: https://technet.microsoft.com/library/JJ665245(v=AX.60)
ms:contentKeyID: 49387334
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Create a sales book 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

VAT debt accrual is generated according to sales book entries. All factures for sales of goods, services, and advance payments from customers are included in the sales book.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Organization administration** \> **Setup** \> **Organization** \> **Legal entities**.

2.  Click the **Statutory reporting** FastTab and, in the **Report Folder** field, specify the folder that contains the purchase book template.

3.  Close the form.

4.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

5.  Click **Number sequences**, and in the **Number sequence code** field, select the number sequence for the reference type **Sales book**.

6.  Close the form.

7.  Click **Accounts receivable** \> **Periodic** \> **Sales book** \> **Sales books journal**. A list of previously created sales books is displayed in the form.

8.  Create a new sales book.
    

    > [!NOTE]
    > <P>The <STRONG>New</STRONG> button is available only if all books that are listed in the form are closed. The <STRONG>Code</STRONG> field is updated automatically, based on the sales book numbering sequence.</P>



9.  In the **Name** field, enter a name for the book.

10. Click **Update** to open the **Sales book** form.

11. In the **To date** field, select the end date of the settlement period for which the sales book is updated.
    

    > [!NOTE]
    > <P>When you create the first book, you can set only the end date. The dates cannot be edited for later books. The <STRONG>From date</STRONG> and <STRONG>To date</STRONG> fields are determined by the tax settlement period.</P>



12. Select the **Close the book** check box to close the book after the update.
    

    > [!NOTE]
    > <P>After you create and close the book, you cannot remove factures from the closed book. You cannot create new factures in a closed period.</P>



13. Click **OK** to create a new sales book. The lines of the sales book are refreshed, and the closing date is saved in the **Closed date** field of the book in the **Sales books journal** form.
    

    > [!NOTE]
    > <P>Click <STRONG>Delete</STRONG> to delete a sales book. Only the last book can be deleted regardless of whether it is closed or not.</P>



14. Click **Print** \> **Sales book** to print the sales book in the internal report.
    

    > [!NOTE]
    > <P>In the <STRONG>Sales books journal</STRONG> form, click <STRONG>Lines</STRONG> to open the <STRONG>Sales book lines</STRONG> form to verify the sales book line details.</P>


  


