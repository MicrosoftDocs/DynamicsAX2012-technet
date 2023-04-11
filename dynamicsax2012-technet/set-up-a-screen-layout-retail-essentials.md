---
title: Set up a screen layout (Retail essentials)
TOCTitle: Set up a screen layout (Retail essentials)
ms:assetid: bf9fadd7-4cc7-4057-b61b-176fbe18cd6a
ms:mtpsurl: https://technet.microsoft.com/library/Dn736941(v=AX.60)
ms:contentKeyID: 62200418
author: tonyafehr
ms.date: 08/15/2014
mtps_version: v=AX.60
---

# Set up a screen layout (Retail essentials) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up a screen layout for one or more registers. The screen layout specifies how the screen is displayed on the register. You can specify the position of various objects, such as the total amounts, the product grid, customer information, and payment information. The screen layout also specifies the position of various menu buttons and the overall appearance of the sales interface that is displayed to workers on the point-of-sale (POS) registers.


> [!NOTE]
> <P>Before you configure a screen layout, you must create all the button grids that you want to appear in the layout. For more information, see <A href="set-up-a-button-grid-retail-essentials.md">Set up a button grid (Retail essentials)</A>.</P>



To set up screen layouts for registers, follow these steps:

1.  Click **Retail essentials** \> **Channels** \> **Setup** \> **POS** \> **Screen layouts**.

2.  In the **Screen layouts** form, click **New** to create a new layout, or select an existing screen layout to modify.

3.  In the **Screen layout ID** field, enter a unique ID for the screen layout, and then enter a name for the layout.

4.  In the **Width** and **Height** fields, enter a combination of a width and height to specify a screen resolution. This screen resolution is used in the **Screen layout designer** form to provide a workspace that closely resembles the screen resolution of the POS register in the store.

5.  On the **Button grids** FastTab, in the **Layout zone** field, select the button grids to display on the POS register that uses this layout. A button grid is a group of similar buttons, such as buttons for products, operations, or payments.
    
    For example, you define one layout for a store and another layout for a manager who works in that store. The general store layout includes a standard set of button grids that is always displayed. The store manager layout includes an additional button grid for operations that only the store manager performs. For example, this layout might include buttons that are used for overrides or approval of large transaction amounts.


> [!NOTE]
> <P>In Retail essentials, the form that you use to complete this task includes a subset of the controls that are available for other configurations of Retail. If a topic about this form describes controls that you don't see, it may be because you’re using Retail essentials.</P>



## See also

[Setting up screen layouts (Retail essentials)](setting-up-screen-layouts-retail-essentials.md)

  


