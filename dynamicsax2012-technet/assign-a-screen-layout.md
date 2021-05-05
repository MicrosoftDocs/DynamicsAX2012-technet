---
title: Assign a screen layout
TOCTitle: Assign a screen layout
ms:assetid: 85bf4eda-e70b-4731-a66e-0d5208f8317b
ms:mtpsurl: https://technet.microsoft.com/library/Hh597157(v=AX.60)
ms:contentKeyID: 39519214
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Assign a screen layout 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

When you configure Retail for point of sale (POS), you can design the screen layouts that your workers use on the registers in your stores. You can define one or more screen layouts for your business. Then, when you configure a POS register, you select the ID of the screen layout that the register uses. You can also assign screen layouts to specific stores or specific workers.

When Microsoft Dynamics AX for Retail POS starts, it determines which screen layout to display. For example, you may assign one screen layout to a specific store, another layout to a specific register, and another layout to a specific worker. The system uses the following order to determine the appropriate layout:

1.  Worker

2.  Register

3.  Store

## Assign a screen layout to a store

1.  Click **Retail** \> **Common** \> **Retail channels** \> **Retail stores**.

2.  On the **Retail stores** list page, select the store to assign a screen layout to, or click **Retail store** on the **Action Pane** to create a new store.

3.  In the **Stores** form, on the **General** FastTab, in the **Screen layout ID** field, select the appropriate screen layout.

## Assign a screen layout to a register

1.  Click **Retail** \> **Setup** \> **POS** \> **POS registers**.

2.  On the **POS registers** list page, select the terminal to assign a till layout to, or click **Terminal** on the **Action Pane** to create a new POS register.

3.  On the **Display** FastTab, in the **Screen layout ID** field, select the appropriate till layout.

## Assign a screen layout to a worker

1.  Click **Retail** \> **Common** \> **Retail channels** \> **Retail stores**.

2.  On the **Retail stores** list page, select the store that includes the staff member to assign a screen layout to.

3.  In the **Stores** form, on the **Action Pane**, on the **Setup** tab, in the **Staff** group, click **Staff**.

4.  In the **Staff** form, select the staff member to modify.

5.  Click the **General** tab, and then, in the **Screen layout ID** field, select the appropriate screen layout.

## See also

[About setting up screen layouts](about-setting-up-screen-layouts.md)

[Set up a screen layout](set-up-a-screen-layout.md)

[Design a screen layout](design-a-screen-layout.md)

  


