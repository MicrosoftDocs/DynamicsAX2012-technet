---
title: About fixed asset determination rules
TOCTitle: About fixed asset determination rules
ms:assetid: 05380afd-8f66-4b8e-9f71-d39457a507b1
ms:mtpsurl: https://technet.microsoft.com/library/Hh242106(v=AX.60)
ms:contentKeyID: 36055949
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- qualifier
- asset determination rules
- Fixed asset
- fixed asset rule
audience: Application User
ms.search.region: Global
---

# About fixed asset determination rules 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the business rules for fixed asset determination to identify purchases that qualify as fixed assets. If you have been assigned the applicable role, you can set up rules to determine whether a product must be treated as a fixed asset when the purchase price of the product exceeds a monetary threshold. The monetary threshold for a legal entity can differ from the monetary threshold for the organization.

The fixed asset rules are displayed when the following conditions are true:

  - An employee selects a product from a procurement category on a purchase requisition.

  - The unit price of the selected product equals or exceeds the threshold amount for the category.

Create qualifier questions to help classify a purchase of a fixed asset into the appropriate fixed asset group. You can create qualifiers for the organization that differ from the qualifiers at the legal entity level. You can also translate qualifiers into another language for legal entities that use a language that differs from the language of the organization.

**Prerequisites**

  - Set up an active procurement category hierarchy. For more information about categories, see [Key tasks: Set up a category hierarchy](key-tasks-set-up-a-category-hierarchy.md).

  - Associate products that could potentially be classified as a fixed asset with a procurement category in the active procurement category hierarchy. For more information about procurement categories, see [Key tasks: Set up and maintain procurement category hierarchies](key-tasks-set-up-and-maintain-procurement-category-hierarchies.md).

  - Set up fixed asset groups for legal entities. For information about fixed asset groups, see [Set up fixed asset groups](set-up-fixed-asset-groups.md).

  - If the currency of a legal entity differs from the organization’s currency, you must create a currency conversion rate before you can associate a legal entity rule with an organization-wide fixed asset identifier. For more information about currency conversion rates, see the [Currency exchange rates (form)](https://technet.microsoft.com/library/hh209477\(v=ax.60\)).

## Example

This example assumes that the following conditions are set up:

  - Contoso is an organization located in the United States. The currency of the organization is USD.

  - Contoso’s only international legal entity, Fabrikam, is located in Germany. The currency of the legal entity is EUR.

  - The currency exchange rate for EUR to USD is set up.

  - A procurement category hierarchy is set up. The procurement category hierarchy has a child category named **Office furniture and equipment**.

  - There are two fixed asset groups set up for Fabrikam. One group is for office equipment and the other group is for office furniture. The difference is that office equipment requires power to operate, and office furniture does not require power.

### Create organization-wide fixed asset identifiers

1.  In the **Organization-wide fixed asset identifiers** form, create a fixed asset identifier named **GFurn** for office furniture for Contoso. Associate the Contoso identifier with Fabrikam’s fixed asset group for office furniture.

2.  Create another organization-wide fixed asset identifier named **GOffEq** for office equipment in Contoso and associate it with Fabrikam’s fixed asset group for office equipment.

### Create an organization-wide fixed asset rule

1.  In the **Business rules for fixed assets determination** form, create an organization-wide fixed asset rule for the **Office furniture and equipment** procurement category. The rule is that a product purchased from the **Office furniture and equipment** procurement category must be capitalized as a fixed asset for Contoso if the cost of the item is at least USD 1,000.

2.  On the **Organization-wide rule** FastTab, select the **Has qualifiers?** check box. Add a qualifier question: **Does this item require power to operate?** This qualifier is a field label that appears on the **Fixed assets** FastTab of a purchase requisition. You can optionally translate the qualifier into another language by clicking **Translations**.

3.  Click **Add**, and in the list, enter **Furniture – No power** in the **Name** field, and then enter **No** in the **Description** field. In the **Fixed asset group** field, select the Contoso fixed asset identifier **GFurn** for office furniture.

4.  In the next row, in the **Name** field, enter **Office equip – Power**, and then enter **Yes** in the **Description** field. In the same row, in the **Fixed asset group** field, select the Contoso fixed asset identifier **GOffEq** for office equipment.

A Contoso employee requests an item from the **Office furniture and equipment** category on a purchase requisition. The unit price of the item exceeds the USD 1,000 monetary threshold. The employee must respond to the organization-wide qualifier question on the **Fixed assets** FastTab of the purchase requisition before the employee can submit the purchase requisition for approval. If the employee selects **Yes**, the item is classified into Contoso’s office equipment fixed asset group. If the employee selects **No**, the item is classified into Contoso’s office furniture fixed asset group.

### Create a legal-entity specific rule for fixed assets

1.  In the **Business rules for fixed assets determination** form, on the **Legal entity-specific rule** FastTab, create a legal entity-specific rule for Fabrikam for the **Office furniture and equipment** procurement category. The rule is that a product purchased from the **Office furniture and equipment** procurement category must be capitalized as a fixed asset for Fabrikam if the cost of the item is at least 200 EUR.

2.  On the **Legal entity-specific rule** FastTab, select the **Has qualifiers?** check box. Add a qualifier question: **Does this item require power to operate?**

3.  On the **Legal entity-specific rule** FastTab, click **Add**. In the list, in the **Name** field, enter **Office furn – No power**, and then enter **No** in the **Description** field. In the same row, in the **Fixed asset group** field, select Fabrikam’s fixed asset group for office furniture.

4.  In the next row, in the **Name** field, enter **Office equip – Power**, and then enter **Yes** in the **Description** field. In the **Fixed asset group** field, select Fabrikam’s fixed asset group for office equipment.

On a purchase requisition, a Fabrikam employee selects an item from the **Office furniture and equipment** procurement category. The item price is less than USD 1,000 but more than 200 EUR. The employee must respond to the qualifier question for Fabrikam on the **Fixed assets** FastTab in the purchase requisition **Line details** form. If the employee selects **Yes**, the product is classified into the **Office equipment** fixed asset group for Fabrikam. If the employee selects **No**, the product is classified to the **Office furniture** fixed asset group for Fabrikam.

The person who reviews a purchase requisition for Contoso or Fabrikam can override the employee responses to the qualifier and modify the fixed asset group on the purchase requisition.

  


