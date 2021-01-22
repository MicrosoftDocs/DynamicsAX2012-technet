---
title: Concurrency When Updating Data
TOCTitle: Concurrency When Updating Data
ms:assetid: d55d6f64-87d2-4ca9-929a-ce26127027ab
ms:mtpsurl: https://technet.microsoft.com/library/Cc639058(v=AX.60)
ms:contentKeyID: 35252031
author: Khairunj
ms.author: daxcpft
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Concurrency When Updating Data 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how you can implement concurrency when updating data in Microsoft Dynamics AX using Application Integration Framework (AIF). Concurrency is the ability for multiple processes to access or change shared data at the same time. The greater the number of concurrent processes that can execute without blocking each other, the greater the concurrency of the database system.

When you update data in Microsoft Dynamics AX using AIF, you can handle concurrency in one of two ways:

  - By using the document hash

  - By using the RecId and RecVersion fields for each record in the update

Regardless of which method you use, you must first read the data, modify it, and then send it back to update the database.

## Document Hash

When you read data, AIF returns a document hash field. This field contains a hash of all the RecId and RecVersion values for each record that is returned. When you send the data back into AIF to update a record, it recalculates the document hash from the database records in the update and compares it to the document hash in the inbound message. If the data has changed, for example, if a record was updated or added, the calculated document hash will differ from the document hash in the inbound document and AIF will return an error.

When you use the document hash, you only have to read and submit one field for comparison instead of reading and submitting the RecId and RecVersion values for each record. However, if a concurrency error occurs when you use the document hash, AIF can only report that a record was changed and not which record changed.

## RecId and RecVersion

If the inbound message contains the RecId and RecVersion field values for each record, AIF will check those values against the values in the database table before data is updated. If the RecId and RecVersion in the inbound message differ from the values in the table, a concurrency error is returned. When you use the RecId and RecVersion fields for concurrency and an error occurs, the error will specify the table and record in which the data has changed.

If the inbound update message does not have a document hash value and you do not pass in the RecId and RecVersion for each record, the update will fail. If the inbound update message contains both a document hash and the RecId and RecVersion for each record, both forms of concurrency checking will be performed.

## See also

[Updating Data With AIF](updating-data-with-aif.md)

[Walkthrough: Updating Data with AIF (Full Update)](walkthrough-updating-data-with-aif-full-update.md)

