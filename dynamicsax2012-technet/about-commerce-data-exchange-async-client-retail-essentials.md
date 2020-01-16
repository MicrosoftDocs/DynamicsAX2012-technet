---
title: 'About Commerce Data Exchange: Async Client (Retail essentials)'
TOCTitle: 'About Commerce Data Exchange: Async Client (Retail essentials)'
ms:assetid: c8385b73-cd4e-4da6-82cd-548e1acedb97
ms:mtpsurl: https://technet.microsoft.com/library/Dn736951(v=AX.60)
ms:contentKeyID: 62200427
ms.date: 04/22/2015
mtps_version: v=AX.60
f1_keywords:
- c8385b73-cd4e-4da6-82cd-548e1acedb97
- MsDynAx060.c8385b73-cd4e-4da6-82cd-548e1acedb97
---

# About Commerce Data Exchange: Async Client (Retail essentials) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Commerce Data Exchange: Async Client is part of the system for asynchronous data exchange between Microsoft Dynamics AX and retail stores. Async Client is installed at the store and communicates with the store database.

## The Async Client service

Async Client runs as a Windows service. At a configurable interval, Async Client checks with Commerce Data Exchange: Async Server to see whether new data packages are available. If there is new data, Async Client takes the data from the working folder and applies that data to the local store database. Async Client also uploads sales transactions from the channel to Microsoft Dynamics AX.

By default, Async Client uses the WS-ReliableMessaging protocol to transfer data. Reliable messaging helps guarantee that the data is transferred successfully over the network. However, the confirmation actions that are sent between the source and the destination can cause data transfers to be slower.

For better throughput, you can use streaming instead. Streaming is ideal for initial high-speed data synchronization and ongoing synchronization of large amounts of data. However, streaming does not handle network issues. If you have a reliable network and high data volume, we recommend that you stream data. For information about how to set up streaming, see [Configure settings for Async Client](configure-settings-for-async-client.md).

## The Async Client message database

Async Client uses a message database to store status information for data transfers that are in progress or have been completed.

## See also

[Commerce Data Exchange: Async Server](commerce-data-exchange-async-server.md)

[Install Commerce Data Exchange: Async Client](install-commerce-data-exchange-async-client.md)

[Configure settings for Async Client](configure-settings-for-async-client.md)

[Commerce Data Exchange](commerce-data-exchange.md)

  


