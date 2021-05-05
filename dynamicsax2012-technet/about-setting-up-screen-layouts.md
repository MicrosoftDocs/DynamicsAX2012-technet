---
title: About setting up screen layouts
TOCTitle: About setting up screen layouts
ms:assetid: 0eef4cc3-3cb7-4349-947c-02061374ece6
ms:mtpsurl: https://technet.microsoft.com/library/Hh580568(v=AX.60)
ms:contentKeyID: 39519046
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- screen layout
- screen layouts
audience: Application User
ms.search.region: Global
---

# About setting up screen layouts 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

The graphical design of the interface for Microsoft Dynamics AX for Retail POS is controlled by the till layout. A layout controls the position of various objects. Examples include the total layout, item grid layout, customer layout, and payment layout, and the layout of various menu buttons. Layouts also include the overall appearance of the sales interface for Retail POS that is presented to workers.

The till layout contains information that controls the visual appearance of objects on a register screen, such as the menus that appear and the position of those menus. The till layout also defines the colors and bars that are displayed.

You can design several till layouts for a business, and then select the till layouts that are used for specific registers. The **Screen layout ID** field in the **POS registers** form identifies the till layout that is used for the register.

You can also assign a specific till layout to a specific register, worker, or store. When Retail POS starts, it determines whether a specific layout is assigned to the worker who logged on, the register, or the store, in that order.

After you set up a till layout, you must assign the layout to a store, register, or worker. You can also assign the layout to more than one of these entities.

A till layout can optionally contain pictures and custom button grids.


> [!NOTE]
> <P>Often, the Retail POS screen layout is specified at the head office by using Microsoft Dynamics AX for Retail Headquarters, and then sent to the stores. In this case, any local customizations that are done at the stores are lost.</P>



## See also

[Set up a screen layout](set-up-a-screen-layout.md)

  


