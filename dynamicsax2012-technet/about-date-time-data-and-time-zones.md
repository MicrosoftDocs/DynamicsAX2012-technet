---
title: About date/time data and time zones
TOCTitle: About date/time data and time zones
ms:assetid: 117fdb0b-03aa-4a97-ba84-953451830d38
ms:mtpsurl: https://technet.microsoft.com/library/Gg230928(v=AX.60)
ms:contentKeyID: 36056032
author: tonyafehr
ms.author: daxcpft
ms.date: 06/10/2016
mtps_version: v=AX.60
f1_keywords:
- UTC
- time zones
- date/time data
audience: Application User
ms.search.region: Global
---

# About date/time data and time zones 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

There are three types of date and time fields in Microsoft Dynamics AX. They correspond to different data types in the database:

  - Combined date/time fields – The preferred method of entering date and time data in Microsoft Dynamics AX. The **datetime** data type stores time and date data in a single field in Coordinated Universal Time (UTC). UTC is the standard time zone that is common to every location in the world, and it is coordinated by the International Bureau of Weights and Measures. It is also known as Greenwich Mean Time. The **datetime** data type is associated with a time zone.

  - Date fields – Used to enter dates only. The **date** data type stores a day, month, and year. However, these values are not stored in UTC and cannot be associated with a time zone.

  - Time fields – Used to display the number of seconds that have elapsed since midnight for the current date. The **timeofDay** data type stores an integer value. Time values are not stored in UTC.

## Time zones

To express UTC times in the local time, you must set a time zone. The time zone controls the offset from UTC that is the equivalent of the local time. For example, the offset for Moscow is UTC+3.

Your preferred time zone is first set according to the Windows locale of your computer, although it might have been changed by an administrator. Your preferred time zone is used only when displaying combined dates and times.

For more information, see [Set a preferred time zone](set-a-preferred-time-zone.md).

  


