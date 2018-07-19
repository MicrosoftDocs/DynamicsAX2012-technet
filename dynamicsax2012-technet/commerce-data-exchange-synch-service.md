---
title: 'Commerce Data Exchange: Synch Service'
TOCTitle: 'Commerce Data Exchange: Synch Service'
ms:assetid: 4828043f-2f9f-4d72-92a3-bee83388d0d9
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ973039(v=AX.60)
ms:contentKeyID: 51649177
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Commerce Data Exchange: Synch Service 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Commerce Data Exchange: Synch Service is the integrated service that periodically replicates data between the Microsoft Dynamics AX database and store databases.


> [!NOTE]
> <P>Synch Service is required for Retail only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 Feature Pack. In Microsoft Dynamics AX 2012 R3, this component is used only to support previous versions of Retail POS while you upgrade (N-1).</P>



Synch Service runs as a Microsoft Windows service, DBServer.exe, that listens for incoming requests or packages. If the service receives a read instruction, it connects to the source database, reads data, and stores the data in a data package file.

Synch Service aggregates data into the fewest possible packages and multicasts those packages. In this manner, Synch Service can update multiple recipients with information such as price changes, but can also minimize network load. All data transfer requests, such as requests to send data to a store or upload point of sale (POS) sales transactions, are initiated by Retail Scheduler. Synch Service supplies the data transfer mechanism.

A package can contain data from more than one database table. After the requested data has been read, the next step depends on the configuration of your organization’s Synch Service instances.

  - In a typical configuration, as described in [Deployment topologies for Retail](deployment-topologies-for-retail.md), Synch Service at the head office takes data from Microsoft Dynamics AX, creates a data package, and sends the package to the store. Synch Service at the store then inserts the data into the appropriate database table.

  - In a forwarder configuration, as described in [Run multiple instances of Synch Service](run-multiple-instances-of-synch-service.md), data packages are cached in the database and working directory. The forwarder picks up the cached data packages and transmits them to their destinations. Use a forwarder configuration for load balancing. This configuration can achieve better performance and scalability.

You can also distribute the communication load at the head office by running multiple instances of Synch Service at the head office. For more information about this configuration option, see [Run multiple instances of Synch Service](run-multiple-instances-of-synch-service.md).

## Components of Synch Service

The following table lists the components that comprise Synch Service.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Subcomponent name</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Synch Service Settings wizard</p></td>
<td><p>The Synch Service Settings wizard, DBServerUtil.exe, is the configuration utility for Synch Service.</p>
<p>For more information, see <a href="configure-settings-for-synch-service.md">Configure settings for Synch Service</a>.</p></td>
</tr>
<tr class="even">
<td><p>Synch Service Pack Viewer</p></td>
<td><p>The Synch Service Pack Viewer, DDPackView.exe, is used to inspect the data that is included in the packages that Synch Service sends and receives.</p>
<p>For more information, see <a href="synch-service-pack-viewer.md">Synch Service Pack Viewer</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Transaction Automation Client</p></td>
<td><p>The Transaction Automation Client, TransAutomClient.dll, is a .NET assembly that manages communication between Microsoft Dynamics AX and the Synch Service service.</p>
<p>TransAutomClient.dll is a prerequisite for Retail. Therefore, Synch Service must be installed for each instance of Application Object Server (AOS) and on each client computer where you use Retail, even if you do not intend to use those particular instances of Synch Service.</p></td>
</tr>
</tbody>
</table>

  


