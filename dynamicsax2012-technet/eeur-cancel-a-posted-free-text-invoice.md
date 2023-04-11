---
title: (EEUR) Cancel a posted free text invoice
TOCTitle: (EEUR) Cancel a posted free text invoice
ms:assetid: 70e0f7b6-9008-42fb-9f14-550324ec3638
ms:mtpsurl: https://technet.microsoft.com/library/JJ730990(v=AX.60)
ms:contentKeyID: 49675232
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Czech Republic, Estonia, Hungary, Latvia, Lithuania, Poland, Russia
---

# (EEUR) Cancel a posted free text invoice 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to cancel a free text invoice that has been posted. If you want to cancel an invoice and create a corrected invoice at the same time, see [Correct a posted free text invoice](correct-a-posted-free-text-invoice.md).

When you cancel a posted invoice, a canceling invoice is created. The combined balance of the original invoice and the canceling invoice is 0 (zero). For example, if you cancel a posted invoice that has a balance of 500.00, the canceling invoice that is created has a balance of -500.00. Therefore, the combined balance of the original and canceling invoices is 0.00.


> [!NOTE]
> <P>This feature is available only if the <STRONG>Free text invoice correction</STRONG> configuration key is selected.</P>



1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  Select a posted invoice.

3.  On the **Action Pane**, click **Correct invoice**, and then enter the following information:
    
      - **Reason code** – Enter or select the reason code that describes why the invoice is being canceled.
    
      - **Comments** – Enter any additional comments about the invoice cancellation.
    
      - **Canceling invoice date** – Enter or select the invoice date to assign to the canceling invoice.
    
      - **Create canceling invoice only** – Select this check box to create only the canceling invoice.

4.  Click **Create corrected invoice**. A canceling invoice is created if you selected the **Create canceling invoice only** check box.

## See also

[(EEUR) Create corrected invoice (form)](https://technet.microsoft.com/library/jj710746\(v=ax.60\))

[Correct a posted free text invoice](correct-a-posted-free-text-invoice.md)

  


