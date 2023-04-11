---
title: Approve or reject an invoice proposal
TOCTitle: Approve or reject an invoice proposal
ms:assetid: 99ca5d37-b0eb-4cbd-9d1a-83ccc963717d
ms:mtpsurl: https://technet.microsoft.com/library/Hh209423(v=AX.60)
ms:contentKeyID: 36058700
author: tfehr
ms.author: daxcpft
ms.date: 10/06/2014
mtps_version: v=AX.60
f1_keywords:
- invoice proposal
- approve invoice proposal
- revoke invoice proposal
- project parameters
audience: Application User
ms.search.region: Global
---

# Approve or reject an invoice proposal 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create a preliminary customer invoice for transactions that were posted to a project. This preliminary invoice is called an invoice proposal. After you review an invoice proposal, you can approve or reject it.

If you approve an invoice proposal, and then decide that the invoice proposal is invalid, you can cancel the invoice proposal.

**Prerequisites**

You can approve or reject an invoice proposal only if the following conditions are true:

  - In the **Project management and accounting parameters** form, on the **Invoice** tab, the **Enable processing invoice proposals in workflow** check box is selected.

  - A workflow is set up for reviewing invoice proposals.

### Approve an invoice proposal

1.  Click **Project management and accounting** \> **Common** \> **Project invoices** \> **Project invoice proposals**.

2.  On the **Invoice proposals** list page, select or open the invoice proposal that you want to approve.

3.  In the workflow message bar, click **Actions**, and then click **Approve**.

### Reject an invoice proposal

1.  Click **Project management and accounting** \> **Common** \> **Project invoices** \> **Project invoice proposals**.

2.  On the **Invoice proposals** list page, select the invoice proposal that you want to reject.

3.  In the workflow message bar, click **Actions**, and then click **Reject**.

## See also

[Project management and accounting parameters (form)](https://technet.microsoft.com/library/aa599440\(v=ax.60\))

[Invoice proposals (form)](https://technet.microsoft.com/library/aa615408\(v=ax.60\))

[About invoice proposals](about-invoice-proposals.md)

[Create an invoice for a time and material project](create-an-invoice-for-a-time-and-material-project.md)

  


