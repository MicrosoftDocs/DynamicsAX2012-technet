---
title: Approve or reject absences
TOCTitle: Approve or reject absences
ms:assetid: 14cfd517-1c47-4bdc-8d9e-6cebb02a2d66
ms:mtpsurl: https://technet.microsoft.com/library/Aa496620(v=AX.60)
ms:contentKeyID: 36966698
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Approve or reject absences 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If you are an absence administrator, you can approve or reject a registered or requested absence, or cancel a previous approval for a requested absence.

## Approve or reject a registered absence

Before you can approve or reject a registered absence, the registered absence must be transferred for approval. For more information, see [Transfer absence journals for approval](transfer-absence-journals-for-approval.md).

If you reject an absence journal, the absence registrations within that journal will be available in the **Register absences** form, where a worker can update the registrations in the journal and then resubmit it for approval.

1.  Click **Home** \> **Common** \> **Absences** \> **Approve absence requests**.

2.  In the upper pane, select the journal to approve or reject.

3.  In the lower pane, review the absence registrations for the selected journal.

4.  To approve the absence journal and all of the absence registrations in it, click **Approve**.
    
    To reject the absence journal and all of the absence registrations in it, on the **Notes** tab, enter a reason for the rejection, and then click **Reject**.

## Approve or reject an absence request

You can approve or reject only absence requests that have a status of **Transferred**. Also, in order to approve an absence request for a worker, an absence journal must be available for the worker for a period that includes the absence date.

1.  Click **Home** \> **Common** \> **Absences** \> **Request absence approval**.

2.  In the upper pane, select the worker to approve or reject absence requests for.

3.  In the lower pane, select the absence requests to approve or reject.

4.  To approve the absence requests, click **Approve**. When you approve an absence request, the absence is transferred to an absence journal as an absence registration.
    
    To reject the absence requests, click **Reject**.

## Cancel an approved absence request

1.  Click **Home** \> **Common** \> **Absences** \> **Request absence approval**.

2.  In the upper pane, select the worker to cancel absence requests for.

3.  In the lower pane, select the approved absence request to cancel.

4.  Click **Cancel**. When you cancel an approved absence request, the corresponding absence registration is removed from the absence journal.

## See also

[Create absence journals](create-absence-journals.md)

[Key task: Set up absence information](key-task-set-up-absence-information.md)

[Approve absence requests (form)](https://technet.microsoft.com/library/aa500373\(v=ax.60\))

[Request absence approval (form)](https://technet.microsoft.com/library/aa586020\(v=ax.60\))

[Request future absences (form)](https://technet.microsoft.com/library/aa556621\(v=ax.60\))

[Register absences for multiple workers (form)](https://technet.microsoft.com/library/aa554509\(v=ax.60\))

  


