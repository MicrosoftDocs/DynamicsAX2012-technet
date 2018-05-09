---
title: Cancel a postdated check for a vendor
TOCTitle: Cancel a postdated check for a vendor
ms:assetid: bb93a0db-b2b7-45ab-a834-7670dfc243f0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242769(v=AX.60)
ms:contentKeyID: 36059131
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- checks
- postdated checks
---

# Cancel a postdated check for a vendor 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Vendor postdated checks** form to cancel a postdated check issued to a vendor. For more information, see [Vendor postdated checks (form)](https://technet.microsoft.com/en-us/library/hh242868\(v=ax.60\)).

You can cancel a posted postdated check when:

  - The check is returned by the bank.

  - The check is applied to an incorrect invoice.

  - A cash payment is made against the check.

<!-- end list -->

1.  Click **Accounts payable** \> **Common** \> **Postdated checks** \> **Vendor postdated checks**.

2.  Select a postdated check that you registered and posted. For more information, see [Register and post a postdated check for a vendor](register-and-post-a-postdated-check-for-a-vendor.md).

3.  Click **Cancel postdated check** to cancel the postdated check. The **Postdated check status** field is updated to **Cancelled**.

4.  Close the form to save your changes.

If the **Post journal entries for postdated checks** check box is selected in the **General ledger parameters** form, the transaction for the check is reversed in the vendor payment journal. If the **Post journal entries for postdated checks** check box is not selected, the vendor payment journal for the check is deleted.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

