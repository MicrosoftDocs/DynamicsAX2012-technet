---
title: Batch server overview
TOCTitle: Batch server overview
ms:assetid: 0ce6ebff-7781-41ed-9a61-199d9638f487
ms:mtpsurl: https://technet.microsoft.com/library/Dd309586(v=AX.60)
ms:contentKeyID: 35132538
author: tonyafehr
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Batch server overview 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes batch processing and batch servers, and how to plan for their use.

The batch framework provides an asynchronous, server-based batch processing environment that can process tasks across multiple Application Object Server (AOS) instances. There is no need for an interactive client for server-side batches. Client-side batch jobs are supported, but are required only for end-user-defined batch tasks. A job can contain both client-side and server-side batch tasks. A job that has client-side tasks requires a Microsoft Dynamics AX client to be open in order to process the client-side tasks.

You should become familiar with the following aspects of the batch framework:

  - A batch job is a process that is used to achieve a specific goal. A batch job consists of one or more batch tasks.

  - A batch task is an activity that is run by a batch job. You can add batch tasks that have multiple types of dependencies to a batch job. You can also configure AOS servers to run multiple threads, with each thread executing a task. All batch tasks that are waiting for execution can be executed by any available AOS server that is configured as a batch server. You can choose to define a batch job as many tasks, and then use a batch server to execute the tasks against all available AOS instances to improve throughput and reduce overall execution time.

  - A batch group is an attribute of a batch task that allows the administrator to determine which AOS runs the task. When you create a new task, it is put in the default batch group. All batch servers are configured to process the default batch group and to process waiting tasks from any job. You can create a named batch group and set an affinity between the batch group and specific AOS servers. When you have created this affinity, only the configured AOS servers will process tasks from the named batch group only. You can also add the default batch group to the configured servers, if it is required.

## Batch server topology planning

You can configure any active AOS server as a batch server. To create a dedicated batch server that does not act as an active AOS server, you must put the batch server in a cluster separate from the active AOS server. You must also make sure that users are not connecting to this dedicated batch server.


> [!NOTE]
> <P>A dedicated load balancer cannot be configured as a batch server.</P>



The capacity of a batch server is determined based on the maximum number of threads that can run on the AOS server concurrently. Each thread executes one batch task. You can add complex dependencies between or among tasks. You can run these tasks in a serial steps or parallel steps, depending on the business logic and requirements. All tasks that do not have any dependencies are considered parallel tasks. AOS servers that are configured as batch servers periodically check for tasks that are waiting for processing. The batch server assigns each parallel task to a thread and starts to process the thread.

You can run multiple threads across multiple AOS servers. Each AOS automatically runs multiple threads, depending on capacity that is defined in the configuration settings. Therefore, parallel tasks from a job can execute on multiple threads across multiple AOS servers.

A batch server checks for available threads once a minute. Therefore, you might have to wait for a minute before you can see a waiting task being picked up for processing by an available thread.

## Batch server management planning

All batch servers can be managed from a single location.

One common use of batch servers is to load balance jobs across multiple time zones and servers. You can define the time period during which an AOS acts as a batch server. You can also set the number of threads that the batch server will process during the time period. The applicable time is based on the user's time zone and not on the time zone of the location of the AOS server. The time period is configured based on a schedule of start time and end time.

Because batch servers are also active AOS servers that service requests from Microsoft Dynamics AX clients and other Microsoft Dynamics AX components, determine carefully when an AOS is available to process batches.

For example, a batch server might be set to process only two batch threads from 8:00 to 6 pm in the time zone that it is located in. But from 6 pm to 7:30 am, it could be set to process 20 threads.

## Walkthroughs

The following walkthroughs describe how tasks are processed, and how batch groups can be used to associate batch jobs with batch servers.

## Batch processing of dependent tasks

Consider that you have created a job that is called JOB 1. As shown in the following diagram, the job has seven tasks: TASK 1, TASK 2, TASK 3, TASK 4, TASK 5, TASK 6, and TASK 7.

![Batch\_Framework\_Programmability](images/Dd309586.Batch_Framework_Programmability(AX.60).gif "Batch_Framework_Programmability")

The dependencies of your tasks are as follows:

  - TASK 1 is the first task.

  - TASK 2 runs on completion of TASK 1 (regardless of the success or failure of TASK 1).

  - TASK 3 runs on success of TASK 2.

  - TASK 4 runs on success of TASK 2.

  - TASK 5 runs on failure of TASK 2.

  - TASK 6 runs on failure of TASK 3.

  - TASK 7 runs on success of both TASK 3 and TASK 4.

Let us assume that two batch servers, Batch1 and Batch2, are configured with a capacity of one thread each. Batch1 checks for waiting tasks, assigns TASK 1 to its thread, and starts execution. Although Batch2 is also available with one thread, TASK 2 will keep waiting until TASK 1 is completed successfully.

As soon as TASK 1 is completed successfully, TASK 2 is ready for execution. Let us assume this time that Batch2 checks for waiting tasks, assigns TASK 2 to its thread, and starts execution of TASK 2. If TASK 2 is successful, TASK 3 and TASK 4 are awaiting execution. Let us assume that Batch2 checks for waiting tasks, assigns TASK 3 to its thread, and starts execution. Batch1 also checks for waiting tasks, assigns TASK 4 to its thread, and starts execution. If TASK 3 and TASK 4 are completed successfully, one of the batch servers will execute TASK 7.

If TASK 2 fails, one of the batch servers will execute TASK 5. If TASK 3 fails, one of the available batch servers will execute TASK 6.


> [!NOTE]
> <P>Note that we are using Batch1 and Batch2 to explain the concept. Any batch server that has available threads will start executing a waiting task. You must create a batch group to determine or specify which batch job runs on which server.</P>



## Batch processing with batch groups

The following describes how batch jobs can be processed on specific batch servers:

1.  You have configured three batch servers: AOS1, AOS2, and AOS3.
    
    By default, all of the batch servers process tasks from all batch jobs, depending on the number of available threads.

2.  You now create a named batch group, BG1, and configure it to run on AOS2 and AOS3. Tasks from jobs in BG1 will run only on AOS2 and AOS3, depending on the number available threads. AOS1 will not process tasks from jobs in BG1. Likewise, AOS2 and AOS3 will process tasks from only BG1.
    
    You can configure AOS2 and AOS3 to process tasks from other batch groups. This includes the default batch group.

## See also

[Configure an AOS instance as a batch server](configure-an-aos-instance-as-a-batch-server.md)

  


