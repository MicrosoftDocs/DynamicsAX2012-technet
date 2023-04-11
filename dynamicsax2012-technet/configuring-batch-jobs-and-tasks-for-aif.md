---
title: Configuring batch jobs and tasks for AIF
TOCTitle: Configuring batch jobs and tasks for AIF
ms:assetid: eec47dcc-29c1-4c0e-acac-970649dc597d
ms:mtpsurl: https://technet.microsoft.com/library/Hh352328(v=AX.60)
ms:contentKeyID: 36687958
author: tonyafehr
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Configuring batch jobs and tasks for AIF 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Application Integration Framework (AIF) uses its gateway queue to handle asynchronous message routing in an orderly way. To move message into and out of the gateway queue, AIF requires a Microsoft Dynamics AX batch job that runs a particular set of services. For detailed information about how batch jobs work on Application Object Servers (AOS), see [Process batch jobs and tasks](process-batch-jobs-and-tasks.md).

## AIF batch services

The four services that move documents through the gateway queue are:

1.  **AIFGatewayReceiveService** – This service communicates with the adapters, receives messages from their external source locations, and puts them into the gateway queue to wait for processing.

2.  **AIFInboundProcessingService** – This service takes incoming messages from the gateway queue and then processes the documents according to the rules that are specified by the inbound port.

3.  **AIFOutboundProcessingService** – This service processes an outbound document according to the rules that are specified by the integration port and then adds the envelope XML code to create a fully-formed AIF message. The service then places the message into the gateway queue to send.

4.  **AIFGatewaySendService** – This service sends the messages to the correct external destinations.

These services must run in a specific order because they depend on each other. For example, the gateway receive service must run before the inbound processing service. Otherwise, the inbound processing service will have no data to process. The order in which these services must run is the order in the previous list.

## Running batch jobs

Typically, these services run as four tasks in one batch job. You can create other batch job configurations, depending on your business requirements. For example, to schedule the AIF services to run at different time intervals, you can divide the services among multiple batch jobs. When you create the batch job, you can specify the order in which the services run by specifying conditions for the tasks. For information about how to create a batch job, including how to set conditions, see [Create a batch job](create-a-batch-job.md).

In order for the AIF services to run, you must set the batch job status to **Waiting**. For information about how to change the status of batch jobs, see [View or change batch job status](view-or-change-batch-job-status.md).

## See also

[Services and AIF operations](services-and-aif-operations.md)

