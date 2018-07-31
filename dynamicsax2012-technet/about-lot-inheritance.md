---
title: About lot inheritance
TOCTitle: About lot inheritance
ms:assetid: 638df47d-a194-40c1-9aba-d91274b3a5aa
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ838738(v=AX.60)
ms:contentKeyID: 50120621
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About lot inheritance 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can configure an item to update its batch attributes and shelf life information from the ingredients of the formula that is used to produce the finished item.

For shelf life information, you can set up shelf life items as ingredients in the formula that you specify, so that the inventory batch with the earliest shelf life dates is inherited by the finished item. For product characteristics, you can set up items and ingredients with batch attributes, and then select which batch attributes of which ingredient are inherited by the finished item.

You can also select co-products as ingredients and then update the batch attributes or shelf life information from the co-products to the finished item.

You can perform the following tasks for lot inheritance:

  - Set up an item as a shelf life item. For more information, see [Set up an item as a shelf life item](set-up-an-item-as-a-shelf-life-item.md).

  - Select ingredients that are used to update the shelf life information for finished items. For more information, see [Define formula ingredients for shelf life inheritance](define-formula-ingredients-for-shelf-life-inheritance.md).

  - Create batch attributes and add them to an item. For more information, see [Create a batch attribute](create-a-batch-attribute.md), [Add a batch attribute to an item](add-a-batch-attribute-to-an-item.md), and [Add a batch attribute group to an item](add-a-batch-attribute-group-to-an-item.md).

  - Select ingredients that are used to update the product characteristic or batch attribute information for finished items. You can select batch attributes from each ingredient to update batch attribute information to the finished items. For more information, see [Define and activate formula ingredients for batch attribute inheritance](define-and-activate-formula-ingredients-for-batch-attribute-inheritance.md).

After you define shelf life ingredients and define and activate batch attributes in the formula ingredients for a finished item, you can create batch orders and process the finished item and any related co-products. After you run the report as finished process, the calculated shelf life dates (the best-before date and the expiration date) and the active batch attributes are updated in the inventory batches of the finished item and any related co-products.

## See also

[(PM) Released product details (form)](https://technet.microsoft.com/en-us/library/hh352306\(v=ax.60\))

[Tracking dimension groups (form)](https://technet.microsoft.com/en-us/library/hh209465\(v=ax.60\))

[(PM) Item model groups (form)](https://technet.microsoft.com/en-us/library/hh328695\(v=ax.60\))

[Formula line (form)](https://technet.microsoft.com/en-us/library/hh352331\(v=ax.60\))

[(PM) Batch attribute selection (form)](https://technet.microsoft.com/en-us/library/jj838761\(v=ax.60\))

  


