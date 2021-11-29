---
title: Delete a batch job
TOCTitle: Delete a batch job
ms:assetid: 52acf8ba-d0b7-4677-8bab-12b0e2913cdb
ms:mtpsurl: https://technet.microsoft.com/library/Aa548919(v=AX.60)
ms:contentKeyID: 36057289
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Delete a batch job 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This article describes how to delete batch jobs that you no longer want to run.

## Delete an individual batch job

1.  Click **Home** \> **Inquiries** \> **Batch jobs** \> **My batch jobs**.

2.  Select the batch job from the list, and then press ALT+F9.


> [!NOTE]
> <P>If you are deleting a batch job that contains inventory journals, you can post an inventory journal again by clearing the <STRONG>Locked by system</STRONG> check box in the <STRONG>Inventory journal</STRONG> form.</P>



## Delete all jobs with a specific status

1.  Click **Home** \> **Inquiries** \> **Batch jobs** \> **My batch jobs**.

2.  Click **Functions**, and then select **Delete**.

3.  In the **Select batch transactions for deletion** dialog box, enter the criteria to use for deleting jobs.
    
    For example, to delete all jobs that have ended, for **Field** select **Status**, for **Criteria**, select **Ended**, and then click **OK**.

  


