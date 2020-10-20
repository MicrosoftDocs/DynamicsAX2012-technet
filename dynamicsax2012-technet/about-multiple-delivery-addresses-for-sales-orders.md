---
title: About multiple delivery addresses for sales orders
TOCTitle: About multiple delivery addresses for sales orders
ms:assetid: ac81a468-0a90-4524-84b3-84cfa2e5260f
ms:mtpsurl: https://technet.microsoft.com/library/Aa498559(v=AX.60)
ms:contentKeyID: 36058916
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About multiple delivery addresses for sales orders 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

By using multiple delivery addresses, you can specify a different delivery address for each order line. When the lines are posted, a journal that lists the relevant order lines is produced for each delivery address.

The **Summary update** tab of the **Accounts receivable parameters** form contains check boxes that you can use to select multiple delivery addresses for the following documents:

  - **Confirmation**

  - **Picking list**

  - **Packing slip**

  - **Invoice**

If you clear one of the check boxes, when the item is posted, the delivery address that is specified on the **Sales order header** tab of the **Sales order** form is used. This address is either the customer address or an alternative address that you can specify by clicking **Other address** on the **Sales order header** tab.

If you select one of the check boxes, the delivery address used is the one that is specified for each sales order line. By default, this is the customer address, unless you have chosen an alternative address by clicking the **Sales order header** tab, and then clicking **Other address** in the **Sales order** form. Items are produced for each delivery address. The relevant sales order lines are listed on each item.

  


