---
title: Create a cost template
TOCTitle: Create a cost template
ms:assetid: 61dcdc31-7458-42e7-837a-9dfe1abbd1a3
ms:mtpsurl: https://technet.microsoft.com/library/Aa571128(v=AX.60)
ms:contentKeyID: 36057661
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- cost template
audience: Application User
ms.search.region: Global
---

# Create a cost template 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A cost template determines whether the automatically-calculated percentage of completion can be edited, and whether the percent complete is calculated in amounts or in units. Because a cost template refers to a set of cost template lines, when you set up a cost template you must also set up cost template lines.

## Cost template lines

Cost template lines determine which categories are included in the automatically-calculated percent complete.

Every transaction has a project category. Cost template lines are mapped to categories by using the **Cost lines** form. This mapping then maps transactions to cost templates lines, so that the following estimate information can be outlined for fixed-price projects:

  - Degree of completion.

  - Estimates on individual cost template lines. Expenses, hours, and items always refer to three different cost template lines. The benefit of this structure is that you can follow up on multiple transactions on a project at the same time by estimating the remaining work on a cost estimate.

If nothing has been modified in the **Cost lines** form, all existing categories are attached to the three predefined cost lines:

  - Hour categories are attached to the **Hour** cost line.

  - Expense categories are attached to the **Expense** cost line.

  - Item categories are attached to the **Item** cost line.


> [!TIP]
> <P>If you create additional cost lines, you must redefine one or more of your categories to refer to the new cost line.</P>



## To create a cost template

1.  Click **Project management and accounting** \> **Setup** \> **Estimates** \> **Cost template**.

2.  Press CTRL+N to create a new line.

3.  Enter the appropriate information in the cost template fields.

## See also

[Cost template (form)](https://technet.microsoft.com/library/aa616683\(v=ax.60\))

[Configuring category groups, categories, and cost templates](configuring-category-groups-categories-and-cost-templates.md)

[About cost templates](about-cost-templates.md)

[Cost lines (form)](https://technet.microsoft.com/library/aa550294\(v=ax.60\))

[Cost lines setup (form)](https://technet.microsoft.com/library/aa617055\(v=ax.60\))

  


