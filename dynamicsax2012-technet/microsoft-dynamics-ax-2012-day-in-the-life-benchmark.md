---
title: Microsoft Dynamics AX 2012 Day in the Life Benchmark
TOCTitle: Microsoft Dynamics AX 2012 Day in the Life Benchmark
ms:assetid: f6030832-b299-42f5-9b8c-7c0fef5a2c71
ms:mtpsurl: https://technet.microsoft.com/library/Hh500191(v=AX.60)
ms:contentKeyID: 37820258
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Microsoft Dynamics AX 2012 Day in the Life Benchmark 


_**Applies To:** Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In August 2011, Microsoft conducted a “day in the life” benchmark of Microsoft Dynamics AX 2012 to measure the application’s performance and scalability characteristics.

The benchmark runs a variety of functional scenarios that use different client and integration technologies, thereby providing a view of ERP workload performance on Microsoft Dynamics AX 2012. This benchmark includes rich client simulations of core accounts receivable scenarios, from order entry through invoicing, quotation management, item arrivals, transfer orders, and payment processing. Enterprise Portal for Microsoft Dynamics AX is used to create timesheets and purchase requisitions. Purchase requisitions are converted into purchase orders through a workflow, and then posted to the general ledger. Services and Application Integration Framework (AIF) are used to generate sales orders. Batch processing with a Microsoft Dynamics AX 2012 asynchronous batch server is used to post general journals and invoice the sales orders that are received through services and AIF.

These scenarios generate load on an instance of Application Object Server (AOS). In this benchmark, some of the AOS instances are configured as multiple logical AOS instances in a cluster.

With this concurrent workload, a 48-core 256-gigabyte database server sustained 77-percent CPU utilization, while demonstrating the ability of Microsoft Dynamics AX 2012 to scale up and scale out on the AOS tier. User experience measures were below 2 to 3 seconds for intensive posting operations, and line save operations averaged sub-second response times. The benchmark simulated 5,135 concurrent users who were divided among three roles. The benchmark demonstrated a sustained rate of more than 1 million lines per hour for these concurrent scenarios.

The benchmark results demonstrate the ability of Microsoft Dynamics AX 2012 to handle various specialized loads concurrently, without compromising performance and scalability for critical business processes.

We have published the following two papers about the “day in the life” benchmark:

  - [Microsoft Dynamics AX 2012 “Day in the life” benchmark detailed results](https://go.microsoft.com/fwlink/?linkid=230564) – This paper provides detailed results of the “Day in the life” benchmark testing, and can be downloaded from CustomerSource and PartnerSource.

  - [Microsoft Dynamics AX 2012 “Day in the life” benchmark summary](https://go.microsoft.com/fwlink/?linkid=230566) – This paper provides a summary of the “day in the life” benchmark results, and can be downloaded from CustomerSource and PartnerSource.

  


