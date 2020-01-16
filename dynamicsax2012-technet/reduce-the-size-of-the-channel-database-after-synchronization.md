---
title: Reduce the size of the channel database after synchronization
TOCTitle: Reduce the size of the channel database after synchronization
ms:assetid: cac181bb-1a67-4f31-a56c-5f02f514d0ff
ms:mtpsurl: https://technet.microsoft.com/library/Mt807869(v=AX.60)
ms:contentKeyID: 74436958
author: Khairunj
ms.date: 04/04/2017
mtps_version: v=AX.60
---

# Reduce the size of the channel database after synchronization 


If your organization has large channel databases, you may want to consider installing KB 3208173, and then configuring your environment to automatically remove unwanted master data from your database after each synchronization. You can customize the data that is removed.

## Install KB 3208173

To use this feature, you must download 3208173 from Dynamics Lifecycle Services and install it on the AOS, Channel database, and Async client. For instructions, see [Apply updates and hotfixes](apply-updates-and-hotfixes.md).

## Configure removal of unwanted data after synchronization

1.  Open the **Retail schedule parameters** form (**Retail** \> **Setup**\> **Retail schedule parameters**).

2.  Select **Remove unneeded master data from channel database**.

3.  Run Commerce data exchange schedule 1110 to sync this change to the channel database.
    
    After the configuration has been synchronized, the Async client will remove unwanted master data from the channel database.

## Customize which data is removed

You can customize which data is removed by modifying the **crt.STRIPMASTERDATA** stored procedure in the channel database.

  


