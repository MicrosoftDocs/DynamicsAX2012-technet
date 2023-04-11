---
title: Create categories and category groups for projects
TOCTitle: Create categories and category groups for projects
ms:assetid: 9cedf673-f167-49ea-b2b6-87924d417cd9
ms:mtpsurl: https://technet.microsoft.com/library/Aa571702(v=AX.60)
ms:contentKeyID: 36811421
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- category
- categories
- category group
- transaction type
audience: Application User
ms.search.region: Global
---

# Create categories and category groups for projects 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Categories represent the types of costs or revenues that are defined for your organization. In Microsoft Dynamics AX, each category must be associated with a category group. Categories and category groups are organized by types. These types correspond to the transaction types that are available in **Project management and accounting**.

To create categories and category groups, you first create the category group, and then add categories to the group. The transaction type for the category must be the same as the one that is defined for the category group. For example, if the category group has a transaction type of **Hour**, a category associated with the category group must also have a transaction type of **Hour**.

## Create a category group

1.  Click **Project management and accounting** \> **Setup** \> **Categories** \> **Category groups**.

2.  In the **Category groups** form, click **New**.

3.  In the **Category group** field, enter an identifier for the category group.

4.  In the **Transaction type** field, select a transaction type for the category group.

5.  Optional: In the **Category group name** field, enter a name for the category group.

6.  Optional: In the **Line property** field, select the line property that you want to use to define cost and sales percentages. The line property that you select also specifies the options for revenue accrual and capitalization costs for this category group.

7.  On the **Cost accounts** FastTab, select the accounts that various types of costs will be charged to.

8.  On the **Revenue accounts** FastTab, select the accounts that various types of revenue will be charged to.

## Create a category

1.  Click **Project management and accounting** \> **Setup** \> **Categories** \> **Project categories**.

2.  In the **Project categories** form, click **New**.

3.  In the **Category ID** field, select the identifier of a category.
    

    > [!NOTE]
    > <P>Only shared categories appear in this field. Shared categories are created in the <STRONG>Shared categories</STRONG> form. For more information, see <A href="https://technet.microsoft.com/library/hh209532(v=ax.60)">Shared categories (form)</A>.</P>



4.  On the **Project** FastTab, in the **Category group** field, select the category group with which you want to associate the category.

5.  Optional: If you want to use this category in **Travel and expense** and **Production control**, select the **Use in Expense** and **Use in Production** check boxes.

6.  On the **Cost accounts** FastTab, select the accounts that various types of costs will be charged to.

7.  On the **Revenue accounts** FastTab, select the accounts that various types of revenue will be charged to.

## See also

[About project category groups](about-project-category-groups.md)

[Configuring category groups, categories, and cost templates](configuring-category-groups-categories-and-cost-templates.md)

[About transaction types](about-transaction-types.md)

  


