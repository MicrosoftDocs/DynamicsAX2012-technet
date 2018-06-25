---
title: About batch attributes
TOCTitle: About batch attributes
ms:assetid: 77968237-ca41-490c-8eca-e64ce57f310f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh209250(v=AX.60)
ms:contentKeyID: 36058213
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# About batch attributes [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Batch attributes are characteristics of raw materials and finished products that make up inventory batches. Batch attributes can differ depending on several factors, such as environmental conditions or the quality of the raw materials used to produce the batch. The number and types of batch attributes used can vary widely from one industry to another.

## Example

Here are two examples of how to use batch attributes:

  - In the cheese industry, milk, which is one of the raw materials used to produce the cheese, may have attributes such as fat content and percent weight. The cheese that is produced from the milk can have other attributes like moisture and age.

  - In the steel industry, the iron that you produce might have attributes such as the percentages of magnesium content, silver content, and zinc content.

## Define batch attributes

You define batch attributes in the **Batch attributes** form. You can also define batch attribute groups, which lets you group multiple attributes that you can then assign to items that share those attributes. By using groups, you eliminate the requirement to add each attribute individually. You define batch attribute groups in the **Batch attribute groups** form. You access both forms under **Setup** in **Inventory and warehouse management**.

## Assign batch attributes to items

You can assign batch attributes to individual items that are held in inventory batches or you can assign them to items that are associated with specific customers. Before you can assign a batch attribute at the customer level, you must first assign it at the item level. The item must have the batch dimension set to active in the **Tracking dimension group**.

To assign a batch attribute to an individual item, use the **Product specific** form. If the attribute is specific to an item for a customer, use the **Customer specific** form.

When you add an attribute to an item, you also define other parameters that include the following:

  - The minimum and maximum ranges for an **Integer** or **Fraction** type attribute.

  - The tolerance actions for an **Integer** or **Fraction** type attribute. The action you select can be either a warning message or an error message if the attribute falls outside the minimum and maximum range.

  - The target value for the attribute. This value is the optimal value of the attribute, and it applies to all attribute types.

You can access these forms for products that you select in the **Released products** list page in **Product information management**. After you assign batch attributes to an item, you can then add specific values to the attributes in the **Inventory batch attributes** form.

## Reserve batches

If you use the **Batch reservation** form, you can perform a batch attribute search. The search helps locate an inventory batch that contains the item with the batch attributes you want. Once you locate the batch, you can then reserve the item to the originating inventory transaction line.

You can access this form from a sales order line to search for and reserve inventory that fulfills the customer’s order. You can also access it from the picking list of the **Production journal lines** to reserve and pick materials for production.

## See also

[Batch attributes (form)](https://technet.microsoft.com/en-us/library/hh209255\(v=ax.60\))

[Batch attribute groups (form)](https://technet.microsoft.com/en-us/library/hh209431\(v=ax.60\))

[Batch reservation (form)](https://technet.microsoft.com/en-us/library/hh208645\(v=ax.60\))

[Customer specific (form)](https://technet.microsoft.com/en-us/library/hh209393\(v=ax.60\))

[Inventory batch attributes (form)](https://technet.microsoft.com/en-us/library/hh209284\(v=ax.60\))

[Product specific (form)](https://technet.microsoft.com/en-us/library/hh227369\(v=ax.60\))

[Production journal lines, picking list (form)](https://technet.microsoft.com/en-us/library/aa616001\(v=ax.60\))

[Sales orders (form)](https://technet.microsoft.com/en-us/library/aa585863\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

