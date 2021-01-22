---
title: 'Commerce Data Exchange: Async Client'
TOCTitle: 'Commerce Data Exchange: Async Client'
ms:assetid: 2cbf6c94-b940-4b0b-888a-559fa57dbabf
ms:mtpsurl: https://technet.microsoft.com/library/Dn741439(v=AX.60)
ms:contentKeyID: 62219723
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Commerce Data Exchange: Async Client 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Commerce Data Exchange: Async Client is part of the system for asynchronous data exchange between Microsoft Dynamics AX and retail channels. Async Client is installed at the channel, and communicates with the channel database. Typically, you will install one instance of Async Client for each channel.

## The Async Client service

Async Client runs as a Windows service. At a configurable interval, Async Client checks with Async Server to see whether new data packages are available. If there is new data, Async Client takes the data from the working folder and applies it to the local channel database. Async Client also uploads sales transactions from the channel to Microsoft Dynamics AX.

By default, Async Client uses the WS-ReliableMessaging protocol to transfer data. Reliable messaging ensures that the data is transferred successfully over the network. However, the confirmation actions that are sent between the source and the destination can cause data transfers to be slower. For better throughput, you can use streaming instead. However, streaming does not handle network problems. Streaming is ideal for initial high-speed data synchronization or for ongoing synchronization of large amounts of data. If you have a reliable network and high data volume, we recommend that you stream data. For information about how to set up streaming, see [Configure settings for Async Client](configure-settings-for-async-client.md).

## The Async Client message database

Async Client uses a message database to store status information for data transfers that are in progress or have been completed.

## See also

[Commerce Data Exchange: Async Server](commerce-data-exchange-async-server.md)

[Install Commerce Data Exchange: Async Client](install-commerce-data-exchange-async-client.md)

[Configure settings for Async Client](configure-settings-for-async-client.md)

[Commerce Data Exchange](commerce-data-exchange.md)

  


