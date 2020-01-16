---
title: (RUS) About the bailment process
TOCTitle: (RUS) About the bailment process
ms:assetid: e03737bf-0af4-4c71-9c80-ebce6bc7b99e
ms:mtpsurl: https://technet.microsoft.com/library/JJ733293(v=AX.60)
ms:contentKeyID: 49685260
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) About the bailment process 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The bailment process involves the transfer of items from a bailor (owner of items) to a bailee (holder of items) for storage purposes.The bailment process includes the following tasks:

1.  Registering an agreement for bailment – A bailor and a bailee sign an agreement that includes details such as the account numbers of the bailor and the bailee, the price of the items for storage, the length of the storage period, and the number of free storage days that are allowed for the bailor.

2.  Transferring items for storage – The bailor transfers the items for storage, ships a transfer order, and generates a Bill of lading (1-T) and an Issue slip (M-15).

3.  Receiving items for storage – The bailee receive the items for storage, creates a purchase order, and generates the Acceptance report in storage (MX-1).

4.  Tracking items in storage – The bailee generates a Counting list (INV-5) report to track the items in storage.

5.  Returning items from storage – The bailee creates a sales order for the item storage and generates the Return report from storage (MX-3). The bailee calculates the cost of storage, and then the sales order with a service of goods storage is created.

6.  Receiving items from storage – The bailor receives the items from storage and creates a transfer order.

Complete the following tasks to initiate the bailment process:

  - Set up currency and exchange rates. For more information, see [Currency exchange rates (form)](https://technet.microsoft.com/library/hh209477\(v=ax.60\)).

  - Create a vendor account or a customer account. The customer and the vendor must be the same organization, and they must belong to the same party. For more information, see [Create a vendor account](create-a-vendor-account.md), [Vendors (form)](https://technet.microsoft.com/library/aa592162\(v=ax.60\)), and [Customers (form)](https://technet.microsoft.com/library/aa590606\(v=ax.60\)).

  - Create a purchase agreement, and then generate an intra-company sales agreement.
    
    –or–

  - Create a sales agreement, and then generate an intra-company purchase agreement.

  - Create an item, and assign an item dimension group to the item. You must also create a tracking dimension group to enable the batch, inventory profile, and owner dimensions. For more information, see [(RUS) Set up tracking dimensions for an inventory owner](rus-set-up-tracking-dimensions-for-an-inventory-owner.md).

  - Create a warehouse to store the items. For more information, see [Create warehouses](create-warehouses.md), [Set up warehouses for transfer orders](set-up-warehouses-for-transfer-orders.md), and [Warehouses (form)](https://technet.microsoft.com/library/aa620570\(v=ax.60\)).

  - Create a ledger account for bailment. For more information, see [Maintain ledger accounts](maintain-ledger-accounts.md) and [Chart of accounts (form)](https://technet.microsoft.com/library/aa618234\(v=ax.60\)).

  - Set up an inventory posting profile for bailment. For more information, see [(RUS) Set up an inventory posting profile](rus-set-up-an-inventory-posting-profile.md).

## See also

[(RUS) Set up an inventory owner for bailment](rus-set-up-an-inventory-owner-for-bailment.md)

  


