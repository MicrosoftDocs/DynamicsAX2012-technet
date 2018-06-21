---
title: Monitoring services and AIF
TOCTitle: Monitoring services and AIF
ms:assetid: 21393afe-4277-4347-954a-15d097ed61c1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa834342(v=AX.60)
ms:contentKeyID: 35132575
ms.date: 11/07/2012
mtps_version: v=AX.60
f1_keywords:
- schema
- see
- XML
- view
- AIF
- AifXmlViewer
---

# Monitoring services and AIF [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

After you set up data exchanges with external systems by using Application Integration Framework (AIF), you must maintain this integration. Microsoft Dynamics AX lets you manage your document exchanges throughout their life cycle and troubleshoot any issues that affect data transfers. The maintenance and management of document exchanges involves the following tasks:

  - Monitor traffic and view the document history as documents pass through the framework.

  - Clear and review messages in the queues for adapter-based exchanges.

  - View the exception logs when problems occur.

  - Modify and resubmit messages that contain formatting errors.

  - Stop and start the batch services when necessary.

## Document history

For both exchanges that are based both on adapters and exchanges that are based on Web services, information about messages and document history is organized by service operation for each port. You set the parameters for logging this information when you configure troubleshooting options for the port.

You can view the logged information in the **History** form. Click **System administration** \> **Periodic** \> **Services and Application Integration Framework** \> **History**.

For more information, see [View the document history](view-the-document-history.md), [View the document log](view-the-document-log.md), and "AIF History (form)" in Microsoft Dynamics AX Help.

## Queue manager

For adapter-based exchanges, you can use the batch functionality in Microsoft Dynamics AX to start and stop the four services that move messages into and out of the document processing queues. After documents are exchanged, you can monitor the activity of documents in the queues. You can also modify and resubmit documents that have errors by using the **Queue manager** form. Click **System administration** \> **Periodic** \> **Services and Application Integration Framework** \> **Queue manager**.

For more information, see [Edit and resubmit messages in the AIF gateway queue](edit-and-resubmit-messages-in-the-aif-gateway-queue.md).

## Exceptions

To view information about AIF errors that occur, open the **Exceptions** form. Click **System administration** \> **Periodic** \> **Services and Application Integration Framework** \> **Exceptions**. The **Exceptions** form contains information about the module and subsystem where the error occurred, a description of the error, the time when the error was logged, the user who is associated with the error, and the form or business logic where the error occurred.

For more information, see [View the exceptions log](view-the-exceptions-log.md).

## Starting and stopping the batch job services

For adapter-based exchanges, you use the batch job functionality in Microsoft Dynamics AX to start and stop the following four AIF services: **AIFOutboundProcessingService**, **AIFInboundProcessingService**, **GatewaySendService**, and **GatewayReceiveService**. These services move messages into and out of the document processing queues. You may have to start and stop these services to troubleshoot issues or to change the settings for batch jobs, such as the recurrence. For more information, see [Configuring batch jobs and tasks for AIF](configuring-batch-jobs-and-tasks-for-aif.md).

