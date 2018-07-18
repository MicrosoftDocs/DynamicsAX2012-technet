---
title: Maintain records
TOCTitle: Maintain records
ms:assetid: bd3112dd-a214-4837-bac6-c7492a2abed4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg213610(v=AX.60)
ms:contentKeyID: 43894515
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- record
- records
audience: Application User
ms.search.region: Global
---

# Maintain records 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

There are several ways to create and delete records in forms.

## Create a record

Open the form to create a new record in and do one of the following.

  - Click **File**\> **New**.

  - Press CTRL+N.

  - Click the **New** button at the top of the form.

## Delete a record

  - Click **Command** \> **Delete Record**.

  - Press ALT+F9.

  - Click the **Delete Record** button at the top of the form.

## Records that have date effective information

Many business scenarios require tracking object history over its lifetime. For example, a bank provides a certificate of deposit with a rate that is effective for a certain time period, student records in a university, employee data in company, and other complex business information. In previous versions of Microsoft Dynamics AX, various forms of implementing date effectiveness were implemented within specific application modules, such as Human resources, Procurement and sourcing, and across the finance modules. Microsoft Dynamics AX 2012 offers the date effective functionality at the kernel to provide the ease, consistency, and scalable behavior of application code for date effective scenarios.

When information that is associated with records is date effective, it means that you can modify that information in a record and then specify when those modifications to the record are effective. For example, consider a position record. Currently, Antonio is assigned as the worker for a position, but you know that Antonio will be leaving the company in two weeks. When Antonio leaves the company, Lori will be taking over his position. Because you know this information now, you can update the worker assignment for the position to indicate a future change to the record.

## See also

[Date Effective Patterns (White paper)](date-effective-patterns-white-paper.md)

  


