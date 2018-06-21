---
title: Sequential and parallel processing in services and AIF
TOCTitle: Sequential and parallel processing in services and AIF
ms:assetid: 19ebee1c-5152-4e25-af8b-6aefd8f4c7d0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh500186(v=AX.60)
ms:contentKeyID: 37820253
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Sequential and parallel processing in services and AIF [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you use asynchronous adapters, performance can be affected by the rate at which messages move through the gateway queue for Application Integration Framework (AIF). In asynchronous scenarios, messages are periodically retrieved from file folders or Message Queuing queues. These messages include batched messages. The frequency at which messages are retrieved and then processed is determined by the recurrence setting of a batch job.

## Sequential processing

Typically, messages that are processed by asynchronous adapters are processed in alphabetical order by file name during each occurrence of a batch job. This type of processing is called sequential processing. You can control the order in which messages are processed by using sequential file names. For example, you can prefix each file name with a numerical value, such as 001\_, 002\_, and so on. Provided that you send all the files at the same time, the files are guaranteed to be processed in the order that you specify. However, the order in which files are sequentially processed applies only during a single occurrence of a batch job.

## Parallel processing

To improve the performance of message processing when you use asynchronous adapters, AIF supports parallel processing. Parallel processing distributes the processing of messages across one or more instances of Application Object Server (AOS). For a single AOS instance, parallel processing uses multiple threads to process messages. If the computer that is running a single AOS has multiple processors, you can expect better performance by using parallel processing. You can further improve the performance of message processing by using parallel processing with multiple AOS instances. For more information about how to load balance the processing of messages, see [Configuring network load balancing for services](configuring-network-load-balancing-for-services.md).

To enable parallel processing of inbound messages, select the **Process requests in parallel** check box on the **Processing options** FastTab of the **Inbound ports** form. Clear the check box to use sequential processing. This check box affects both single and batched message types.

By default, when you enable parallel processing, the number of messages that AOS can process in parallel is set to 1000. The MaximumInboundParallelMessages macro defines the number of inbound messages that are processed in parallel. You can change this setting by changing the corresponding AIF macro in the Application Object Tree (AOT). You must have a developer license to access the AOT. The following macro is defined in the Aif subnode.

    #define.MaximumInboundParallelMessages      (1000)

To enable parallel processing of outbound messages, you must modify the code that calls the AIF Send API. For more information, see [Walkthrough: Deploying the Document Service in an Outbound Exchange](walkthrough-deploying-the-document-service-in-an-outbound-exchange.md).

## Conversations

Sometimes, the order in which messages are processed is important. For example, new customer accounts must be created before sales orders for the customers can be processed. You can specify that certain messages must be processed sequentially by an integration port, even when parallel processing is enabled for that port. In each document that must be processed in parallel, include a special XML element that is named ConversationId. All messages that have the same conversation ID are processed sequentially by any port for which parallel processing is enabled. The ConversationId element has no effect when messages are processed by ports for which parallel processing is not enabled. For more information about the ConversationId element, see [Message Header](message-header.md).

## Summary

The following table summarizes processing behavior.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Message type</p></th>
<th><p>Parallel processing is enabled</p></th>
<th><p>Parallel processing is disabled</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Single message</p></td>
<td><p>Message processing is distributed across one or more AOS instances. The order of processing is not deterministic.</p></td>
<td><p>Messages are processed by a single AOS instance, in alphabetical order by file name, during each occurrence of the batch job.</p></td>
</tr>
<tr class="even">
<td><p>Batched messages</p></td>
<td><p>Batched messages are separated into single messages. Message processing is then distributed across one or more AOS instances. The order of processing is not deterministic.</p></td>
<td><p>Batched messages are separated into single messages. Messages are then processed by a single AOS instance, in alphabetical order by file name, during each occurrence of the batch job.</p></td>
</tr>
<tr class="odd">
<td><p>Conversations</p></td>
<td><p>Single messages that have the same conversation ID are processed by the same AOS instance, in alphabetical order by file name, during each occurrence of the batch job.</p></td>
<td><p>The ConversationId element is ignored.</p></td>
</tr>
</tbody>
</table>


## See also

[Configure processing options](configure-processing-options.md)

[Key concepts in AIF](key-concepts-in-aif.md)

[Processing batched messages in AIF](processing-batched-messages-in-aif.md)

[Configuring batch jobs and tasks for AIF](configuring-batch-jobs-and-tasks-for-aif.md)

