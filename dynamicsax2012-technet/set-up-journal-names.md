---
title: Set up journal names
TOCTitle: Set up journal names
ms:assetid: 63ee9215-d1c0-4226-9340-87319b8ce1cd
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa571140(v=AX.60)
ms:contentKeyID: 36057702
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up journal names 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To use fixed assets, you must set up the journal names that are the basis of the fixed asset journals. To use items from inventory as fixed assets, you must also set up journal names for the inventory to fixed asset journals.

## Set up journal names for the fixed asset journals

1.  Click **General ledger** \> **Setup** \> **Journals** \> **Journal names**.

2.  Click **New** and enter a unique identifier in the **Name** field.

3.  Select **Post fixed assets** in the **Journal type** field. You use this journal type for any type of fixed asset transactions that will be posted for value models. This journal type provides special functionality for fixed assets, such as creating proposals for different types of fixed asset transactions.

4.  Enter values in the **Description** and **Voucher series** fields and other fields, as required.

5.  Be sure to set up a journal name for each posting layer to post fixed asset transactions to.

6.  Click **New** to create another journal name and enter a unique identifier in the **Name** field.

7.  Select **Fixed asset budget** in the **Journal type** field. This journal type has functionality similar to **Post fixed assets**, but is used only for fixed asset budget register entries.

8.  Enter values in the **Description** and **Voucher series** fields and other fields, as required.

9.  Be sure to set up a journal name for each posting layer to post fixed asset budget register entries to.

## Set up journal names for the inventory to fixed assets journals

Setting up fixed asset journals is not a mandatory step in the setup of fixed assets. However, journal names must be set up to create fixed assets from inventory items.

1.  Click **Inventory management** \> **Setup** \> **Journals** \> **Journal names, inventory**.

2.  Click **New** and enter a unique identifier in the **Name** field.

3.  Select **Fixed assets** in the **Journal type** field, and enter values in the **Description** and **Voucher series** fields and other fields, as required.

4.  Click **Fixed assets** \> **Journals** \> **Fixed assets**.

5.  Select a default inventory journal in the **Inventory journal** field.

  


