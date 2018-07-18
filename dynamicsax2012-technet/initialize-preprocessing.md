---
title: Initialize preprocessing
TOCTitle: Initialize preprocessing
ms:assetid: 592a6c93-0ce6-4958-890b-c619bb8410d9
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg731799(v=AX.60)
ms:contentKeyID: 35132644
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- scripts
- tables
- upgrade
- initialize
- dictionary
- shadow
---

# Initialize preprocessing 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Initialize preprocessing** task prepares the Microsoft Dynamics AX source system for data upgrade by creating shadow and dictionary tables for all the data tables that are in the live production database. The task also initializes the preprocessing scripts. The tables that are created by this step will hold the data that is created during upgrade preprocessing. Most of the data in the shadow and dictionary tables is created by the live and delta preprocessing scripts, though some records are created by each of the other preprocessing tasks.

To initialize preprocessing and create the shadow and dictionary tables, complete the following steps:

1.  In the **Preprocessing upgrade checklist**, expand **Prepare for upgrade**.

2.  Click **Initialize preprocessing**.

The upgrade framework creates the shadow and dictionary tables that are not created during importation of the preprocessing XPO and, when it finishes, opens an **Infolog** form that lists all the tables that were created. This step also loads the preprocessing scripts into upgrade framework tables.

After you finish the **Initialize preprocessing** task, you can connect to the source database from the Microsoft Dynamics AX 2012 target system and begin preparing the target database for upgrade. This allows you to save time by carrying out upgrade tasks concurrently on both systems.

  


