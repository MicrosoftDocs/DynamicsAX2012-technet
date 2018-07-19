---
title: About scheduling helpers
TOCTitle: About scheduling helpers
ms:assetid: 5b905e71-fce0-436d-a161-d4685ad64c73
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg242496(v=AX.60)
ms:contentKeyID: 43876667
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About scheduling helpers 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use scheduling helpers to reduce the time that is required to process items during master scheduling and forecast scheduling. Scheduling helpers are multiple processes that simultaneously calculate the same scheduling plan.

Based on the parameters that you set in the **Master scheduling** or **Forecast scheduling** form, the items are distributed for processing among the available batch servers.

Scheduling helpers process items by bill of material (BOM) level, starting with the items with the lowest-level value. In other words, the processing starts from the top of the product structure. All of the scheduling helpers process items at the same level and do not proceed to the next level until all of the helpers are finished processing. Therefore, there are no conflicts or internal interdependencies among the helper threads.

When you run scheduling, the batch framework enables the automatic launching of scheduling helpers. Each helper is launched as a subtask to the batch header of the scheduling process. If a batch header does not exist, it is created.

## See also

[Master scheduling (class form)](https://technet.microsoft.com/en-us/library/aa616758\(v=ax.60\))

[Forecast scheduling (class form)](https://technet.microsoft.com/en-us/library/aa619452\(v=ax.60\))

[Unfinished scheduling processes (form)](https://technet.microsoft.com/en-us/library/hh227390\(v=ax.60\))

[Item process duration (form)](https://technet.microsoft.com/en-us/library/hh242287\(v=ax.60\))

[Thread list (form)](https://technet.microsoft.com/en-us/library/hh242895\(v=ax.60\))

  


