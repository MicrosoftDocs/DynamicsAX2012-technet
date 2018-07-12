---
title: Set up procurement and sales category defaults for projects
TOCTitle: Set up procurement and sales category defaults for projects
ms:assetid: 07e1964b-1850-433d-aecb-eca62c9a8b0c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh781064(v=AX.60)
ms:contentKeyID: 43894461
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up procurement and sales category defaults for projects 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Category hierarchies are used to classify products or transactions for reporting and analysis. Your organization might use a procurement category hierarchy to track purchases and a sales category hierarchy to track sales. If you purchase the products that are used for a project from a specific procurement category, you can assign a default project category to that procurement category. For example, you assign a project category named **Indirect expense** to a procurement category named **Office supplies**. Your project manager creates a purchase order for a project and selects the **Office supplies** procurement category on a PO line. By default, the cost on the line is automatically assigned to the **Indirect expense** project category for the selected project.

## Assign a project category to a procurement hierarchy

Use the following procedure to set up a default project category for purchases from a procurement hierarchy.

1.  Create a category hierarchy. For more information, see [Key tasks: Set up a category hierarchy](key-tasks-set-up-a-category-hierarchy.md).

2.  Assign the category hierarchy to the **Procurement category hierarchy** type. For more information about category hierarchy types, see [Category hierarchy types (form)](https://technet.microsoft.com/en-us/library/hh227389\(v=ax.60\)).
    

    > [!NOTE]
    > <P>Only one active procurement category hierarchy can be defined for an organization.</P>



3.  In the **Category hierarchy** form, in the left pane, select a procurement category to associate with the project category.

4.  On the **Assign project categories** FastTab, in the **Project category** field, select the project category to use as the default project category for the selected procurement category.

## Assign a project category to a sales hierarchy

Use the following procedure to set up a default project category for a sales hierarchy.

1.  Create a category hierarchy. For more information, see [Key tasks: Set up a category hierarchy](key-tasks-set-up-a-category-hierarchy.md).

2.  Assign the category hierarchy to the **Sales category hierarchy** type. For more information about category hierarchy types, see [Category hierarchy types (form)](https://technet.microsoft.com/en-us/library/hh227389\(v=ax.60\)).
    

    > [!NOTE]
    > <P>Only one active sales category hierarchy can be defined for an organization.</P>



3.  In the **Category hierarchy** form, in the left pane, select a procurement category to associate with the project category.

4.  On the **Assign project categories** FastTab, in the **Project category** field, select the project category to use as the default project category for the selected procurement category.

## See also

[About category hierarchies](about-category-hierarchies.md)

[Key tasks: Set up and maintain procurement category hierarchies](key-tasks-set-up-and-maintain-procurement-category-hierarchies.md)

[About project category groups](about-project-category-groups.md)

[Configuring category groups, categories, and cost templates](configuring-category-groups-categories-and-cost-templates.md)

  


