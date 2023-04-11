---
title: Set up permissions for ordering products on behalf of someone else
TOCTitle: Set up permissions for ordering products on behalf of someone else
ms:assetid: 0f0a0036-7331-470c-a8b8-c92e97c709f0
ms:mtpsurl: https://technet.microsoft.com/library/Hh242135(v=AX.60)
ms:contentKeyID: 36056015
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- permissions
- Buy on behalf of
- Purchase requisition
- Purchase requisition permissions
audience: Application User
ms.search.region: Global
---

# Set up permissions for ordering products on behalf of someone else 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

As an administrator of the purchasing process, you can grant permissions to workers to prepare purchase requisitions on behalf of other workers. You can also grant permissions for a worker to order items and services in one or more legal entities or operating units.

## Set up permissions for ordering products on behalf of someone else

### Grant permissions to a preparer to enter purchase requisitions for a worker

1.  Click **Procurement and sourcing** \> **Setup** \> **Policies** \> **Purchase requisition permissions**.

2.  In the **Purchase requisition permissions** form, in the **Current view** field, select **By preparer**. Then select a preparer from the list in the left pane.

3.  On the **Requester** FastTab, click **Add**.

4.  In the **Name** field, select the worker for whom the preparer is authorized to create purchase requisitions, and then click **Select**.

5.  In the **Authorization** field, select one of the following options:
    
      - **Specific** –The selected preparer can create purchase requisitions only for the selected worker.
    
      - **Reporting** – The selected preparer can create purchase requisitions for this worker and all workers who report to this worker.

6.  In the **Effective** field, enter the date on which the selected worker can begin entering purchase requisitions for this worker.

7.  In the **Expiration** field, enter the last date on which the selected worker can enter purchase requisitions for this worker.

8.  To view a list of preparers who have been granted permissions to create purchase requisitions for a selected worker, in the **Purchase requisition permissions** form, in the **Current view** field, select **By requester**. Then select a requester from the list in the left pane.

9.  To grant permissions to additional preparers to enter purchase requisitions for the selected worker, on the **Preparer** FastTab, click **Add**. Then select a worker from the list and enter an effective and expiration date.

### Grant permissions to a worker to order items or services in another legal entity or operating unit

1.  Click **Procurement and sourcing** \> **Setup** \> **Policies** \> **Purchase requisition permissions**.

2.  In the **Purchase requisition permissions** form, in the **Current view** field, select **By requester**. Then select a worker from the list in the left pane.

3.  To grant permission to the worker to order items and services in other legal entities, on the **Legal entity** FastTab, click **Add**. Then, in the **Buying legal entity** field, select a legal entity.
    

    > [!NOTE]
    > <P>This grants permission to the worker to order products in legal entities other than the primary legal entity that the worker is assigned to.</P>



4.  In the **Effective** field, enter the date on which the worker can begin ordering items and services in this legal entity.

5.  In the **Expiration** field, enter the last date on which the worker can order items and services in this legal entity.

6.  To grant permission to the worker to order items and services in other operating units, on the **Operating unit** FastTab, click **Add**. Then, in the **Receiving operating unit** field, select an operating unit.
    

    > [!NOTE]
    > <P>This grants permission to the worker to order products in operating units other than the primary operating unit in which the worker holds a position.</P>



7.  In the **Effective** field, enter the date on which the worker can begin ordering items and services in this operating unit.

8.  In the **Expiration** field, enter the last date on which the worker can order items and services in this operating unit.

## See also

[Purchase requisition permissions (form)](https://technet.microsoft.com/library/hh242815\(v=ax.60\))

[Purchase requisitions (form)](https://technet.microsoft.com/library/hh209453\(v=ax.60\))

[About purchase requisitions](about-purchase-requisitions.md)

[Key tasks: Create and submit a purchase requisition](key-tasks-create-and-submit-a-purchase-requisition.md)

  


