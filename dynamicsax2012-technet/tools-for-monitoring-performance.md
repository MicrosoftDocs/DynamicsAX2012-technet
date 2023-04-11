---
title: Tools for monitoring performance
TOCTitle: Tools for monitoring performance
ms:assetid: 2e740397-8bf2-41d1-8855-98b4397a5b83
ms:mtpsurl: https://technet.microsoft.com/library/JJ149695(v=AX.60)
ms:contentKeyID: 47541246
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Tools for monitoring performance 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

We recommend the following tools for monitoring the performance of Microsoft Dynamics AX.

  - Microsoft Dynamics AX 2012 Trace Parser – Trace Parser ships with Microsoft Dynamics AX. Trace Parser consolidates information from multiple sources, such as remote procedure calls (RPCs) and Microsoft SQL Server, to provide an integrated view of application performance at run time. For more information, see the following resources:
    
      - [Install the Trace Parser](install-the-trace-parser.md)
    
      - [Tracing Cockpit Form](https://technet.microsoft.com/library/hh272149\(v=ax.60\))
    
      - [Walk through major features of Microsoft Dynamics AX 2012 Trace Parser (Part 1)](https://blogs.msdn.com/b/axperf/archive/2011/08/15/walk-through-major-features-of-microsoft-dynamics-ax-2012.aspx)
    
      - [Walk through major features of Microsoft Dynamics AX 2012 Trace Parser (Part 2)](https://blogs.msdn.com/b/axperf/archive/2011/09/06/walk-through-the-major-features-in-microsoft-dynamics-ax-2012-trace-parser-part-2.aspx)

  - [Performance Monitor](https://technet.microsoft.com/library/cc749115.aspx) – Performance Monitor is the basic tool for obtaining an overview of performance. You can review the CPU, disk, and memory counters to find performance issues. After you have identified a time frame during which your system may have experienced performance problems, you can add more specific counters to understand the problem in more detail. For more information, see the following resources:
    
      - [Set up Performance Monitor counters](set-up-performance-monitor-counters.md)
    
      - [Collect AX 2012 event traces with Windows Performance Monitor](https://blogs.msdn.com/b/axperf/archive/2011/11/18/collect-ax-2012-event-traces-with-windows-performance-monitor.aspx)

  - [Performance Analyzer for Microsoft Dynamics AX (DynamicsPerf)](https://blogs.msdn.com/b/axinthefield/archive/2011/02/28/setting-up-performance-analyzer-for-microsoft-dynamics.aspx) – DynamicsPerf can be used to collect information from Microsoft Dynamics AX and SQL Server. DynamicsPerf consists of a database and a collection of scripts that collect information from SQL Server and Microsoft Dynamics AX. Based on this information, you can find issues such as expensive queries and locking/blocking. When you have gained experience, you can also use this tool to find inefficient code or business processes.

  - [System Center Operations Manager Monitoring Pack for Microsoft Dynamics AX 2012](https://www.microsoft.com/downloads/details.aspx?familyid=6714f97a-17e2-42a0-9029-c224416d95d8%26amp%3bamp%3bdisplaylang=e%26displaylang=en) – The Monitoring Pack can be used to monitor your system. The Monitoring Pack can automatically discover the servers in your environment, monitor server availability, and find violations of setup best practices.

  - [Intelligent Data Management Framework for Microsoft Dynamics AX](microsoft-dynamics-ax-intelligent-data-management-framework-idmf.md) –Intelligent Data Management Framework (IDMF) provides functionality that resembles the functionality of DynamicsPerf, and also includes a user interface. IDMF also provides tools for activities that are related to data management, such as archiving and purging.

  - [Microsoft Visual Studio Profiling Tools](https://msdn.microsoft.com/library/bb385770.aspx) – The Visual Studio Profiling Tools help you identify performance issues in source code and compare the performance of possible solutions. For more information, see the following resources:
    
      - [Find Application Bottlenecks with Visual Studio Profiler](https://msdn.microsoft.com//magazine/cc337887.aspx)
    
      - [Beginners Guide to Performance Profiling](https://msdn.microsoft.com/library/ms182372.aspx)

## See also

[Plan for performance optimization and testing](plan-for-performance-optimization-and-testing.md)

  


