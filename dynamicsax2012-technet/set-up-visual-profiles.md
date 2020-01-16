---
title: Set up visual profiles
TOCTitle: Set up visual profiles
ms:assetid: 11d730e4-2525-46ec-bc16-810d11577521
ms:mtpsurl: https://technet.microsoft.com/library/Hh580572(v=AX.60)
ms:contentKeyID: 39519050
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Forms.RetailVisualProfile
- MsDynAx060.Forms.RetailVisualProfile
audience: Application User
ms.search.region: Global
---

# Set up visual profiles 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

A visual profile contains basic information that determines the appearance of Microsoft Dynamics AX for Retail POS registers. This topic explains how to use the **POS visual profiles** form to select the POS application and the colors or pictures that are visible on the register.

You can create several visual profiles and assign specific profiles to run on specific registers.


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed for Microsoft Dynamics AX 2012 R3. For more information, see the section later in this topic.</P>



## Set up visual profiles

1.  Click **Retail** \> **Setup** \> **POS** \> **Profiles** \> **Visual profiles**.

2.  In the **POS visual profiles** form, click **New** to create a new visual profile.

3.  In the **Profile number** field, enter a unique identifier for the profile.

4.  In the **Description** field, enter a brief description for the profile.

5.  On the **General** FastTab, select the settings for the POS registers that use the selected profile.
    
      - Select the **Full screen mode** check box to display Retail POS in full screen mode rather than in a window.
    
      - The **Screen width** must be at least 1024 pixels. The **Screen height** must be at least 768 pixels.
    
      - Select the **Design allowed on POS** check box to allow a store to modify the profile design on a register.
    
      - Select the **Hide cursor** check box to hide the mouse cursor in Retail POS.
    
      - In the **Theme** field, select a visual theme for Retail POS. Each theme is a set of coordinated colors for the point-of-sale screen.

6.  On the **Login background** FastTab, in the **Image ID** field, select a picture to be displayed as the background on the logon screen of Retail POS. If you select **0**, no image is displayed.

## Set up visual profiles in Microsoft Dynamics AX 2012 R3

1.  Click **Retail** \> **Setup** \> **POS** \> **Profiles** \> **Visual profiles**.

2.  In the **POS visual profiles** form, click **New** to create a new visual profile.

3.  In the **Profile number** field, enter a unique identifier for the profile.

4.  In the **Description** field, enter a brief description for the profile.

5.  On the **General** FastTab, in the **Application type** field, do one of the following:
    
      - Select a Retail POS application type, and then enter the following information:
        
        1.  On the **General** FastTab, select the **Full screen mode** check box to display Retail POS in full screen mode rather than in a window.
        
        2.  The **Screen width** must be at least 1024 pixels. The **Screen height** must be at least 768 pixels.
        
        3.  Select the **Design allowed on POS** check box to allow a store to modify the profile design on a register.
        
        4.  Select the **Hide cursor** check box to hide the mouse cursor in Retail POS.
        
        5.  In the **Theme** field, select a visual theme for Retail POS. Each theme is a set of coordinated colors for the point-of-sale screen.
        
        6.  In the **Font scheme** field, select a font scheme, either **Standard** or **Large**. This affects the size of the text on the Retail POS screen.
        
        7.  On the **Login background** FastTab, in the **Image ID** field, select a picture to be displayed as the background on the logon screen of Retail POS. If you select **0**, no image is displayed.
    
      - Select a Retail Modern POS application type, and then enter the following information:
        
        1.  On the **General** FastTab, in the **Theme** field, select a visual theme for Retail POS. Each theme is a set of coordinated colors for the point-of-sale screen.
        
        2.  In the **Accent color** field, select an accent color to use with the selected theme.
        
        3.  In the **Font scheme** field, select a font scheme, either **Standard** or **Large**. This affects the size of the text on the Retail POS screen.
        
        4.  On the **Login background** FastTab, in the **Image ID** field, select a picture to be displayed as the background on the logon screen of Retail POS. If you select **0**, no image is displayed.
        
        5.  On the **Background** FastTab, in the **Image ID** field, select a picture to be displayed as the background of Retail POS. If you select **0**, no image is displayed.

## Assign a visual profile to a POS register

1.  Click **Retail** \> **Setup** \> **POS** \> **POS registers**.

2.  In the **POS registers** list, select the register that you want to assign a profile to.

3.  On the **General** FastTab, in the **Visual profile** field, select the appropriate visual profile.

## See also

[About setting up Retail POS](about-setting-up-retail-pos.md)

[POS visual profiles (form)](https://technet.microsoft.com/library/hh597120\(v=ax.60\))

  


