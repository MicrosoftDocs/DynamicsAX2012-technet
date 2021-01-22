---
title: (BRA) Cancel a free text invoice
TOCTitle: (BRA) Cancel a free text invoice
ms:assetid: 8671d464-5e1b-4afa-8e97-9251dfeb54e6
ms:mtpsurl: https://technet.microsoft.com/library/JJ710557(v=AX.60)
ms:contentKeyID: 49384447
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- free text invoice
- create invoice
- Brazil
- (BRA)
- Cancel free text invoice
audience: Application User
ms.search.region: Brazil
---

# (BRA) Cancel a free text invoice 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can cancel a posted free text invoice that is incorrect. When you cancel a free text invoice, a negative free text invoice is created. When you post the negative free text invoice, the original and negative free text invoices are marked as canceled, and all the ledger and financial transactions are reversed. The original transaction is reported in the fiscal books as canceled, and the negative transaction is not reported in the fiscal books.

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  Select a posted free text invoice to cancel.

3.  On the **Action Pane**, on the **Invoice** tab, click **Cancel fiscal document**.

4.  In the **Reason code** field, select the reason code for the reason to cancel the free text invoice. The **Comments** field is updated with the comments for the selected reason code. These comments are specified in the **Default comment** field in the **Customer reasons** form.

5.  In the **Canceling invoice date** field, enter the date when the invoice is canceled.

6.  Click **Cancel invoice** to create a free text invoice that has a negative quantity and amount in the **Free text invoice** form.

7.  On the **Action Pane**, on the **Invoice** tab, click **Post** to open the **Post free text invoice** form.

8.  Click the **Bill of lading** tab, and then in the **Volume type** and **Volume quantity** fields, enter the volume type and volume quantity that are used in an invoice posting.
    

    > [!NOTE]
    > <P>The <STRONG>Bill of lading</STRONG> tab is available only if the <STRONG>Service invoice</STRONG> check box is not selected on the <STRONG>Fiscal information invoice line</STRONG> tab on the <STRONG>Line details</STRONG> FastTab in the <STRONG>Free text invoice</STRONG> form.</P>



9.  Click **OK** to cancel the free text invoice and reverse all the ledger and financial transactions.

  


