---
title: Select invoices to settle with payments on behalf of multiple legal entities
TOCTitle: Select invoices to settle with payments on behalf of multiple legal entities
ms:assetid: 462738d8-b17f-4529-9d49-274862f9d4eb
ms:mtpsurl: https://technet.microsoft.com/library/Gg231384(v=AX.60)
ms:contentKeyID: 36056901
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Select invoices to settle with payments on behalf of multiple legal entities 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In organizations that use centralized payment processing, each operating legal entity manages its own invoices receivable information. Payments from customers are received by a single legal entity, which is referred to as the legal entity of the payment. Use this procedure to select invoices to settle. For more information, see [Key tasks: Customer payments and settlements](key-tasks-customer-payments-and-settlements.md).

1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Create a journal and then click **Lines**. For information about how to create a journal, see [Create and validate journals and journal lines](create-and-validate-journals-and-journal-lines.md).

3.  In the **Journal voucher** form, click **Payment proposal** \> **Create payment proposal**.

4.  In the **Customer payment proposal** form, in the **Proposal type** form, select the type of payment proposal to create.

5.  Enter a range of payment dates to include in the payment proposal.

6.  Select the **Include customer invoices from other legal entities** check box. The posting profile for each proposed payment will be blank.
    

    > [!NOTE]
    > <P>By default, the payment proposal includes invoices for all legal entities that are included in the organizational hierarchy that is set up for centralized payments. If necessary, you can click <STRONG>Select</STRONG> and use the <STRONG>Company range</STRONG> tab to select a subset of legal entities whose invoices you want to include in the payment proposal.</P>



7.  To create a separate payment for each customer account in each legal entity, select the **Propose separate customer payment per legal entity** check box.
    
    To create a single payment for each customer account that includes invoices for that customer in all selected legal entities, clear this check box.

8.  You can select a default offset account type and a default offset account.
    

    > [!NOTE]
    > <P>If you do not select an account type, the account type for each payment is based on the method of payment.</P>



9.  Add other criteria as needed in the other fields in this form, and then click **OK**.

10. In the **Customer payment proposal** form, review the proposal. When you are satisfied with it, click **Transfer**, and then click **OK** to confirm the transfer.

11. In the **Journal voucher** form, select a line and then click the **Payment** tab.

12. Select a posting profile.

13. Repeat steps 11 and 12 for the remaining lines in the payment proposal.

## See also

[About centralized customer payments](about-centralized-customer-payments.md)

[Customer payment proposal (class form)](https://technet.microsoft.com/library/aa550814\(v=ax.60\))

  


