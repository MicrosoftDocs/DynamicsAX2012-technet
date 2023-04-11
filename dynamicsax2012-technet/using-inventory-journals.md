---
title: Using inventory journals
TOCTitle: Using inventory journals
ms:assetid: 775dc1c5-4c89-45cf-968c-6a92dded4016
ms:mtpsurl: https://technet.microsoft.com/library/Aa550043(v=AX.60)
ms:contentKeyID: 44080995
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Using inventory journals 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic applies to features in the **Inventory management** module. It does not apply to features in the [Warehouse management](warehouse-management.md) module.

To open a journal, click **Inventory management** \> **Journals**, and then click a journal type. The following types of inventory journal are available:

  - **Movement**

  - **Inventory adjustment**

  - **Transfer**

  - **Bills of materials**

  - **Item arrival**

  - **Production input**

  - **Counting**

  - **Tag counting**

In the journal form, on the **Overview** tab, you can select to view all journals, open journals, or posted journals. In the **Show** field, click **All**, **Open**, or **Posted**.

## Creating journals

Create journals by clicking **New** in the journal form. The journal names that you can select in the **Name** field in the journal forms are created in the **Journal names, inventory** form. In the **Inventory and warehouse management parameters** form, in the **Journals** area, you can select the default journal name that appears in the **Name** field for each type of inventory journal.

## Working with journals

Click **Lines** in the journal forms to create journal lines.


> [!NOTE]
> <P>A journal can be accessed by only one user at a time. If several users must access the journals at the same time to create journal lines, the users must select journals that are not currently being used to prevent overwriting.</P>



It can be useful to divide journals so that each posting routine is entered in its own unique inventory journal. For posting routines that are associated with inventory transactions, create one journal for periodic inventory adjustments and another for inventory counting.

You can use inventory journals in various parts of Microsoft Dynamics AX. For example, when you report a bill of materials (BOM) as finished, you can create a BOM journal. By using a BOM journal, you can post the BOM directly.

## Posting journal lines

You can post the journal lines that you create at any time. Data that you enter in a journal remains in the journal even if you close the journal without posting the lines.

  


