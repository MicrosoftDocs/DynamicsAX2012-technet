---
title: Create a rework batch order
TOCTitle: Create a rework batch order
ms:assetid: c539adb6-d9da-433b-a6c4-7844b8f0d2d8
ms:mtpsurl: https://technet.microsoft.com/library/Hh352346(v=AX.60)
ms:contentKeyID: 36687977
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create a rework batch order 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to create a rework batch order. You can create a rework batch order for any finished formula item. There should be sufficient on-hand inventory (including any catch weight inventory) to fill the order. You must manually reserve this inventory before you run estimation.

1.  Click **Production control** \> **Common** \> **Production orders** \> **All production orders**.

2.  On the **Action Pane**, on the **Production order** tab, in the **New** group, click **Batch order**.

3.  In the **Item number** field, select the item to be produced. The default values previously defined for the item are displayed.
    

    > [!NOTE]
    > <P>If you select a batch-controlled item for production, the <STRONG>Create batch</STRONG> form dynamically displays the Inventory dimension fields that you must complete.</P>



4.  Select the **Rework batch** check box.

5.  Optionally, enter any remaining information or modify default values as necessary for the particular production.

6.  To add or modify details for the route to be associated with the rework batch order, click **Route** and add the information in the **Route** form.

7.  To add lines to the rework batch order, click **Formula**, add or modify lines in the **Formula line** form, and close the form.
    

    > [!TIP]
    > <P>You cannot select a co-product, by-product, or containerized item for a material input.</P>



8.  In the **Create batch** form, click **Create**. The **All production orders** list page is displayed with the rework batch order in the list.

9.  Double-click the new rework batch order to open the **Batch order** form. The batch order should contain one material line that includes the same formula item and quantity as the original order. Add other material lines to complete the rework batch order.

## See also

[About batch orders](about-batch-orders.md)

[Create batch (form)](https://technet.microsoft.com/library/hh328644\(v=ax.60\))

[Formula line (form)](https://technet.microsoft.com/library/hh352331\(v=ax.60\))

[Route (form)](https://technet.microsoft.com/library/aa550121\(v=ax.60\))

  


