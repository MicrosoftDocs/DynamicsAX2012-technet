---
title: Hyper-V Benchmark for Microsoft Dynamics AX 2012
TOCTitle: Hyper-V Benchmark for Microsoft Dynamics AX 2012
ms:assetid: 68c32c12-0738-44c4-a42b-b25882643016
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh881829(v=AX.60)
ms:contentKeyID: 45769251
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Hyper-V Benchmark for Microsoft Dynamics AX 2012 [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012_

In December 2011, Microsoft conducted a benchmark to measure the performance and scalability characteristics of Microsoft Dynamics AX 2012 on physical servers, Windows Server 2008 R2 Hyper-V virtual servers, and a mixture of physical servers and Hyper-V virtual servers.

The benchmark simulated 300 concurrent users who were divided among four roles, and who ran a variety of functional scenarios that use different client and integration technologies, thereby providing a comparison view of ERP workload performance on Microsoft Dynamics AX 2012 on different server configurations. These scenarios include sales order creation through .NET Business Connector, and timesheet entry, expense entry, and purchase requisitions through Enterprise Portal for Microsoft Dynamics AX. The benchmark architecture consisted of one Microsoft SQL Server, one Application Object Server (AOS) server, one Enterprise Portal server, and a corresponding Hyper-V server that has the same hardware settings as the physical server. This white paper describes a series of test configurations we ran, which represented a variety of possible scenarios that involved SQL Server running on Hyper-V, an AOS server running on Hyper-V, and an Enterprise Portal server running on Hyper-V.

The following four server configurations were used to do the comparison:

  - All physical servers

  - Physical SQL Server, physical AOS server, virtual Enterprise Portal server

  - Physical SQL Server, virtual AOS server, virtual Enterprise Portal server

  - Virtual SQL Server, virtual AOS server, virtual Enterprise Portal server

We have published the following two papers about the Hyper-V benchmark:

  - [Hyper-V benchmark for Microsoft Dynamics AX 2012 (details)](http://go.microsoft.com/fwlink/?linkid=245625) – This paper provides detailed results of the Hyper-V benchmark testing, and can be downloaded from CustomerSource and PartnerSource.

  - [Hyper-V benchmark for Microsoft Dynamics AX 2012 (summary)](http://go.microsoft.com/fwlink/?linkid=245626) – This paper provides a summary of the Hyper-V benchmark results, and can be downloaded from CustomerSource and PartnerSource.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

