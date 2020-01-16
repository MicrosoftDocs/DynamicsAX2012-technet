---
title: Use batch processing to improve performance when documents are posted or printed
TOCTitle: Use batch processing to improve performance when documents are posted or printed
ms:assetid: a0c773eb-6ca2-4005-b958-e04b0b483c20
ms:mtpsurl: https://technet.microsoft.com/library/JJ933494(v=AX.60)
ms:contentKeyID: 50935108
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Use batch processing to improve performance when documents are posted or printed 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012_

To improve performance when you post source documents or print statements that include large amounts of data, use batch processing. When you use batch processing, you can run specific tasks as batch jobs, and then schedule those batch jobs to be run on a different computer (a batch server). When you move the processing of these tasks to a batch server, the report performance on the client computer can improve. You can also apply range restrictions to limit the size of each batch. You can improve performance by submitting multiple, smaller batches to be processed at the same time on different servers, instead of submitting one large batch.

Many tasks in Microsoft Dynamics AX can be run as part of batch jobs. For more information, see [Batch processing overview](batch-processing-overview.md).

  


