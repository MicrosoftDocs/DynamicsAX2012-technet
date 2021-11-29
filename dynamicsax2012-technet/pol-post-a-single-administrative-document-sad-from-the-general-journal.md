---
title: (POL) Post a Single Administrative Document (SAD) from the general journal
TOCTitle: (POL) Post a Single Administrative Document (SAD) from the general journal
ms:assetid: 2f552576-1e6b-4186-97db-d3958bc477ba
ms:mtpsurl: https://technet.microsoft.com/library/JJ731079(v=AX.60)
ms:contentKeyID: 49675319
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Poland
---

# (POL) Post a Single Administrative Document (SAD) from the general journal 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes how to create a Single Administrative Document (SAD), and how to post the SAD transactions by using the general journal.

Before you start working with SADs, you must verify the setup of number sequences, main accounts for SADs, and duty rates groups. For more information, see [(POL) Set up parameters for a Single Administrative Document (SAD)](pol-set-up-parameters-for-a-single-administrative-document-sad.md).

To provide an item commodity code for the SAD references, you must set up an item code. Click **General ledger** \> **Setup** \> **Item codes for SAD**. Click **New** to create an item code.

1.  Click **General ledger** \> **Journals** \> **General journal**.

2.  Click **New** to create a journal, or select an existing journal to generate a transaction for.

3.  Click **SAD documents** to open the **SAD documents** form.

4.  Complete the fields on the **SAD documents** FastTab. For information about the fields on this FastTab, see [(POL) SAD documents (form)](https://technet.microsoft.com/library/jj678156\(v=ax.60\)).

5.  On the **SAD document references** FastTab, on the **Positions of SAD** tab, in the **Position** field, enter the line number of the document.

6.  If you have to create additional position lines, click **New**. For each position, enter the tax amounts to increase the sales tax amount of the document.

7.  Complete the remaining fields on the **Positions of SAD** tab. For information about the fields on this tab, see [(POL) SAD documents (form)](https://technet.microsoft.com/library/jj678156\(v=ax.60\)).

8.  On the **Invoices for SAD - ledger** tab and the **Items from the SAD document** tab, create lines, and then complete the fields on these tabs. The amount in the **Total** field on the **Invoices for SAD - ledger** tab is calculated from the amounts on the lines for each invoice number. The **Total** field value cannot be changed, and the value is displayed only when all the required values are entered on all the tabs.
    
    For information about the fields on these tabs, see [(POL) SAD documents (form)](https://technet.microsoft.com/library/jj678156\(v=ax.60\)).

9.  Click **Create lines for the SAD document** to generate the transactions for the current document. New journal lines that represent postings for the SAD are created in the **Journal voucher** form for the selected journal line.

10. Close the **SAD documents** form, and then, in the **General journal** form, click **Lines** to open the **Journal voucher** form. Click **Post** to post the transactions for the SAD.

## See also

[(POL) Set up parameters for a Single Administrative Document (SAD)](pol-set-up-parameters-for-a-single-administrative-document-sad.md)

[(POL) Post a Single Administrative Document (SAD) from the SAD](pol-post-a-single-administrative-document-sad-from-the-sad.md)

[(POL) SAD documents (form)](https://technet.microsoft.com/library/jj678156\(v=ax.60\))

  


