---
title: Create a subcomponent for a component
TOCTitle: Create a subcomponent for a component
ms:assetid: 42427253-5e1f-4589-a02b-273ccddd9fa8
ms:mtpsurl: https://technet.microsoft.com/library/Hh580618(v=AX.60)
ms:contentKeyID: 39519105
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- component
- product configurator
- subcomponent
audience: Application User
ms.search.region: Global
---

# Create a subcomponent for a component 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create a hierarchy of components in a product configuration model by adding components as subcomponents. The hierarchy represents the relations between a root component, such as an audio system, and its parts, such as stereo speakers, a receiver, and an amplifier. A component becomes a subcomponent when you add it to another component in a product configuration model. For more information, see [Create components](create-components.md).

1.  Click **Product information management** \> **Common** \> **Product configuration models**.

2.  Select the product configuration model to add the component to, and then click **Edit** on the **Action Pane**.

3.  Select the component in the component tree on the left side of the **Constraint-based product configuration model details** form, and then expand the **Attributes** FastTab.

4.  On the toolbar, click **Name**.

5.  In the **Name** field, enter the name of the subcomponent.

6.  In the **Solver name** field, enter the name of the subcomponent in the Solver Foundation syntax. For example, the name cannot contain spaces or special characters, such as ampersands (&) and number signs (\#).

7.  In the **Component** field, select the component that the subcomponent is based on.

8.  Click **BOM line details** to associate the subcomponent with a product master.
    

    > [!NOTE]
    > <P>A subcomponent must be associated with a product. Otherwise, a user who has configured a product cannot save the configuration.</P>



## See also

[About product configuration models](about-product-configuration-models.md)

  


