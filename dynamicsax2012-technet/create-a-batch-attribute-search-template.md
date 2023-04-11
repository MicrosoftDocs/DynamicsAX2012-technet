---
title: Create a batch attribute search template
TOCTitle: Create a batch attribute search template
ms:assetid: 2b635c41-c8e8-4ca2-9fc8-09610adc7d73
ms:mtpsurl: https://technet.microsoft.com/library/Hh208507(v=AX.60)
ms:contentKeyID: 36056245
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create a batch attribute search template 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to create a search template for batch attributes. This feature is used to locate items with certain characteristics to reserve the inventory against a sales order or a production order.


> [!NOTE]
> <P>This procedure uses the <STRONG>Released products list page</STRONG> to move to the <STRONG>Batch attributes search</STRONG> form. You can also access this form from the <STRONG>Batch reservation</STRONG> form.</P>



1.  Click **Product information management** \> **Common** \> **Released products**.

2.  Select an item that has been assigned a batch attribute.

3.  On the **Action Pane**, on the **Manage inventory** tab, in the **Batch attributes** group, click **Search inventory**.

4.  Click **Batch attribute search**. The **Batch attribute search** form is displayed.

5.  Enter CTRL+N to add a new line.

6.  In the **Attribute** field, select the attribute value to search on.

7.  Select or enter the search criterion in the following fields:
    
      - **Operator**: In the first **Operator** field, select the value that identifies the search parameter. If you want to search on a range, in the second **Operator** field enter the ending search parameter. For more information about operator search parameters, see [About operator search parameters for batch attributes](about-operator-search-parameters-for-batch-attributes.md).
    
      - **Minimum**: Enter the minimum value in the attribute range.
    
      - **Maximum**: Enter the maximum value in the attribute range.

8.  Click **Save template**. A template dialog box is displayed.

9.  In the **Template** field, enter an identifier for the new template.

10. In the **Description** field, optionally enter a description for the template.

11. Click **OK**.

## See also

[About batch attributes](about-batch-attributes.md)

[Batch attribute search (form)](https://technet.microsoft.com/library/hh242819\(v=ax.60\))

[Batch reservation (form)](https://technet.microsoft.com/library/hh208645\(v=ax.60\))

  


