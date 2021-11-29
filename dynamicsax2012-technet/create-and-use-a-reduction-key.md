---
title: Create and use a reduction key
TOCTitle: Create and use a reduction key
ms:assetid: b29dcc9d-e77a-4efa-a8a1-1b36b04783c9
ms:mtpsurl: https://technet.microsoft.com/library/Aa498658(v=AX.60)
ms:contentKeyID: 36059060
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- forecast consumption
- forecast reduction
- forecast, consume
- forecast, reduce
audience: Application User
ms.search.region: Global
---

# Create and use a reduction key 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use these procedures to create and use a reduction key:

  - Create and set up a reduction key

  - Use a reduction key

### Create and set up a reduction key

1.  Click **Master planning** \> **Setup** \> **Coverage** \> **Reduction keys**.

2.  Click **New** or press **CTRL+N** to create a new reduction key.

3.  Enter an identifier for the key in the **Reduction key** field, and then enter a name for it in the **Name** field.

4.  On the **Periods** tab, enter the following information:
    
      - Define the time periods during which you want the forecast reduction to occur.
    
      - For a particular time period, specify the percentages by which you want to reduce forecast requirements.
    
      - Specify start dates and end dates to define when the time period is valid.

### Use a reduction key

1.  Click **Master planning** \> **Setup** \> **Coverage** \> **Coverage groups**.

2.  In the **Reduction key** field on the **Other** tab, select a reduction key to assign to the coverage group. The reduction key then applies for the items that belong to the coverage group.

3.  To use a reduction key to calculate forecast reduction during master scheduling, you must define this setting in the forecast plan or the master plan setup.
    
    Click **Master planning** \> **Setup** \> **Plans** \> **Forecast plans**.
    
    –or–
    
    Click **Master planning** \> **Setup** \> **Plans** \> **Master plans**.

4.  In the **Reduction principle** field on the **General** tab, select the **Percent - reduction key** option or the **Transactions - reduction key** option.

## See also

[Reduction keys (form)](https://technet.microsoft.com/library/aa553816\(v=ax.60\))

[Example: Use reduction keys](example-use-reduction-keys.md)

  


