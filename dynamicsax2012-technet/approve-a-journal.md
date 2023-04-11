---
title: Approve a journal
TOCTitle: Approve a journal
ms:assetid: 37784aa9-378e-4a18-a82d-3eb364937835
ms:mtpsurl: https://technet.microsoft.com/library/Aa570130(v=AX.60)
ms:contentKeyID: 36056607
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Approve a journal 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If journals are approved by a user other than the one who enters the journal lines, an approval system can be set up. The posting function will be unavailable until the approver has approved the journal. If the journal is rejected instead of approved, it cannot be posted. You can view the approval history on the **History** tab of the **Journal** and **Journal voucher** forms. For more information, see [Set up financial journal approvals](set-up-financial-journal-approvals.md).


> [!NOTE]
> <P>The manual approval system can be used in most of the <STRONG>Journal</STRONG> forms and in the lines of the journals. To open the <STRONG>Journal voucher</STRONG> form, which contains the journal lines, click <STRONG>Lines</STRONG> in the journal.</P>



## Submit a journal for approval

A user enters data in the journal for which the approval system is set up. The **Post** button is unavailable until the journal has been approved.

1.  Open a **Journal** form and select a journal name for which the approval system is active.

2.  Click **Lines** and create journal lines. For more information, see [Create and validate journals and journal lines](create-and-validate-journals-and-journal-lines.md).

3.  Select the journal lines that are ready for approval, click **Approval**, and then click **Report as ready**.

## Approve a journal

A member of the user group that was designated in the **Journal names** form can approve the journal.

1.  In the same **Journal** form (or the same **Journal voucher** form), click **Approval**, and then click **Approve** to approve the journal.
    

    > [!NOTE]
    > <P>If the journal contains errors, click <STRONG>Reject</STRONG>. The journal then can be corrected and submitted again for approval.</P>



2.  Click **Post** to post the journal lines or the journal.

## See also

[Post and print a journal or journal lines](post-and-print-a-journal-or-journal-lines.md)

[Journal names setup (form)](https://technet.microsoft.com/library/aa552517\(v=ax.60\))

  


