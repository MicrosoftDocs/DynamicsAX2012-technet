---
title: Run delta preprocessing scripts
TOCTitle: Run delta preprocessing scripts
ms:assetid: 93a36d22-1877-4823-ae20-08d0d167922a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg731872(v=AX.60)
ms:contentKeyID: 35132768
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- update
- upgrade
- delta
- preprocessing
---

# Run delta preprocessing scripts 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You run the delta preprocessing scripts after you complete the **Global address book country/region upgrade** task on the Microsoft Dynamics AX source system. The delta preprocessing scripts check for changes to the production data that have occurred since you started running the live preprocessing scripts. Then, like the live preprocessing scripts, the delta scripts process the updated data into the shadow and dictionary tables.

Like the live preprocessing scripts, the delta preprocessing scripts run while your Microsoft Dynamics AX source system is live and being used for production. To optimize performance, you can pause some or all of the delta scripts by using the **Manage running tasks** form.


> [!NOTE]
> <P>Some delta preprocessing scripts cannot be paused. These scripts appear in the grid with a <STRONG>Task state</STRONG> that says <EM>The task does not support pausing</EM>.</P>



You can run the delta preprocessing scripts multiple times until you are ready to enter single-user mode. To minimize downtime, make sure to run the delta preprocessing scripts just before entering single-user mode.

## Run the delta preprocessing scripts

1.  In the **Preprocessing upgrade checklist**, click **Run delta preprocessing scripts**.

2.  In the **Upgrade delta preprocessing** form, click **Run**.

## Pause and resume the delta preprocessing scripts

Complete the following steps to pause delta preprocessing scripts.

1.  In the **Upgrade delta preprocessing** form, click **Manage running tasks**.

2.  In the **Manage running tasks** form, do one of the following:
    
      - To pause a single script, select a running script from the grid, and then click **Pause task**.
    
      - To pause all running scripts, click **Pause all tasks**.

Complete the following steps to resume a paused script.

1.  In the **Upgrade live preprocessing** form, click **Manage running tasks**.

2.  In the **Manage running tasks** form, select a paused script from the grid, and then click **Resume task**.

## See also

[Upgrade preprocessing scripts (form)](https://technet.microsoft.com/en-us/library/hh202100\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

