---
title: (EEUR) Correct a free text invoice using a credit note
TOCTitle: (EEUR) Correct a free text invoice using a credit note
ms:assetid: a6b96e39-10d7-43c6-b8fb-bd3a5145835b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ911005(v=AX.60)
ms:contentKeyID: 52075303
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Czech Republic, Estonia, Hungary, Latvia, Lithuania, Poland, Russia
---

# (EEUR) Correct a free text invoice using a credit note 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When you correct an invoice that has been posted, a corrected invoice is created, and you can modify the invoice and post it with the new values. When you post the corrected invoice, a canceling invoice is created, which brings the combined balance of the original invoice and the canceling invoice to a zero amount.

When a free text invoice has already been issued, you should use a credit note to correct the original invoice. A credit note contains a reference to the original invoice, all corrected and optional corrective lines, and the reason for the correction.

For example, if you correct an original posted invoice that has a balance of 500.00, a corrected invoice will be created that has a balance of 500.00. You can change the information for the invoice, and then post it. When the corrected invoice is posted, a canceling invoice will be created that has a balance of -500.00. This brings the combined balance of the original and canceling invoices to 0.00.

## Prerequisites

Before you can create a credit note, you must follow these steps.

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**. In the **Ledger** area, on the **Accounting rules** FastTab, select the **Correction** check box. Transactions that have negative amounts can now be posted as corrections in the general ledger.

2.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**. In the **Updates** area, on the **Invoice** FastTab, select the **Credit note as correction** check box.

## Correct a free text invoice

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  Select a posted invoice.

3.  On the **Action Pane**, click **Create credit note**, and then enter the following information:
    
      - **Reason code** – Enter or select the reason code that describes why the invoice is being corrected.
    
      - **Reason comment** – Enter any additional comments about the invoice cancellation.
    
      - **Create corrective lines** – Select this check box to create a corrected invoice. Select the invoice date to assign to the canceling invoice.
    
      - **Copy exchange rate** – Select this check box to copy the exchange rate from the original invoice to the free text cred note.
    

    > [!NOTE]
    > <P>By default, the <STRONG>Create corrective lines</STRONG> check box is selected. A selected check box indicates that both the corrected and corrective lines are created. To reverse the original transaction without creating a corrective line, clear the <STRONG>Create corrective lines</STRONG> check box.</P>



4.  Click **Edit** and make any necessary changes to the invoice.

5.  In the **Free text invoice** form, on the **Action Pane**, click **Post** and then click **OK**. The corrected invoice is posted, and a canceling invoice is automatically created.
    

    > [!TIP]
    > <P>To view the original invoice and the credit note, in the <STRONG>Related information</STRONG> group, click <STRONG>Invoice journal</STRONG> to open the <STRONG>Invoice journal</STRONG> form.</P>


  


