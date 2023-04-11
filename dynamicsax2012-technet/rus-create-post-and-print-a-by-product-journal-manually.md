---
title: (RUS) Create, post, and print a by-product journal manually
TOCTitle: (RUS) Create, post, and print a by-product journal manually
ms:assetid: f65551ec-f085-43cf-abb2-7409edf02382
ms:mtpsurl: https://technet.microsoft.com/library/JJ678627(v=AX.60)
ms:contentKeyID: 49388109
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Create, post, and print a by-product journal manually 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can manually create a by-product journal by using the **By-product** form. A by-product journal is created when items that are returned to the warehouse after they have been rejected from production. These items can include defective products, process losses, reusable items, missing items, or low-quality products. You create a by-product journal manually when you must reconcile the difference in quantity between inventory transactions and route transactions.

1.  Click **Production control** \> **Journals** \> **By-product**.

2.  Press CTRL+N to create a line in a by-product journal line.

3.  In the **Name** field, select the by-product journal.

4.  Click **Lines** to open the **By-product journal lines** form.

5.  In the **Production** field, select the production order.

6.  In the **Kind of by-product** field, select the type of by-product.

7.  In the **Item number** field, select the defective item or by-product.

8.  In the **Unit quantity** field, enter the quantity of the defective item or by-product.

9.  In the **Oper. No.** field, select the operation number of the production order route that the defective item or by-product was received from.

10. Click the **Product dimensions** tab, and then, in the **Warehouse** field, enter the name of the warehouse for the defective item.

11. Click **Validate**, and then click **OK** to validate the journal.

12. Click **Post**, and then click **OK** to post and print the journal.

## See also

[(RUS) By-product (form)](https://technet.microsoft.com/library/jj711526\(v=ax.60\))

[(RUS) By-product journal lines (form)](https://technet.microsoft.com/library/jj711637\(v=ax.60\))

  


