---
title: About formulas
TOCTitle: About formulas
ms:assetid: 142186e7-2e23-4630-9853-7a404f24e257
ms:mtpsurl: https://technet.microsoft.com/library/Hh352182(v=AX.60)
ms:contentKeyID: 36687815
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About formulas 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A formula consists of the required ingredients and quantities that are required to produce a determined quantity of a formula item. Depending on the task that you perform, you can access formula functionality from **Inventory and warehouse management** or **Product information management**.

## Formulas and formula lines

In Process manufacturing production and logistics, a formula consists of one or more formula lines, which identify the ingredients or items that make up the formula. A formula line may contain BOM items, formula items, catch weight items, purchased items, co-products, or by-products. Because many items are used in multiple products, an item may be used in more than one formula.

An example of a formula might be a chocolate chip cookie formula. The ingredients for that formula use multiple lines, such as flour, sugar, eggs, butter, and chocolate chips. The chocolate chip cookie formula contains ingredients that are most likely used in other formulas. For example, while you make the chocolate chip cookies, there might be leftovers, such as crumbs, or some of the cookies may be over or under baked. These items could be set up as co-products or by-products depending on the production operations.

## Formula versions

To create a new formula, you must first create a formula version before you add the formula line items with their specific characteristics. Every formula must have at least one version. The **Approved** button on a formula version becomes available only after a version record has been successfully saved. Each formula version record is associated with one or many co-products and by-products that can be produced as you produce the finished product. Many products can be made from the same ingredients in different batch sizes, multiples, or using different yields. You can create as many versions of a formula as needed.

To manage multiple active formula versions, use effective date ranges or from quantity fields. Multiple active formula versions can exist only if the date range and from quantity do not overlap.

## Approving and activating formulas and formula versions

 Formulas and formula versions must be approved before they can be used for planning and production. Although formulas are usually activated before they are used, you can select a formula version during production that is approved, but not activated.

To secure a formula or formula version, you can set **Block editing** and **Block removal of approval** parameters in the **Production control parameters** form.

If you select **Block editing** and the formula is approved, no fields in the formula lines can be deleted or edited. However, if you remove the approval of the formula, you can delete and modify the formula lines. You can also create new formulas and new formula versions.

If you select **Block removal of approval**, you cannot un-approve an approved formula or formula version. However, you can create new formulas and new formula versions, and you can remove activation of the formula version.

You can add more levels of control by using electronic signature functionality. When a user is set up to require electronic signature on formula approval, a **Signature** form is displayed at activation of the formula. You must be authorized to sign electronically and the certificate must be successfully validated for the change to be committed. If your signature cannot be authenticated, the approval or removal of approval is denied and the change that initiated it is returned to its original state.

## Using the Scalable feature

The Scalable feature is available only if all item components in the formula are set to **Variable consumption**. It is not available for **Fixed consumption** or **Step consumption**. By using the scalable feature, any change that you make to an ingredient in a formula will also adjust the quantity of the other ingredients that you select. The size of the formula is also adjusted. Likewise, any change in the formula size will change the quantity of all ingredients that are scalable. This feature is specifically for formula creation and maintenance and does not indicate whether the ingredient quantity will scale up or down on a batch order.

## Using Step consumption

Step consumption eliminates the requirement to enter a quantity on the **Formula line** tab for an ingredient. Instead, Step consumption is configured to have a **From series** and a **Quantity**. Based on the batch order quantity, the information from the Step consumption per series record that satisfies this quantity is selected. This is useful where the consumption rate is not linear with the batch order size and only increases the requirement when a certain quantity threshold is met. To enable this feature for a new formula, change the formula setting under the **Consumption calculation group** from **Standard** to **Step** for the applicable ingredient. You specify this consumption method on the **Setup** tab in the **Formula line** form.

## See also

[About line types](about-line-types.md)

[Formula (form)](https://technet.microsoft.com/library/hh328668\(v=ax.60\))

[Formula line (form)](https://technet.microsoft.com/library/hh352331\(v=ax.60\))

[Formula version (form)](https://technet.microsoft.com/library/hh352348\(v=ax.60\))

[Production control parameters (form)](https://technet.microsoft.com/library/aa498700\(v=ax.60\))

  


