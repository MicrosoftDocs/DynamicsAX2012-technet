---
title: About reusing configurations
TOCTitle: About reusing configurations
ms:assetid: e0f67cef-f26d-4987-abe3-1dc2e660968c
ms:mtpsurl: https://technet.microsoft.com/library/JJ677368(v=AX.60)
ms:contentKeyID: 49384144
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About reusing configurations 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can specify that you want to automatically reuse an existing configuration for a product. When the user finishes a configuration session, the system verifies whether a configuration that matches the user’s selections already exists. If a matching configuration is found, the configuration ID, corresponding bill of materials (BOM), and route are reused.


> [!NOTE]
> <P>This topic includes information about features that were added or changed for Microsoft Dynamics AX 2012 R2. This information also applies to AX 2012 R3. See the section later in this topic.</P>



## Requirements for reusing configurations

To allow a configuration to be reused, you must specify the following information for the components and attributes in the **Constraint-based product configuration model details** form:

  - Components and subcomponents – On the **General** FastTab, select **Yes** in the **Reuse configurations** field.

  - Attributes – On the **Attributes** FastTab, select the **Include in reuse** check box. This check box is displayed only when the related component is enabled for reuse. If you do not select any attributes for reuse, the configuration is always reused, regardless of the user’s selections during a configuration session. The attributes in the existing configuration must match the user’s selections. For example, if the user selects the color **Blue** during a configuration session, the system verifies whether an existing configuration of the component has an attribute for the color blue.

## See also

[About product configuration models](about-product-configuration-models.md)

  


