---
title: Insert a Route node
TOCTitle: Insert a Route node
ms:assetid: f4e6c1fd-d93c-49b6-907c-feec179d8a9f
ms:mtpsurl: https://technet.microsoft.com/library/Aa551643(v=AX.60)
ms:contentKeyID: 36059996
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Insert a Route node 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Route node is useful for adding individual route operations to a product model. If you want to add a complete route from the **Routes** form, you should use a Route node, instead.


> [!NOTE]
> <P>This information applies only to Product builder.</P>



1.  Click **Product information management** \> **Common** \> **Product builder** \> **Product models**.

2.  Double click a product model.

3.  Select the **Tree** tab in the lower pane.

4.  Right-click the **Modeling tree** node.

5.  Click **New** and select **Route node**. A new node is added to the bottom of the modeling tree. If you want to insert a node into a particular position in the tree, drag it from the node list displayed on the left.

6.  The form which opens contains the same fields as a standard route operation in the **Routes** form plus two extra fields that control how values are assigned to each data field on the route operation. Select one or the other:
    
      - **Value** - You can type a fixed value into the route operation field. The fixed value could be a numeric value or some other type of data, depending on which field you are in.
    
      - **Variable** - You can type the name of one of the product model’s variables into the route operation field. During item configuration, this field will then be completed with the value of the selected variable.

7.  Complete the remainder of the fields on the **Routes** form. For their descriptions, see the [Create and update routes (form)](https://technet.microsoft.com/library/aa590442\(v=ax.60\)).

## See also

[Product models (form)](https://technet.microsoft.com/library/aa572853\(v=ax.60\))

  


