---
title: Cancel a postdated check from a customer
TOCTitle: Cancel a postdated check from a customer
ms:assetid: 1aca7e73-4e7d-4274-a2d8-6807dc36857d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208455(v=AX.60)
ms:contentKeyID: 36056127
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- checks
- postdated checks
---

# Cancel a postdated check from a customer [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Customer postdated checks** form to cancel a postdated check received from a customer. For more information, see [Customer postdated checks (form)](https://technet.microsoft.com/en-us/library/hh227493\(v=ax.60\)). You can cancel a posted postdated check when:

  - The check is returned by the bank.

  - The check is applied to an incorrect invoice.

  - A cash payment is made against the check.

<!-- end list -->

1.  Click **Accounts receivable** \> **Common** \> **Postdated checks** \> **Customer postdated checks**.

2.  Select a postdated check that you registered and posted. For more information, see [Register and post a postdated check from a customer](register-and-post-a-postdated-check-from-a-customer.md).

3.  Click **Cancel postdated check** to cancel the postdated check. The **Postdated check status** field is updated to **Cancelled**.

4.  Close the form to save your changes.

If the **Post journal entries for postdated checks** check box is selected in the **Cash and bank management parameters** form, the transaction for the check is reversed in the customer payment journal. If the **Post journal entries for postdated checks** check box is not selected, the customer payment journal for the check is deleted.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

