---
title: Enterprise Portal Benchmark for Microsoft Dynamics AX 2012
TOCTitle: Enterprise Portal Benchmark for Microsoft Dynamics AX 2012
ms:assetid: 78620ec1-47bc-4df0-a521-19d43a642a2b
ms:mtpsurl: https://technet.microsoft.com/library/Hh881830(v=AX.60)
ms:contentKeyID: 45769252
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Enterprise Portal Benchmark for Microsoft Dynamics AX 2012 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012_

In January 2012, Microsoft conducted a benchmark of Enterprise Portal for Microsoft Dynamics AX 2012 to measure its performance and scalability characteristics.

The benchmark runs a variety of functional scenarios that use Enterprise Portal, thereby providing a view of ERP workload performance on Microsoft Dynamics AX 2012. This benchmark includes creating timesheets, entering expenses, and entering purchase requisitions. The benchmark architecture consisted of two load-balanced Application Object Server (AOS) instances that served web users from ten Enterprise Portal servers, and three workflow servers to process approvals. The benchmark simulated 10,000 concurrent users divided among three roles.

The benchmark demonstrated a sustained rate of more than 741,587 lines per hour for these concurrent scenarios. With this concurrent workload, a 48-core, 256-gigabyte (GB) database server sustained 55-percent CPU utilization; two 12-core, 16-GB AOS servers sustained 57-percent CPU utilization; ten 8–12 core, 16-GB Enterprise Portal servers sustained 47-percent to 85-percent CPU utilization; and an 8-core, 16-GB Microsoft Windows Server AppFabric cache server sustained 7-percent CPU utilization and 73-percent memory utilization.

The benchmark results demonstrate the ability of Enterprise Portal to handle various loads concurrently, without compromising performance and scalability for critical business processes.

We have published the following two papers about the Enterprise Portal benchmark:

  - [Enterprise Portal benchmark for Microsoft Dynamics AX (details)](https://go.microsoft.com/fwlink/?linkid=245627) – This paper provides detailed results of the Enterprise Portal benchmark testing, and can be downloaded from CustomerSource and PartnerSource.

  - [Enterprise Portal benchmark for Microsoft Dynamics AX (summary)](https://go.microsoft.com/fwlink/?linkid=245631) – This paper provides a summary of the Enterprise Portal benchmark results, and can be downloaded from CustomerSource and PartnerSource.

  


