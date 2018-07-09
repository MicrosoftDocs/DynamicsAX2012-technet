---
title: About releasing production orders
TOCTitle: About releasing production orders
ms:assetid: d5b408fa-3586-43d8-9c49-bc8ce5e38192
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa499380(v=AX.60)
ms:contentKeyID: 37832537
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# About releasing production orders [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you release a production order, it leaves the office where it is estimated and scheduled, and is released to the shop floor. The production order status changes to **Released**. At this point, you can take the following actions:

  - Print route cards, route jobs, and job cards.

  - Start the pre-production setup and machine changeover without starting the production process.

  - Stop a production if you have to.


> [!NOTE]
> <P>Route jobs and job cards cannot be printed if the job scheduling process is incomplete.</P>



## Route cards

A route card provides an overview of information that comes from route and operation setups, and from operation and job scheduling methods. A route card specifies the following information:

  - Routes used

  - Operations involved, including their names and numbers

  - Operations resources

  - Quantities

  - Setup and process times

  - Start dates and times

  - End dates and times

## Route jobs

A route job lists each job of an operation in detail, and includes setup, process, queue, and transportation times. For example, an operation, such as painting, may require individual jobs, such as setup, run time for the painting process, and queue time for drying.

## Job cards

A job card lists the individual job numbers of a particular operation. One job appears on each page. The jobs that are included on a job card, and their estimated times, come from the route and operation setup information. From the job card, you can open the **Production journal lines, job card** form. The people who run operations resources can provide feedback on the production process. There are fields where you can enter consumption statistics and information such as the error quantity.

## See also

[Production - Release (class form)](https://technet.microsoft.com/en-us/library/aa500134\(v=ax.60\))

[Production orders (form)](https://technet.microsoft.com/en-us/library/aa617966\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

