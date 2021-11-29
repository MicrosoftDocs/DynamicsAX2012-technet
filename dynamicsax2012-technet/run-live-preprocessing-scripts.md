---
title: Run live preprocessing scripts
TOCTitle: Run live preprocessing scripts
ms:assetid: 84af1a02-486c-482e-8ef0-b3797bef292f
ms:mtpsurl: https://technet.microsoft.com/library/Gg731849(v=AX.60)
ms:contentKeyID: 35132709
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- scripts
- online
- upgrade
- live
- production
---

# Run live preprocessing scripts 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Run live preprocessing scripts** task opens the **Upgrade live preprocessing** form and displays the scripts that will write prepared data into the shadow and dictionary tables that were created by the [Initialize preprocessing](initialize-preprocessing.md) task. After you run the live preprocessing scripts, you must correct any issues that are flagged with an error status in the grid. After you correct an issue, you must rerun the failed script, or all failed scripts, until all live preprocessing scripts finish without error. You cannot proceed to running the single-user mode preprocessing scripts until you resolve all live preprocessing script errors.

## Run the live preprocessing scripts

Depending on the amount of data you are processing, running the live preprocessing scripts may take a long time. The scripts run while your Microsoft Dynamics AX source system is live and being used for production. This can slow system performance. To lessen the impact of preprocessing on your live system, you can pause some or all of the scripts during business hours and resume them after business hours.


> [!IMPORTANT]
> <P>If you are upgrading from Microsoft Dynamics AX 4.0, the Microsoft Dynamics AX must be operating in the DAT company context for upgrade batch jobs to be picked up correctly.</P>




> [!NOTE]
> <P>Some live preprocessing scripts cannot be paused. These scripts appear in the grid with a task status of <STRONG>The task does not support pausing</STRONG>.</P>



Complete the following steps to begin running the live preprocessing scripts.

1.  In the **Preprocessing upgrade checklist**, click **Run live preprocessing scripts**.

2.  In the **Upgrade live preprocessing** form, click **Run**.

## Pause and resume live preprocessing scripts

Complete the following steps to pause live preprocessing scripts.

1.  In the **Upgrade live preprocessing** form, click **Manage running tasks**.

2.  In the **Manage running tasks** form, do one of the following:
    
      - To pause a single script, select the script in the grid, and then click **Pause task**.
    
      - To pause all scripts, click **Pause all tasks**.

Complete the following steps to resume a paused script.

1.  In the **Upgrade live preprocessing** form, click **Manage running tasks**.

2.  In the **Manage running tasks** form, select a paused script in the grid, and then click **Resume task**.

## See also

[Upgrade preprocessing scripts (form)](https://technet.microsoft.com/library/hh202100\(v=ax.60\))

  


