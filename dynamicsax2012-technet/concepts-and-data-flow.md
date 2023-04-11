---
title: Concepts and data flow
TOCTitle: Concepts and data flow
ms:assetid: f5de7da1-9d91-4b8c-af69-ac7c57dfc359
ms:mtpsurl: https://technet.microsoft.com/library/Aa551650(v=AX.60)
ms:contentKeyID: 36931887
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Concepts and data flow 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you use the **Product Builder**, you should understand the concepts implemented in it and the ideas behind the types of configuration information and the setup options that are available.


> [!NOTE]
> <P>This information applies only to Product builder.</P>



  - An item that is configurable with the **Product Builder** is called a modeling enabled item.

  - The structure that makes it possible to configure an item in this manner is called a product model.

  - A product model contains a set of previously defined variable groups and modeling variables. It can also contain a set of validation rules for modeling variables. Modeling variables are the basis of the product model’s **Product Builder configuration** form. Apart from the modeling variables, calculation variables can also be created. These are used in the product model’s internal calculations.

  - The configuration process, that is the steps that the product model must perform at configuration time to create a finished configuration, is defined in a modeling tree. The modeling tree consists of nodes of different types. Its complexity will depend on several factors: the number of modeling variables and calculation variables that have to be handled, the relations between them and the rules that govern their content, and the extent of the bill of material (BOM) and route required to produce the item.

  - Before it can be made active, a product model must be compiled. The compilation creates an executable version of the product model. It also detects some types of logical or syntactical errors that might be hidden in the modeling tree’s node structure.

  - The actual item configuration is initiated from a sales order, sales quotation, purchase order, production order, or project quotation. To the user, the item configuration appears as a user dialog box where data can be entered into the product model’s modeling variables. The data input is then processed by the validation rules that were created for each modeling variable.

  - The **Product Builder configuration** form also uses any default values that have been defined for the product model’s modeling variables. This results in predefined values that are customized to the needs of specific customers from the start of the configuration.

  - A set of user profiles can be created for different types of users who should be granted access to the system. By using user profiles, you can control which modeling variables a specific user group can see or modify during item configuration.

## See also

[About modeling variables](about-modeling-variables.md)

[About product models](about-product-models.md)

[About default values](about-default-values.md)

  


