---
title: 'Commerce Data Exchange: Async Server'
TOCTitle: 'Commerce Data Exchange: Async Server'
ms:assetid: 8f802c2f-37bc-4a5c-805e-bece3640245f
ms:mtpsurl: https://technet.microsoft.com/library/Dn741449(v=AX.60)
ms:contentKeyID: 62219726
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Commerce Data Exchange: Async Server 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Commerce Data Exchange: Async Server is part of the system for asynchronous data exchange between Microsoft Dynamics AX and retail channels. Async Server is installed at headquarters and communicates with Microsoft Dynamics AX. You can distribute the communication load at the head office by installing multiple instances of Async Server.

## The Async Server service

Async Server runs as a Windows Communication Foundation (WCF) service on IIS.

Microsoft SQL Server change tracking on the Microsoft Dynamics AX database is used to determine the data changes that must be sent to channels. Based on a distribution schedule, Async Server packages that data and saves it to a file location. Commerce Data Exchange: Async Client periodically checks for new data packages, picks up the data packages, and applies them at the channel. For more information about Async Client, see [Commerce Data Exchange: Async Client](commerce-data-exchange-async-client.md).

## Async Server message databases

Async Server uses a message database to store status information for data transfers that are in progress or have been completed. Async Client contacts the message database to determine if there are new data packages to pick up.

You can also transfer status messages from the message database to the Microsoft Dynamics AX database so they can be viewed in Microsoft Dynamics AX. For information about how to transfer and view status messages, see [Process status messages for data exchange](process-status-messages-for-data-exchange.md) and [View or cancel retail data distribution sessions](view-or-cancel-retail-data-distribution-sessions.md).

Each instance of Async Server can refer to only one message database. However, a message database can have multiple instances of Async Server referring to it. There can be only one message database per partition in Microsoft Dynamics AX. The following illustration shows the relationships between partitions, message databases, and instances of Async Server.

![How Async Server works with partitions](images/Dn741449.AsyncServerPartitions(en-us,AX.60).gif "How Async Server works with partitions")

## See also

[Install Commerce Data Exchange: Async Server](install-commerce-data-exchange-async-server.md)

[Commerce Data Exchange](commerce-data-exchange.md)

  


