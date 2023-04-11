---
title: Set up a minimum/maximum key
TOCTitle: Set up a minimum/maximum key
ms:assetid: d9f71886-d730-400f-9b64-847d7de7fe2c
ms:mtpsurl: https://technet.microsoft.com/library/Aa551208(v=AX.60)
ms:contentKeyID: 36941360
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- minimum/maximum key
audience: Application User
ms.search.region: Global
---

# Set up a minimum/maximum key 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to create and set up a minimum or maximum key.

1.  Click **Master planning** \> **Setup** \> **Coverage** \> **Minimum/maximum keys**.

2.  Click **New** or press Ctrl+N to create a new minimum/maximum key.

3.  Enter an identifier and name for the key.

4.  On the **Periods** FastTab, enter the following information:
    
      - Define the periods during which you want the key to be used.
    
      - Specify the factor that you want to apply to the key for each period.
    
      - Specify the starting date and ending date, or the validity dates, for each period.

**Example**

You want to set up a minimum key that accounts for increased seasonal demand during the spring and summer months.

1.  Create 12 lines, and number the lines from 1 to 12 in the **Change** field.

2.  In the **Unit** field, select **Months**.

3.  In the **Factor** field, enter the values that are described in the following table.
    
    <table>
    <colgroup>
    <col style="width: 33%" />
    <col style="width: 33%" />
    <col style="width: 33%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Line</p></th>
    <th><p>Enter this value</p></th>
    <th><p>Result</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>1–3</p></td>
    <td><p>1</p></td>
    <td><p>Minimum inventory is based on the setting for January through March in the <strong>Item coverage</strong> form.</p></td>
    </tr>
    <tr class="even">
    <td><p>4–5</p></td>
    <td><p>2</p></td>
    <td><p>Minimum inventory is multiplied by a factor of 2 for April and May.</p></td>
    </tr>
    <tr class="odd">
    <td><p>6–8</p></td>
    <td><p>2.5</p></td>
    <td><p>Minimum inventory is multiplied by a factor of 2.5 for June through August.</p></td>
    </tr>
    <tr class="even">
    <td><p>9–12</p></td>
    <td><p>1</p></td>
    <td><p>Minimum inventory reverts to the setting for September through December in the <strong>Item coverage</strong> form.</p></td>
    </tr>
    </tbody>
    </table>


## See also

[Minimum/maximum keys (form)](https://technet.microsoft.com/library/aa633906\(v=ax.60\))

  


