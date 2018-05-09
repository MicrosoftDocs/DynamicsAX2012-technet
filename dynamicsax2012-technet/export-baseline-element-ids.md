---
title: Export baseline element IDs
TOCTitle: Export baseline element IDs
ms:assetid: 58661815-619c-43a1-9c22-6fc0332b8a04
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn497766(v=AX.60)
ms:contentKeyID: 62200023
ms.date: 04/29/2014
mtps_version: v=AX.60
---

# Export baseline element IDs 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The **Export baseline element IDs** task generates a CSV file containing element IDs from all of the populated layers of the baseline model store. These legacy element IDs are needed in order to preserve consistency between metadata and business data.

The generated CSV file is automatically saved to C:\\Users\\\<username\>\\AppData\\Local\\Temp\\18\\SysUpgradeExportIdMap.csv. In the next task, **Preserve legacy element IDs**, you will use axutil to apply the element IDs in this file to the databases being upgraded.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

