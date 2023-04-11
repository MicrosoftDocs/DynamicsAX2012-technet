---
title: (RUS) Create a tax register journal
TOCTitle: (RUS) Create a tax register journal
ms:assetid: 0767b13a-a74d-46b0-b335-84e22d1361d4
ms:mtpsurl: https://technet.microsoft.com/library/JJ711368(v=AX.60)
ms:contentKeyID: 49387186
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Create a tax register journal 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



The tax registers that must be presented for a reporting period are consolidated into a periodic tax register journal. You can create a new tax register journal only if all journals for previous periods have been approved.


> [!NOTE]
> <P>For more information, see <A href="rus-approve-the-register.md">(RUS) Approve the register</A>.</P>



1.  Click **General ledger** \> **Journals** \> **Tax register journal**.

2.  Press CTRL+N to create a new journal.

3.  In the **Journal batch number** field, enter the batch number of the journal.
    

    > [!NOTE]
    > <P>For more information, see <A href="rus-set-up-the-numbering-sequence-for-the-tax-register-journal.md">(RUS) Set up the numbering sequence for the tax register journal</A>.</P>



4.  In the **Description of the journal** field, enter a description for the journal.

5.  In the **Period types** field, select the type of time period for which the register is created.

6.  In the **Period number** field, enter the period for which the journal is to be generated.

7.  In the **Years** field, enter the year.

8.  Click **Lines** to open the **Register journal lines** form and create register journal lines.
    

    > [!NOTE]
    > <P>The <STRONG>Approved</STRONG> check box is automatically selected if all the journal lines are approved in the <STRONG>Register journal lines</STRONG> form.</P>



9.  Click **Print** to print the tax declarations.

10. Press CTRL+S or close the form.
    

    > [!NOTE]
    > <P>To delete an unapproved journal, click <STRONG>Delete rows</STRONG> in the <STRONG>Register journal lines</STRONG> form to delete the journal lines, and then delete the journal in the <STRONG>Tax register journal</STRONG> form.</P>



## See also

[(RUS) Tax register journal (form)](https://technet.microsoft.com/library/jj856114\(v=ax.60\))

[(RUS) Register journal lines (form)](https://technet.microsoft.com/library/jj839663\(v=ax.60\))

  


