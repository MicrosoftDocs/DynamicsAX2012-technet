---
title: Specify absence information for a worker
TOCTitle: Specify absence information for a worker
ms:assetid: 716fe8d7-f7a2-4add-a80a-27b6ae14e4c0
ms:mtpsurl: https://technet.microsoft.com/library/Hh450756(v=AX.60)
ms:contentKeyID: 36966728
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Specify absence information for a worker 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You must specify absence information for a worker before you can enter, transfer, or approve absence registrations or requests for that worker.

Use the **Absence** area in the **Worker** form to specify the following absence information for each worker whose absences should be tracked.


> [!NOTE]
> <P>If the worker is employed by multiple legal entities, you must specify absence information for the worker for each legal entity that the worker is employed by.</P>



## Absence setup

The absence setup for a worker determines who the absence administrator for the worker is, the length of the worker’s absence periods, and the whether the worker’s absences will be tracked in days or hours. For more information about absence setups, see [Key task: Set up absence information](key-task-set-up-absence-information.md).


> [!NOTE]
> <P>Before you can select an absence setup for a worker, absence setups must be created in the legal entity where the worker is employed.</P>



## Absence date

The absence date is the earliest date when the worker can submit an absence registration or absence request. For example, if Alicia Samuel is hired on September 9, 2011, but her employment agreement indicates that she cannot be absent from work until October 15, 2011, you would enter 10/15/2011 as the absence date.

## Working time

For each day of the week, enter the number of working hours that the worker is expected to work. The total hours per work week is calculated for you in the **Total working hours** field. This information is used for reporting and also to calculate the default hours for the absence registrations or requests that you create.

## See also

[About absence administration](about-absence-administration.md)

[Manage absence in Human resources](manage-absence-in-human-resources.md)

[Absence setup (form)](https://technet.microsoft.com/library/aa583231\(v=ax.60\))

[Request future absences (form)](https://technet.microsoft.com/library/aa556621\(v=ax.60\))

[Worker (form)](https://technet.microsoft.com/library/hh209054\(v=ax.60\))

  


