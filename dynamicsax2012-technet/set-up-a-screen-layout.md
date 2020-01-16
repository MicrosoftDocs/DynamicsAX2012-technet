---
title: Set up a screen layout
TOCTitle: Set up a screen layout
ms:assetid: 8a835e7f-0fda-4abd-8124-08044cad2930
ms:mtpsurl: https://technet.microsoft.com/library/Hh597160(v=AX.60)
ms:contentKeyID: 39519217
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up a screen layout 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

The screen layout specifies how the screen is displayed on the point of sale (POS) register. The screen layout specifies the position of various objects. For example, the screen layout specifies the total layout, product grid layout, customer layout, and payment layout. The screen layout also specifies the position of various menu buttons and the overall appearance of the sales interface for Microsoft Dynamics AX for Retail POS that is displayed to the worker. You can configure a screen layout after all the button grids for the layout have been created.

1.  Click **Retail** \> **Setup** \> **POS** \> **Screen layouts**.

2.  In the **Screen layout** form, click **New** to create a new layout, or select an existing screen layout to modify.

3.  In the **Screen layout ID** field, enter a unique ID for the screen layout, and then enter a name for the layout.

4.  In the **Width** and **Height** fields, enter a combination of a width and height to specify a screen resolution. This screen resolution is used in the **Screen layout designer** form to provide a workspace that closely resembles the screen resolution of the POS register.

5.  In the **Button grid 1** through **Button grid 5** fields, select the button grids to display on the POS register that uses this layout. A button grid is a group of similar buttons, such as buttons for products, operations, or payments.
    
    For example, you define one layout for a store and another layout for a manager who works in that store. The general store layout includes a standard set of button grids that is always displayed. The store manager layout includes an additional button grid for operations that only the store manager performs. For example, this layout includes buttons that are used for overrides or approval of large transaction amounts.

## See also

[About setting up screen layouts](about-setting-up-screen-layouts.md)

[Set up a button grid](set-up-a-button-grid.md)

[Screen layouts (form)](https://technet.microsoft.com/library/hh597310\(v=ax.60\))

  


