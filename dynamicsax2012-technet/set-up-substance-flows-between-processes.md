---
title: Set up substance flows between processes
TOCTitle: Set up substance flows between processes
ms:assetid: 37ca8d37-6aec-4582-bdef-666beea6762c
ms:mtpsurl: https://technet.microsoft.com/library/Hh242204(v=AX.60)
ms:contentKeyID: 36056611
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up substance flows between processes 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can set up a substance flow between a source process and a destination process. You can also specify the substances or substance categories that flow between the two processes. You can reference more than one substance, substance category, and destination process from a single source process. Enter each reference on a separate budget line in the form.

1.  Click **Compliance and internal controls** \> **Common** \> **Environmental sustainability** \> **Environmental processes** \> **Environmental process references**.

2.  Click **New** to create a new line.

3.  Select a source process and a destination process for the substance.

4.  Select a substance or a substance category.

5.  In the **Scope** field, select the scope for the substance or substance category. You can select a different scope for each substance or substance category coming from a source process. For more information about **Scope**, see [Environmental process references (form)](https://technet.microsoft.com/library/hh209500\(v=ax.60\)).

6.  Enter the frequency and the time interval for entering substance flow data in the **Frequency** and **Entry interval** fields.
    
    For example, if you enter 2 in the **Frequency** field and you select **Month** in the **Entry interval** field, the data will be entered once every two months.

7.  On the **Budget lines** tab, click **Add** to create a new substance flow forecast line.

8.  Enter the quantity of the substance and the start and end dates of the substance flow.
    
    These lines can be used to forecast or budget how much of a substance will be used during a specified time period.

## See also

[Environmental process references (form)](https://technet.microsoft.com/library/hh209500\(v=ax.60\))

[Set up substances for environmental tracking](set-up-substances-for-environmental-tracking.md)

[Set up substance categories](set-up-substance-categories.md)

[Set up environmental processes](set-up-environmental-processes.md)

  


