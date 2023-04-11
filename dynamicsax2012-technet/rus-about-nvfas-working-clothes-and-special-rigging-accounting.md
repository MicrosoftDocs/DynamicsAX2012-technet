---
title: (RUS) About NVFAs, working clothes, and special rigging accounting
TOCTitle: (RUS) About NVFAs, working clothes, and special rigging accounting
ms:assetid: 153f7a97-f807-4a9f-a246-0b07efa43ab8
ms:mtpsurl: https://technet.microsoft.com/library/JJ853158(v=AX.60)
ms:contentKeyID: 50396438
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) About NVFAs, working clothes, and special rigging accounting 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

An organization must account for each working clothes item or special rigging asset that is issued to an employee, and create a Working clothes or Special rigging issue card. You can create queries to display all assets that are on-hand for employees and print the **Working clothes issue sheet (No. MB-7)**. You can cancel or return the Working clothes or Special rigging issue card to the warehouse, and calculate the net book value and residual wearing period.

Working clothes and special rigging assets are regulated by their useful life cycle. This period starts when the item is written off from a warehouse and issued to an employee, and ends after a stipulated period of use. The useful lifetime is specified in months for each item. All of the data that pertains to an item is linked. This includes the identity of the employee, the useful life of the item, the date when the item is issued to the employee, and the calculated end date based on the rating of the item. When the end of the useful life approaches, the item is written off, so that it is no longer assigned to the employee.

During their life cycle, the cost of these types of assets must be amortized. If the life cycle is longer than 12 months, which is the legally defined rate, the linear method of depreciation is used. If it is less than 12 months, the cost is written off when the item is issued to the employee.

The **Working clothes** and **Special rigging** forms are similar to the **Fixed assets** form, which accounts for all issued working clothes and special rigging.

You can also track and account for low-value, high-wear items that are used in the workplace as a special type of fixed asset. Not valuable fixed assets (NVFAs) are items with a cost that is less than the specified cost limit. The full cost of NVFAs should be written off for depreciation in the first month of use.

If the purchase price of a fixed asset is less than the value that is specified in the **Max cost of the NVFA** field in the **Fixed asset parameters** form, the item is considered to be an NVFA. You cannot specify a fixed asset inventory number for this item in the **Purchase order** form. You cannot register the NVFA directly in the **Not valuable FAs** form until the purchase order process is completed.

After you purchase and register the NVFAs, you can perform the following tasks:

  - Divide fixed assets and NVFAs by price when you post purchase orders.

  - Automate the placement of NVFAs into operation and into subsequent depreciation transactions.

  - Print the MB-2, MB-4, and MB-8 reports.

## See also

[(RUS) Generate the NVFA accounting card (No. MB-2) for NVFAs, special rigging, and working clothes](rus-generate-the-nvfa-accounting-card-no-mb-2-for-nvfas-special-rigging-and-working-clothes.md)

[(RUS) Generate the NVFA statement of disposal (No. MB-4) from the Working clothes, Special rigging, or Not valuable FAs forms](rus-generate-the-nvfa-statement-of-disposal-no-mb-4-from-the-working-clothes-special-rigging-or-not-valuable-fas-forms.md)

[(RUS) Generate the NVFA statement of writing-off (No. MB-8) from the Working clothes, Special rigging, or Not valuable FAs forms](rus-generate-the-nvfa-statement-of-writing-off-no-mb-8-from-the-working-clothes-special-rigging-or-not-valuable-fas-forms.md)

  


