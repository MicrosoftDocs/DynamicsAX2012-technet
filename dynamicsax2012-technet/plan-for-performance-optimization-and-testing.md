---
title: Plan for performance optimization and testing
TOCTitle: Plan for performance optimization and testing
ms:assetid: 23349355-77a5-4790-80e6-ccaf54cf3bf4
ms:mtpsurl: https://technet.microsoft.com/library/JJ149696(v=AX.60)
ms:contentKeyID: 47541245
author: tonyafehr
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Plan for performance optimization and testing 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic provides an overview of performance optimization and testing for Microsoft Dynamics AX. The topic also describes the testing that we recommend that you perform both before and after go-live.

## Performance optimization and testing cycle

The following diagram illustrates typical cycles for performance optimization and testing.

![Performance optomization and testing process](images/JJ149696.PerformanceOptimization(AX.60).png "Performance optomization and testing process")

## Performance monitoring and tuning before go-live

The following list describes some of the goals of testing and monitoring performance before go-live:

  - Ensure good performance of your core business processes before you move to a production environment.

  - Find and optimize expensive code patterns.

  - Find missing indexes and configurations.

  - Find slow elements of the UI, and slow queries.

## Preparation

Identify all your core scenarios. Many times, you can find 5 to 10 processes that are essential for your business. If you find other processes that are essential, such as reports, add them to the list for performance testing.

Examples of core scenarios might include the creation and processing of sales orders, production orders, and transfer orders.

## Testing

Define how to test your scenarios. There are three primary methods for testing performance before go-live:

  - **Tracing** – You can use either Trace Parser or the Microsoft Visual Studio Profiling Tools to get an overview of the performance of your processes. You must use the Visual Studio Profiling Tools if X++ code traverses into Microsoft Compiled Intermediate Language (CIL). For example, you must use the Visual Studio Profiling Tools if you use the RunAs() command, run a batch process, or work with services. By repeatedly tracing your core processes, you can find up to 90 percent of all performance issues in your pre-production system.

  - **User acceptance tests** – Projects usually have multiple user acceptance tests. During these tests, you can use DynamicsPerf to find bottlenecks. You can also monitor the system by using Performance Monitor. Interviews with users can also help you find bottlenecks.

  - **Benchmarks** – You can use the Benchmark SDK toolkit for Microsoft Dynamics AX to simulate the behavior of your system under a load. For more information, see [Performance Benchmark Software Development Toolkit (SDK) for Microsoft Dynamics AX 2012](performance-benchmark-software-development-toolkit-sdk-for-microsoft-dynamics-ax-2012.md).

## Performance monitoring and tuning after go-live

The following list describes some of the goals of performance testing and monitoring after go-live:

  - During the first few weeks after you go into production, monitor performance closely to ensure that everything runs as you expect.

  - As time passes, and the amount of data increases, monitor performance to ensure that everything continues to run as you expect. Larger amounts of data may cause Microsoft SQL Server to use different execution plans. Additionally, code that previously had fast performance, such as while loops, may become slower, because the code must iterate through more data.

## Preparation

Plan to trace all your important business processes to double-check that there are no obvious problems.

Plan a test in which as many users as possible execute their regular work. Then analyze the results by using DynamicsPerf.

Test the efficiency of your infrastructure. If you have offshore offices, check the latency between those offices and the data center.

Double-check that all your systems are set up and configured according to best practices.

## At go-live and during the first few weeks

Monitor your system closely for any potential performance problems by using Performance Monitor or the Monitoring Pack.

If you find problems, collect DynamicsPerf snapshots daily.

## Monitoring in production

We recommend that you use the following monitoring tools in the production environment:

  - Performance Monitor

  - The System Center Operations Manager Monitoring Pack for Microsoft Dynamics AX 2012

Both before and after go-live, performance tuning is an iterative process. For example, if you identify a slow process at any point, you can trace and optimize the process by using either the Visual Studio Profiling Tools or Trace Parser.

## Regular maintenance activities in production that affect performance

The following list describes some of the maintenance activities that we recommend that you perform regularly in your production environment:

  - **Defragment indexes** – You can defragment indexes from either SQL Server Management Studio or the Intelligent Data Management Framework (IDMF).

  - **Update SQL Server statistics from SQL Server Management Studio** – We recommend that you run both manual and automatic updates of statistics. Manual updates may become more important as the size of your database increases, because automatic updates are less likely to be completed on large data sets.

  - **Reduce the size of the database** – You can use IDMF to keep the size of the production database small. A small database makes database operations more efficient. For example, you can delete or archive data that is not required in your production system.

## Conclusion

Good performance requires good and continuous monitoring. If you find problematic processes early, you can optimize them without significantly affecting your end users. Remember that performance tuning is an iterative process. Often, you must complete more than one round of tuning to achieve the maximum improvement in performance.

## See also

[Microsoft Dynamics AX Performance Team Blog](https://blogs.msdn.com/axperf)

[InformationSource](http://informationsource.dynamics.com/)

[Plan for data](plan-for-data.md)

  


