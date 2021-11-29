---
title: (CHN) Create, approve, and post a general journal
TOCTitle: (CHN) Create, approve, and post a general journal
ms:assetid: 0b6cf5af-a5a3-4f22-83f7-544ad3003492
ms:mtpsurl: https://technet.microsoft.com/library/JJ663991(v=AX.60)
ms:contentKeyID: 49384577
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: China (PRC)
---

# (CHN) Create, approve, and post a general journal 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create, approve, and post a general journal that contains lines by using the **Chinese vouchers** form. To record a customer payment, you must create a journal header, enter voucher transactions on the journal lines, approve the voucher, and then post the voucher to the general ledger.

To create voucher transactions, you must select the **Chinese voucher system** check box in the **General ledger parameters** form. You can also approve and post multiple journals for customer payments.

1.  Click **General ledger** \> **Journals** \> **Chinese vouchers**.

2.  Click **New** to create a new record, and then in the **Name** field, select the general journal that you created in the **Journal names** form. For more information, see [About journal names](about-journal-names.md).

3.  On the **General journal lines** FastTab, click **Add line**, and then in the **Voucher type** field, select a voucher type for the voucher. The number sequence that is associated with the voucher type generates the Chinese voucher number in the **Chinese voucher** field.

4.  In the **Account type** field, select the **Ledger**, and then in the **Account** field, select the ledger account.

5.  In the **Description** field, select transaction text to describe the transaction.

6.  In the **Credit** field, enter the amount to pay the customer.

7.  In the **Offset account type** field, select **Ledger**, and then in the **Offset account** field, select the offset account.

8.  Click **Validate** \> **Validate** to validate the journal.

9.  Select the journal, and then click **Approval** \> **Report as ready** to indicate that the journal is ready for approval. The **Approval status** field of the journal is updated to **Ready**.
    

    > [!NOTE]
    > <P>The journal is available for approval only if you select the <STRONG>Active</STRONG> check box for the journal name in the <STRONG>Journal names</STRONG> form.</P>



10. In the left pane, select the journal lines that are ready for approval, and then click **Approval** \> **Approve** to open the **Approve journals** form.
    

    > [!NOTE]
    > <P>If the journal contains errors, click <STRONG>Reject</STRONG>. The journal can then be corrected and resubmitted for approval.</P>



11. Click **OK** to approve the journal.

12. Select a journal that has been approved, and then click **Post** \> **Post** to post the journal.

## See also

[(CHN) Chinese vouchers (form)](https://technet.microsoft.com/library/jj664151\(v=ax.60\))

[(CHN) Run a batch job to check the continuity of voucher numbers](chn-run-a-batch-job-to-check-the-continuity-of-voucher-numbers.md)

  


