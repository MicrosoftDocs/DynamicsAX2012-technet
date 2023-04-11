---
title: Create a batch order
TOCTitle: Create a batch order
ms:assetid: 66b9cb50-5ea9-40a9-b14f-72dfc8d4a8b0
ms:mtpsurl: https://technet.microsoft.com/library/Hh352208(v=AX.60)
ms:contentKeyID: 36687842
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create a batch order 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to create a batch order. Each item that you select for production is associated with a formula version and a route. The route is a sequence of operations that produce the finished product. If the item that you select has been approved and activated, and is in a valid date interval, the correct formula and route versions are displayed in the **Formula number** and **Route number** fields. These versions are based on the default quantity for the batch order.

1.  Click **Production control** \> **Common** \> **Production orders** \> **All production orders**.

2.  On the **Action Pane**, on the **Production order** tab, in the **New** group, click **Batch order**.

3.  In the **Item number** field, select the item to produce. The default values that were previously defined for the item are displayed in applicable fields.
    

    > [!NOTE]
    > <P>If you select a batch-controlled item for production, the <STRONG>Create batch</STRONG> form dynamically displays the inventory dimension fields that must be completed.</P>



4.  Optionally, enter any remaining information or change the default values as necessary for the particular production.

5.  To add details for the route that must be associated to the batch order, click **Route** to open the **Route** form and add the information.

6.  To add more lines to the batch order, click **Formula** to open the **Formula line** form and add the necessary lines. Close the **Formula line** form.

7.  In the **Create batch** form, click **Create** to add the new batch order. The **All production orders** list page is redisplayed with the batch order appearing in the list.

## See also

[About batch orders](about-batch-orders.md)

[Create batch (form)](https://technet.microsoft.com/library/hh328644\(v=ax.60\))

[Formula line (form)](https://technet.microsoft.com/library/hh352331\(v=ax.60\))

[Route (form)](https://technet.microsoft.com/library/aa550121\(v=ax.60\))

  


