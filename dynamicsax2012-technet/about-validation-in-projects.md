---
title: About validation in projects
TOCTitle: About validation in projects
ms:assetid: 89c6fab9-56cb-4cfb-b803-bc3f2ee24830
ms:mtpsurl: https://technet.microsoft.com/library/Aa498234(v=AX.60)
ms:contentKeyID: 36966734
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- validation
- validation parameters
- category/employee
- project/category
- project/employee
- validation connections
- validation groups
audience: Application User
ms.search.region: Global
---

# About validation in projects 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To control how project transactions are recorded, you can limit the values that are available in journals and timesheets for workers, projects, and categories. You can also set up rules to prevent records that violate the validation rules from being posted.

To use the validation feature, you must complete the following tasks:

  - Create one or more of the following validation groups: **Worker/project**, **Project/category**, or **Category/worker**. For more information, see [Define validation connections](define-validation-connections.md).

  - Combine projects, workers, and categories as needed in validation groups. For more information, see [Set up validation groups](set-up-validation-groups.md).

  - Enable workers for category or project validation. By default, workers are not restricted by the project validation system. You must enable this option for individual workers. For more information, see [Enable validation parameters](enable-validation-parameters.md).

  - In the **Project management and accounting parameters** form, in the **General** area, set up parameters in the **Project/category**, **Worker/project**, and **Category/worker** fields. These parameters determine restrictions, for entry into journals and timesheets, for any validation connections that you set up for workers, projects, and categories. You can choose from the following options:
    
      - **None** – All projects/categories, project/workers, and category/workers are shown.
    
      - **Lookup** – A filtered list of projects/categories, project/workers, and category/workers is shown. Valid options that are not in the list can be entered.
    
      - **Mandatory** – A specified list of projects/categories, project/workers, and category/workers is shown. Only options that appear in the list can be selected.

  - Define category and worker validation assignments for a selected project. For more information, see [Project validation worker assignments (form)](https://technet.microsoft.com/library/aa583039\(v=ax.60\)) and [Project validation category assignments (form)](https://technet.microsoft.com/library/hh209635\(v=ax.60\)).

**Example**

You create a group for junior sales personnel in the **Worker/category** form and add to it all junior salespeople and all categories for transactions that can be entered by junior sales personnel.

Next, in the **Project management and accounting parameters** form, in the **General** area, in the **Category/worker** field, you select **Mandatory**.

As a result, when a junior salesperson enters a transaction line in the **Expense** journal form, only the categories that are defined for the junior sales personnel group are available.

In addition to the categories that are specified for the junior sales personnel group, you can add extra categories for particular workers in the group. These workers can then select from the additional categories when they record expense transactions.

## See also

[Define validation connections](define-validation-connections.md)

[Set up validation groups](set-up-validation-groups.md)

[Enable validation parameters](enable-validation-parameters.md)

[Project management and accounting parameters (form)](https://technet.microsoft.com/library/aa599440\(v=ax.60\))

[Project validation worker assignments (form)](https://technet.microsoft.com/library/aa583039\(v=ax.60\))

[Project validation category assignments (form)](https://technet.microsoft.com/library/hh209635\(v=ax.60\))

  


