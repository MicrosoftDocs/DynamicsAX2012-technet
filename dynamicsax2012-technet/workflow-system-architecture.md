---
title: Workflow system architecture
TOCTitle: Workflow system architecture
ms:assetid: 36794bf3-0d67-4221-8fa1-d6e8549f79e3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dd309641(v=AX.60)
ms:contentKeyID: 35132602
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Workflow system architecture 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The workflow infrastructure consists of two components that are hosted on Application Object Server (AOS): the X++ workflow runtime and the managed workflow runtime.

The X++ workflow runtime consists of:

  - Workflow runtime API

  - A messaging batch job

  - A message queue

The messaging batch job or the workflow runtime API can invoke the application code, if it is required. The X++ workflow runtime is compiled into the Common Intermediate Language (CIL) of the .NET Framework. For more information, see [X++ Compiled to .NET CIL](https://technet.microsoft.com/en-us/library/gg839855\(v=ax.60\)).

The managed workflow runtime consists of the Windows Workflow Foundation and Microsoft Dynamics AX extensions.

Logically, the workflow infrastructure is an extension of Microsoft Dynamics AX and is transparent to users. Physically, both the X++ workflow and the managed workflow runtimes are hosted on AOS. The workflow infrastructure uses batch processing on the AOS and .NET Interop to integrate both subsystems and to pass messages from one subsystem to another. The X++ code that is executed in the batch processor is compiled to .NET CIL. The batch processing runs in the .NET common language runtime (CLR).

The following figure illustrates the high-level architecture of the workflow infrastructure.

![Workflow architecture](images/Dd309641.Workflow_ArchitectureDiagram(AX.60).gif "Workflow architecture")

Users can use the workflow forms and controls in the Microsoft Dynamics AX client and in Enterprise Portal for Microsoft Dynamics AX to participate in business processes.

Developers can create workflows for objects that they have added to Microsoft Dynamics AX. For more information, see [Implementing Workflow for Microsoft Dynamics AX](https://technet.microsoft.com/en-us/library/cc585061\(v=ax.60\)).

The following table describes the workflow steps that occur when a user submits an expense report to the workflow system for approval.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Step</p></th>
<th><p>Runtime</p></th>
<th><p>Activity</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>1</p></td>
<td><p>X++ workflow runtime</p></td>
<td><p>A user submits an expense report by clicking the <strong>Submit</strong> button on one of the workflow controls. This causes X++ code to activate a workflow instance by calling the workflow runtime API. The workflow runtime API posts a message to the message queue. The messaging batch job reads the message and sends a workflow activation request to the managed workflow runtime.</p>
<div class="alert">

> [!NOTE]
> <P>The messaging batch job processes the message queue at one-minute intervals.</P>


</div></td>
</tr>
<tr class="even">
<td><p>2</p></td>
<td><p>Managed workflow runtime</p></td>
<td><p>.NET Interop from X++ receives the message and starts a new workflow instance via Windows Workflow Foundation. This workflow instance performs a callback to the X++ workflow runtime API via .NET Interop to X++ CIL and posts a message that the workflow has started.</p>
<p>After posting the message, the managed workflow runtime saves the idle workflow instance to the Microsoft Dynamics AX database. Runtime then removes it from memory. When the managed workflow runtime receives another message from the X++ workflow runtime for this workflow instance, it restores the workflow instance to memory and resumes it.</p>
<p>Each workflow instance is unique. If you have two users who submit their expense reports for approval, two workflow instances are started.</p></td>
</tr>
<tr class="odd">
<td><p>3</p></td>
<td><p>X++ workflow runtime</p></td>
<td><p>The messaging batch job reads the <em>workflow started</em> message from the message queue and invokes the application event handler to process a <em>workflow started</em> event. The batch job then posts an acknowledgment message that the event was processed.</p></td>
</tr>
<tr class="even">
<td><p>4</p></td>
<td><p>Both</p></td>
<td><p>This same messaging pattern is repeated, as necessary, throughout the life cycle of the workflow instance.</p></td>
</tr>
</tbody>
</table>


The workflow architecture helps to provide a reliable and durable messaging system and helps to ensure that the state of the workflow is always synchronized with the state of the application. In the event of an unexpected hardware or software failure, the workflow instance state is returned to its last known saved point and the message stays in the queue. Therefore, from an architecture perspective, the recovery model is to fix the problem and resume the workflow.

  


