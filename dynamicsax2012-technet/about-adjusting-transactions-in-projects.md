---
title: About adjusting transactions in projects
TOCTitle: About adjusting transactions in projects
ms:assetid: f7da01a6-cb5c-406b-baa3-c807a446f2fe
ms:mtpsurl: https://technet.microsoft.com/library/Hh227554(v=AX.60)
ms:contentKeyID: 36060042
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About adjusting transactions in projects 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can configure Project management and accounting parameters to allow workers who have permissions to modify project parameters to adjust certain transactions. For example, you might be able to adjust transactions that have a status of Posted or Invoiced, but not those that have a status of Invoice proposal, Estimated, or Eliminated.

These permissions are included in the Project supervisor role by default. The Project supervisor also has the capability to assign these permissions to other workers. Other configuration options set by your Project supervisor can affect how adjustments are made. For example, the project date for adjustment transactions can be set to either the original transaction date or the adjustment date. The Project supervisor can also configure adjustment options so that adjustment records are created automatically.

Transaction lines can either be adjusted as a whole or split into multiple lines so that only part of the transaction is changed.

You can also view the adjustment history of a transaction to see which user made each adjustment.


> [!WARNING]
> <P>If you make an adjustment to an intercompany timesheet, the general ledger accounts of the two legal entities that are involved in the adjusted transaction may become out of balance. In this case, you must manually adjust the account balances.</P>



## See also

[Adjust transactions](adjust-transactions.md)

[Adjust transactions (class form) (Project)](https://technet.microsoft.com/library/aa583326\(v=ax.60\))

[Adjustments (form)](https://technet.microsoft.com/library/aa553205\(v=ax.60\))

[Create adjustment transactions (class form)](https://technet.microsoft.com/library/aa634561\(v=ax.60\))

[View and record transactions](view-and-record-transactions.md)

[View transaction adjustment history](view-transaction-adjustment-history.md)

  


