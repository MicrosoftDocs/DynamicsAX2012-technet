---
title: Post invoices in the Invoice approval journal form
TOCTitle: Post invoices in the Invoice approval journal form
ms:assetid: f79de90e-a2f4-4bf0-be6d-e6733dcd6574
ms:mtpsurl: https://technet.microsoft.com/library/Aa499801(v=AX.60)
ms:contentKeyID: 36060037
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Post invoices in the Invoice approval journal form 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this information to post invoices that have been entered in an invoice pool.

1.  Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice approval journal**.

2.  Create a journal. For more information, see [Create and validate journals and journal lines](create-and-validate-journals-and-journal-lines.md).

3.  Click **Lines** to open the **Journal voucher** form.
    

    > [!NOTE]
    > <P>If budget control is turned on and the appropriate source documents and journals are enabled for budget control, the <STRONG>Journal voucher</STRONG> form can display a budget check icon. A red X indicates that the budget check failed, a yellow triangle indicates that the budget check passed with warnings, and a green check mark indicates that the budget check passed. Budget check results can be affected by project budget control settings, over budget permissions, and other budget control parameters and settings. For more information, see <A href="about-budget-control.md">About budget control</A>.</P>



4.  Click **Find vouchers** to open the list of invoice vouchers in the invoice pool. These invoices are posted to temporary accounts and are awaiting approval.

5.  Select the invoice vouchers that have been approved, click **Select** to move them to the lower pane, and then click **OK**.
    
    –or–
    
    To select all vouchers, click **Select all**, and then click **OK**.

6.  Select a voucher in the upper pane of the **Journal voucher** form. In the lower pane, view the transaction lines that are created when the voucher is posted.
    
    Ledger accounts from the temporary posting are already selected for these lines, but you must select the appropriate ledger account for the open line.

7.  Click **Validate** \> **Validate voucher only** to verify that the invoice in the upper pane is ready for posting.
    

    > [!NOTE]
    > <P>Instead of validating each line, you can click <STRONG>Validate</STRONG> &gt; <STRONG>Validate</STRONG> when the account information is complete for all the invoices.</P>



8.  Repeat steps 6 and 7 until you have entered account information for all of the invoices.

9.  Click **Post** \> **Post**.

The posted invoices can now be settled in the **Payment journal** form. If you cannot post, and you receive a message that mentions posting restrictions, you can post only the journals that you created. For more information, see [Posting restrictions (form)](https://technet.microsoft.com/library/hh227598\(v=ax.60\)).

## See also

[About fixed assets integration](about-fixed-assets-integration.md)

  


