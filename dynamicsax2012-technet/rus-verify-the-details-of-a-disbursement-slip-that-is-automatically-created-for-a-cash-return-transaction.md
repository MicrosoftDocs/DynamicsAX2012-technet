---
title: (RUS) Verify the details of a disbursement slip that is automatically created for a cash return transaction
TOCTitle: (RUS) Verify the details of a disbursement slip that is automatically created for a cash return transaction
ms:assetid: 6a0dd9cd-51cc-4013-ac05-1ead85102723
ms:mtpsurl: https://technet.microsoft.com/library/Dn716019(v=AX.60)
ms:contentKeyID: 62200267
author: Khairunj
ms.date: 04/28/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.LedgerJournalTable
- Forms.LedgerJournalTransRCash
- Forms.RCashTrans
- Forms.RetailStatementJour
audience: Application User
ms.search.region: Russia
---

# (RUS) Verify the details of a disbursement slip that is automatically created for a cash return transaction 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

After you set up Microsoft Dynamics AX to process return transactions for items that are returned during a shift that is different from the shift in which the items are sold at the point of sale (POS). You can use one of the following methods to process a cash return transaction during a different shift:

  - Automatically create a disbursement slip for the return transaction at the POS.

  - Register a disbursement slip in Microsoft Dynamics AX for the return transaction, and then specify the disbursement slip number during the return transaction at the POS.

Use the following procedure to verify the details of a disbursement slip that is created automatically for a cash return transaction.

1.  Click **Retail** \> **Inquiries** \> **Posted statements**.

2.  In the **Statement journal** form, select a statement to view the details for, and then click **Inquiries** \> **Cash payment journal**.

3.  In the **Slip journal** form, select a cash journal to view the details for, and then click **Lines** to open the **Journal voucher** form. For more information, see [(RUS) Journal voucher (form)](https://technet.microsoft.com/library/jj923409\(v=ax.60\)) and [(RUS) Journal voucher - Slip journal (form)](https://technet.microsoft.com/library/jj852151\(v=ax.60\)).

4.  Verify the details in the following fields on the **Cash order** tab:
    
      - **Name of person** – The name of the customer for the disbursement slip.
    
      - **Identity card** – The identity card details of the customer for the disbursement slip.

## See also

[(RUS) Post a statement for return transactions that are processed during a different shift](rus-post-a-statement-for-return-transactions-that-are-processed-during-a-different-shift.md)

[(RUS) Set up Microsoft Dynamics AX to process returns during a different shift](rus-set-up-microsoft-dynamics-ax-to-process-returns-during-a-different-shift.md)

  


