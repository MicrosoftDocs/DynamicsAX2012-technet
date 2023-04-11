---
title: Set up visual profiles (Retail essentials)
TOCTitle: Set up visual profiles (Retail essentials)
ms:assetid: a80bdcba-1d57-4578-b343-bf39eebc0f2d
ms:mtpsurl: https://technet.microsoft.com/library/Dn736931(v=AX.60)
ms:contentKeyID: 62200408
author: tonyafehr
ms.date: 08/15/2014
mtps_version: v=AX.60
f1_keywords:
- a80bdcba-1d57-4578-b343-bf39eebc0f2d
- MsDynAx060.a80bdcba-1d57-4578-b343-bf39eebc0f2d
---

# Set up visual profiles (Retail essentials) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up the appearance of Retail POS registers. For example, you can select menus that you want to appear on the register screen and define the colors and bars that are visible.

The information that determines the appearance of the register is specified in a visual profile. You can create several visual profiles and then select the profiles that you want to run on specific registers. You can also decide whether to allow a store to modify a visual profile that you assign to a register.


> [!NOTE]
> <P>In Retail essentials, the form that you use to complete this task includes a subset of the controls that are available for other configurations of Retail. If a topic about this form describes controls that you don't see, it may be because you’re using Retail essentials.</P>



## Set up visual profiles

1.  Click **Retail essentials** \> **Channels** \> **Setup** \> **POS** \> **Profiles** \> **Visual profiles**.

2.  In the **POS visual profiles** form, select an existing visual profile, or click **New** to create a new visual profile.

3.  If you are creating a new profile, in the **Profile number** field, enter a unique identification number for the profile.

4.  In the **Description** field, enter a brief description for the profile.

5.  On the **General** FastTab, select the settings for the POS registers that use the selected profile.

6.  On the **Login background** FastTab, in the **Image ID** field, select a picture to be displayed as the background on the POS registers that use the selected profile. If you select **0**, no image is displayed.

7.  On the **Background** FastTab, select the logo to be displayed on the POS registers that use the selected profile. If you select **0**, no image is displayed.

## Assign a visual profile to a POS register

1.  Click **Retail essentials** \> **Channels** \> **POS registers**.

2.  In the **POS registers** list, select the register that you want to assign a profile to, and then, on the **Action Pane**, click **Edit**.

3.  In the **POS registers** form, on the **General** FastTab, in the **Visual profile** field, select the appropriate visual profile.

## See also

[Setting up Retail POS (Retail essentials)](setting-up-retail-pos-retail-essentials.md)

  


