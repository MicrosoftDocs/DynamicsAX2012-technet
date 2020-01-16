---
title: Set up a channel profile
TOCTitle: Set up a channel profile
ms:assetid: 4ef00ad9-9da2-4d21-b3e1-637f77cab208
ms:mtpsurl: https://technet.microsoft.com/library/JJ677402(v=AX.60)
ms:contentKeyID: 49384182
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Set up a channel profile 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

A channel profile contains properties that must be defined for a retail channel, such as URLs for site collections. The available properties depend on the type of channel.

1.  Click **Retail** \> **Setup** \> **Retail scheduler** \> **Channel integration** \> **Channel profiles**.

2.  Press CTRL+N to create a new channel profile.

3.  In the **Name** field, enter a unique name for the profile.

4.  Select the type of online channel that the profile is for.
    
    In AX 2012 R2, only **SharePoint online store** is available. In AX 2012 R3, you can also set properties for **eBay**, **Amazon**, and **Retail Server**.

5.  Click **Add** to add a property to the profile. For each property, provide the following information:
    
      - **Property key** – Select the type of property to set for the selected channel profile. The available properties depend on the profile type that you selected. For example, for a profile type of **SharePoint online store**, you can select the **Catalog site collection URL** property.
    
      - **Property value** – Specify a value for the property.

6.  Click **Validate profile** to confirm that the property information for the profile is correct.

## See also

[Channel profiles (form)](https://technet.microsoft.com/library/jj677439\(v=ax.60\))

  


