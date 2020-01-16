---
title: Set up registers
TOCTitle: Set up registers
ms:assetid: 2d92630e-c1e5-4d61-8bcb-59616186b88a
ms:mtpsurl: https://technet.microsoft.com/library/Hh580597(v=AX.60)
ms:contentKeyID: 39519083
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- 2d92630e-c1e5-4d61-8bcb-59616186b88a
- MsDynAx060.2d92630e-c1e5-4d61-8bcb-59616186b88a
audience: Application User
ms.search.region: Global
---

# Set up registers 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

When you set up a terminal in Microsoft Dynamics AX for Retail POS, you select a hardware profile and a visual profile for the terminal. A hardware profile determines the physical configuration of a terminal and a visual profile determines its screen characteristics.

You can assign the profiles either to a specific terminal or to a group of terminals. You can also modify the profiles that are assigned to a terminal. Certain configuration changes do not take effect at stores until the terminals in the store are restarted. In general, if you modify anything that affects the POS terminal setup or configuration of one or more terminals, you must restart the affected terminal.

Before you set up terminals, complete the following prerequisites:

  - Create a store.

  - Create Retail POS functionality profiles and assign them to stores.

  - Create a hardware profile.

  - Create a visual profile.

  - Create a screen layout.

Use the following procedure to set up a terminal and assign profiles to it.

1.  Click **Retail** \> **Setup** \> **POS** \> **POS registers**.

2.  In the **POS registers** list, on the **Action Pane**, in the **New** group, click **Terminal** to create a new terminal.

3.  In the **POS registers** form, on the **General** FastTab, in the **Register number** field, enter a unique number for the terminal.

4.  In the **Reference** field, select a store for the register.

5.  In the **Hardware profile** field, select a profile for the register.

6.  In the **Visual profile** field, select a profile for the register.

7.  On the **General** FastTab, enter values in the remaining fields as appropriate.

8.  In the **POS registers** form, enter values on the other FastTabs as appropriate. For more information, see [POS registers (form)](https://technet.microsoft.com/library/hh597141\(v=ax.60\)).

## See also

[About setting up Retail POS](about-setting-up-retail-pos.md)

  


