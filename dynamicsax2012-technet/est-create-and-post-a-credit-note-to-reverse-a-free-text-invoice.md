---
title: (EST) Create and post a credit note to reverse a free text invoice
TOCTitle: (EST) Create and post a credit note to reverse a free text invoice
ms:assetid: 904f4117-c1a3-489b-8225-f1bec1b52911
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ710864(v=AX.60)
ms:contentKeyID: 49385260
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- reversal
- free text invoice
- fixed asset
- credit note
- post a credit note
- create a credit note
- reverse free text invoice
---

# (EST) Create and post a credit note to reverse a free text invoice 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use a credit note to reverse a free text invoice that was generated for the sale of a fixed asset. When you create a credit note, you must include each transaction line from the free text invoice.

All credit notes that are created by your organization should include the original invoice number for the transaction.


> [!NOTE]
> <P>You can set up a credit invoice layout that is specific to Estonia that includes a field that displays the original invoice number. This number is displayed in the <STRONG>Main invoice no.</STRONG> field on the printed invoice.</P>



1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**. Select the free text invoice that you are creating a credit note for, and then, on the **Action Pane**, in the **Cancel** group, click **Create credit note**.
    
    For more information, see [Creating credit notes](creating-credit-notes.md).

2.  In the **Reason code** field, select the reason for creating the credit note.

3.  Select the **Create corrective lines** check box to add a reversal line and a corrective line to the credit note for each transaction line in the original free text invoice.

4.  On the **Invoice** tab, select the **Mark** check box next to each invoice line that must be added to the credit note.

5.  Click **OK** to add the selected lines to the invoice and return to the **Free text invoice** form.

6.  On the **Action Pane**, click **Post**.

7.  In the **Post free text invoice** form, select the **Print invoice** check box, and then click **OK** to post and print the credit note.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

