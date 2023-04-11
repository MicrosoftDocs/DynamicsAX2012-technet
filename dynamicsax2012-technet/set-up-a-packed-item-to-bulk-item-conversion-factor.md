---
title: Set up a packed item to bulk item conversion factor
TOCTitle: Set up a packed item to bulk item conversion factor
ms:assetid: 5e3ebd06-4922-4090-ae4e-a53589b8d09d
ms:mtpsurl: https://technet.microsoft.com/library/Hh352207(v=AX.60)
ms:contentKeyID: 36687841
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up a packed item to bulk item conversion factor 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to set up the conversion factor for converting a packed item to a related bulk item. You must create the packed and bulk items before you can set up the conversion factor for them.


> [!TIP]
> <P>The <STRONG>Factor</STRONG> that you enter in this procedure is a different factor than the one that you might enter in the standard <STRONG>Unit conversions</STRONG> form. You use the <STRONG>Bulk Item Conversion</STRONG> form to identify how much of the bulk item is contained within each of the packed items. For example, if you identify the bulk item in a unit of measure of GL and the packed item in a unit of measure of CS that contains six gallons of the bulk item, the <STRONG>Factor</STRONG> would be 6.</P>



1.  Click **Product information management** \> **Common** \> **Released products**.

2.  Select the packed product that you want to convert.

3.  On the **Action Pane**, on the **Manage inventory** tab, in the **Packaging** group, click **Bulk item conversion**.

4.  In the **Bulk item conversion** form, in the **Bulk item** field, select the identifier for the bulk product to use in the conversion.

5.  In the **Factor** field, enter any quantity to be added to the unit upon conversion.

6.  In the **Rounding** field, select the applicable rounding factor.


> [!TIP]
> <P>If you want to confirm that the conversion factors that you entered generate the results that you expect, use the <STRONG>Calculator for units</STRONG> button.</P>



## See also

[About consolidated batch orders](about-consolidated-batch-orders.md)

[Bulk item conversion (form)](https://technet.microsoft.com/library/hh209242\(v=ax.60\))

[Create a consolidated batch order](create-a-consolidated-batch-order.md)

[Firm a consolidated batch order](firm-a-consolidated-batch-order.md)

[Released products (list page)](https://technet.microsoft.com/library/hh597154\(v=ax.60\))

[Unit conversions (form)](https://technet.microsoft.com/library/hh209285\(v=ax.60\))

  


