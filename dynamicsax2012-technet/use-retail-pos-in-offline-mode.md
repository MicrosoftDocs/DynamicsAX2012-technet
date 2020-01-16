---
title: Use Retail POS in offline mode
TOCTitle: Use Retail POS in offline mode
ms:assetid: d5306558-f78c-4592-8956-33f81d485005
ms:mtpsurl: https://technet.microsoft.com/library/Dn720297(v=AX.60)
ms:contentKeyID: 62221436
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Use Retail POS in offline mode 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

A POS device will go offline if the system is temporarily down or if the channel database is unavailable. When the connection with the channel database is lost, Retail POS automatically switches to the offline database.


> [!NOTE]
> <P>If a transaction is in progress when the connection is lost, you must void the transaction, and then start a new transaction that uses the offline database.</P>



This topic contains the following sections:

  - POS operations that can be completed when the channel database is offline

  - POS operations that can’t be completed when the channel database is offline

  - Reconnect to the channel database

## POS operations that can be completed when the channel database is offline

If a POS device has an offline database, you can complete the following operations when the channel database is offline:

  - Generate a sales transaction

  - Recall an unfinished transaction, if the transaction was initiated during the current offline session

  - Void an item

  - Void a payment

  - Void a transaction, if the transaction was initiated during the current offline session

  - Blank operations

  - Complete a return transaction, under specific circumstances. The following table shows when an offline return transaction can be completed.
    
    <table>
    <colgroup>
    <col style="width: 33%" />
    <col style="width: 33%" />
    <col style="width: 33%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Mode of database when the original transaction was generated</p></th>
    <th><p>Current mode of database</p></th>
    <th><p>Return allowed</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Offline</p></td>
    <td><p>Offline</p></td>
    <td><p>Yes, if the original transaction was completed during the current offline session</p></td>
    </tr>
    <tr class="even">
    <td><p>Offline</p></td>
    <td><p>Online</p></td>
    <td><p>Yes</p></td>
    </tr>
    <tr class="odd">
    <td><p>Online</p></td>
    <td><p>Offline</p></td>
    <td><p>No</p></td>
    </tr>
    <tr class="even">
    <td><p>Online</p></td>
    <td><p>Online</p></td>
    <td><p>Yes</p></td>
    </tr>
    </tbody>
    </table>


## POS operations that can’t be completed when the channel database is offline

You can’t complete the following operations when the channel database is offline:

  - Print an X report

  - Print a Z report

  - Close a shift

  - Blind-close a shift

  - View blind-closed shifts

  - Suspend a shift

## Reconnect to the channel database

When the channel database becomes available again, you must use the **Database connection status** operation in Retail POS to reestablish the connection with the channel database. Offline POS devices do not automatically reconnect to the channel database when it becomes available.

  


