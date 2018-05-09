---
title: Compress data between clients and an AOS
TOCTitle: Compress data between clients and an AOS
ms:assetid: 79e79814-4964-4d14-b944-f3310bc81dbc
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa569624(v=AX.60)
ms:contentKeyID: 35949319
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Compress data between clients and an AOS 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Either low bandwidth or high latency can cause slow response times on your network. If you have a slow network, you may want to increase the compression of the data that is sent between Microsoft Dynamics AX clients and servers.

A decrease in the size of data packets in each client/server request or response has the following benefits that can, in turn, greatly reduce transmission times:

  - Better use of limited bandwidth

  - Smaller chance of bit errors

  - Smaller chance of exceeding the TCP window size

The TCP window size is the amount, in bytes, of the data that is received that can be buffered at one time on a connection. After the sending host sends that amount of data, it must wait for an acknowledgement (ACK) and a window update from the receiving host.

If the size of each client/server request or response is less than the TCP window size, the sending host does not have to wait for an acknowledgement when the window size is exceeded. However, sometimes the sending host cannot avoid exceeding the TCP window size. In this case, it is important that you reduce, as much as you can, the number of TCP round trips that are required for each client/server request or response.

1.  Open the server configuration utility. Click **Start** \> **Control Panel** \> **Administrative Tools** \> **Microsoft Dynamics AX 2012 Server Configuration**.

2.  Verify that the instance of Application Object Server (AOS) and the configuration that you want to modify are selected.

3.  On the **Performance** tab, in the **Minimum packet size to compress (in KB)** field, select a packet size.
    
    Select the smallest packet size that is useful. The gains that you achieve in performance decrease as the packet size increases.

## See also

[Manage AOS performance and availability](manage-aos-performance-and-availability.md)

[Tune data access settings](tune-data-access-settings.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

