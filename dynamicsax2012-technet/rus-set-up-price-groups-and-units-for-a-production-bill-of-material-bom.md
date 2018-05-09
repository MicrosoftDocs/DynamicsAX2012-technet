---
title: (RUS) Set up price groups and units for a production bill of material (BOM)
TOCTitle: (RUS) Set up price groups and units for a production bill of material (BOM)
ms:assetid: 4d212b16-73c2-4560-9aea-a3aff0ba27fe
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ665364(v=AX.60)
ms:contentKeyID: 49387453
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Set up price groups and units for a production bill of material (BOM) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the following procedures to define parameters that are used to calculate cargo prices or amounts on a transportation invoice or a job ticket. For more information, see [(RUS) About transportation invoices and job tickets that are based on bills of lading](rus-about-transportation-invoices-and-job-tickets-that-are-based-on-bills-of-lading.md).

## Set up a price group for a production order

Use the **Production orders** form to set up the price group and currency for a production order. For more information, see [Production orders (form)](https://technet.microsoft.com/en-us/library/aa617966\(v=ax.60\)).

1.  Click **Production control** \> **Common** \> **Production orders** \> **All production orders**.

2.  Create a production order. For more information, see [Create production orders manually](create-production-orders-manually.md).

3.  Click the **Setup** FastTab.

4.  In the **Price group** field, select the price group that is created for goods that are delivered to customers. For more information, see [Create price groups](create-price-groups.md).

5.  In the **Currency** field, select the currency that is used to define the prices for the goods.

## Set up a unit price for a production BOM

Use the **BOM** form to set up the unit price for a production bill of materials (BOM). For more information, see [Production BOM (form)](https://technet.microsoft.com/en-us/library/aa556713\(v=ax.60\)).

1.  Click **Production control** \> **Common** \> **Production orders** \> **All production orders**.

2.  On the **Action Pane**, in the **Production details** group, click **BOM**.

3.  Create a production BOM.

4.  In the **Item number** field, select the item that the production order is created for.

5.  Click the **Setup** tab.

6.  In the **Unit price** field, enter the price for the unit.

7.  In the **Price unit** field, enter the quantity of materials in the unit.

8.  In the **Amount** field, enter the amount for the production BOM line.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

