---
title: Set processor affinity
TOCTitle: Set processor affinity
ms:assetid: 2931af93-352a-43c7-9e9b-67d8f6ed7201
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dd309629(v=AX.60)
ms:contentKeyID: 35949275
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Set processor affinity 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If an instance of Application Object Server (AOS) has multiple processors, you can specify which processors host the AOS service. When you specify one or more processors for a service, you are said to set processor affinity. By setting processor affinity, you can help improve server performance.

1.  Open the server configuration utility. Click **Start** \> **Administrative Tools** \> **Microsoft Dynamics AX 2012 Server Configuration**.

2.  Click **Manage** \> **Create configuration**.

3.  Enter a name, select where you want to copy the configuration from, and then click **OK**.

4.  Click the **Performance** tab.

5.  In the **Processor Affinity** section, select **Custom**, and then select the processors that you want to host the AOS service.

6.  Click **OK**.

## See also

[Manage AOS performance and availability](manage-aos-performance-and-availability.md)

[Manage load balancing](manage-load-balancing.md)

  


