---
title: Commerce Data Exchange
TOCTitle: Commerce Data Exchange
ms:assetid: 33ee0ecd-24f7-4b8a-8f01-c76c5f9710e0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn741440(v=AX.60)
ms:contentKeyID: 62219718
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Commerce Data Exchange 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Commerce Data Exchange is a system that transfers data between Microsoft Dynamics AX and retail channels, such as online stores or brick-and-mortar stores.

The database that stores data for a retail channel is separate from the Microsoft Dynamics AX database. A channel database holds only the data that is required for retail transactions. For a brick-and-mortar store, the channel database is also known as a store database and is typically located on the premises.

Master data is configured in Microsoft Dynamics AX and is distributed to channels. Transactional data is created in the point of sale (POS) system or the online store, and is then uploaded to Microsoft Dynamics AX. Data distribution is asynchronous. In other words, the process of gathering and packaging data at the source occurs separately from the process of receiving and applying data at the destination.

For some scenarios, such as price and inventory lookups, data must be retrieved in real time. To support these scenarios, Commerce Data Exchange also includes a service that enables real-time communication between Microsoft Dynamics AX and a channel.

The following table describes the components of Commerce Data Exchange.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Component</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Commerce Data Exchange: Async Server (Microsoft Dynamics AX 2012 R3 only)</p></td>
<td><p>Async Server handles asynchronous data exchange at headquarters. Microsoft SQL Server change tracking on tables is used to determine which data must be packaged and sent to channels. Based on a distribution schedule, data packages are generated from Microsoft Dynamics AX and deposited in a working folder.</p>
<p>For more information, see <a href="commerce-data-exchange-async-server.md">Commerce Data Exchange: Async Server</a>.</p></td>
</tr>
<tr class="even">
<td><p>Commerce Data Exchange: Async Client (AX 2012 R3 only)</p></td>
<td><p>Async Client handles asynchronous data exchange for a channel. Data transfer is initiated by the client. At a configurable interval, Async Client polls for data to download. If there is new data, Async Client takes the data from the working folder and applies it to the local channel database.</p>
<p>Async Client also uploads sales transactions from the channel to Microsoft Dynamics AX.</p>
<p>For more information, see <a href="commerce-data-exchange-async-client.md">Commerce Data Exchange: Async Client</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Commerce Data Exchange: Real-time Service</p></td>
<td><p>Real-time Service provides real-time data exchange between a channel and Microsoft Dynamics AX.</p>
<p>For more information, see <a href="commerce-data-exchange-real-time-service.md">Commerce Data Exchange: Real-time Service</a>.</p></td>
</tr>
<tr class="even">
<td><p>Commerce Data Exchange: Synch Service (Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 Feature Pack)</p></td>
<td><p>Synch Service handles asynchronous data exchange at headquarters and at the channel. Based on a distribution schedule, data is packaged and sent to channels.</p>
<p>If you’re using AX 2012 R3, Synch Service is used only in an environment where you have to support previous POS versions during an upgrade (N-1).</p>
<p>If you’re using AX 2012 R2 or AX 2012 Feature Pack, see <a href="commerce-data-exchange-synch-service.md">Commerce Data Exchange: Synch Service</a> for more information.</p></td>
</tr>
</tbody>
</table>


## Asynchronous data exchange

The following illustration shows an overview of asynchronous data flow through Commerce Data Exchange.

![Overview of Commerce Data Exchange data flow](images/Dn741440.CDXOverview(en-us,AX.60).gif "Overview of Commerce Data Exchange data flow")

## Real-time data lookup

The following illustration shows an overview of real-time data lookup through Commerce Data Exchange.

![Flow of Real-time Service in R3](images/JJ679919.Retail_Real-timeService_R3(en-us,AX.60).gif "Flow of Real-time Service in R3")

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

