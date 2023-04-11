---
title: Set up hardware profiles (Retail Essentials)
TOCTitle: Set up hardware profiles (Retail Essentials)
ms:assetid: 8100e9d1-bf4a-4d4f-a07f-c4cf25ecad59
ms:mtpsurl: https://technet.microsoft.com/library/Dn736908(v=AX.60)
ms:contentKeyID: 62200386
author: tonyafehr
ms.date: 08/15/2014
mtps_version: v=AX.60
f1_keywords:
- 8100e9d1-bf4a-4d4f-a07f-c4cf25ecad59
- MsDynAx060.8100e9d1-bf4a-4d4f-a07f-c4cf25ecad59
---

# Set up hardware profiles (Retail Essentials) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to create hardware profiles. Hardware profiles are used to set preferences and properties for a register and the peripheral devices that are connected to the register. Hardware devices include receipt or document printers, customer displays, magnetic strip readers (MSRs), cash drawers, bar code scanners, scales, keylocks, keyboards, and the electronic funds transfer (EFT) setup.

You must assign a hardware profile for each set of hardware that is used for your registers. If each register has a unique set of peripherals, you must assign a different hardware profile to each register. If each register has the same set of peripherals, you can assign the same hardware profile to every register.

Retail essentials supports hardware that complies with Object Linking and Embedding for Retail POS (OPOS). OPOS is a standard that the retail industry uses for point of sale (POS) devices.


> [!NOTE]
> <P>In Retail essentials, the form that you use to complete this task includes a subset of the controls that are available for other configurations of Retail. If a topic about this form describes controls that you don't see, it may be because you’re using Retail essentials.</P>



## Set up hardware profiles

1.  Click **Retail essentials** \> **Channels** \> **Setup** \> **POS** \> **Profiles** \> **Hardware profiles**.

2.  Click **New** to enter a new profile, or select an existing profile.

3.  On the following FastTabs, enter information about the appropriate hardware devices:
    
      - **Printer** and **Printer 2** – Specify the settings for the printers that are used to print receipts and other documents.
    
      - **Line display** – You can set up an optional customer display. The customer can use this display to view transaction totals, payment amounts, and optional customized messages. The customer display can also display advertising.
    
      - **Dual display** – If a second monitor is set up in a Windows-based application, you can use the monitor as a line display. This monitor can also display advertising.
    
      - **MSR** – Specify the settings for a magnetic stripe reader. An MSR reads the information that is encoded in the magnetic stripe on the back of a plastic card. The stripe is read through physical contact, and when the stripe is swiped past a reading head. Magnetic stripes are typically used on credit cards, identity cards, and transportation tickets.
        
        If you are using only a keyboard wedge MSR that does not use OPOS drivers, you must still specify **Start track 1**, **Separator**, and **End track 1** on the **MSR** FastTab.
    
      - **Drawer** and **Drawer 2** – Specify the settings for one or two cash drawers. A valid signal from the computer or receipt printer opens the cash drawer.
    
      - **Scanner** and **Scanner 2** – Specify the settings for one or two scanners. Because of the constant flow of sales in retail stores, cashiers can scan items into a POS system more accurately than they can enter items manually.
    
      - **Scale** – Specify the settings for a scale. A scale is a weighing instrument that is connected to your POS hardware. If you sell items by a weighable unit of measure, the weight of an item is calculated by a POS scale and recorded in the register.
        

        > [!NOTE]
        > <P>You must set the base unit of measure for a product to a unit of weight. For more information about how to set up the base unit of measure for a product, see <A href="https://technet.microsoft.com/library/hh209233(v=ax.60)">Units (form)</A>.</P>

    
      - **Keylock** – Specify the settings for your keylock. The keylock settings specify whether an OPOS keylock or a logon dialog box controls access to the register.
    
      - **Keyboard** – Specify the settings for keyboard mapping groups.
    
      - **EFT service** – Specify the settings for your EFT payment processor.
    
      - **PIN pad** – Specify the settings for the PIN pad.
    
      - **Signature capture** – Specify the settings for the signature capture pad.

## Assign a hardware profile to a register

1.  Click **Retail essentials** \> **Channels** \> **POS registers**.

2.  On the **POS registers** list page, select the register to assign a hardware profile to.

3.  On the **Action Pane**, in the **Maintain** group, click **Edit**.

4.  In the **POS registers** form, on the **General** tab, in the **Hardware profile** field, select the appropriate hardware profile.
    
    For more information about how to set up a POS terminal, see [Set up registers (Retail essentials)](set-up-registers-retail-essentials.md).

## See also

[Setting up Retail POS (Retail essentials)](setting-up-retail-pos-retail-essentials.md)

[Setting up profiles (Retail essentials)](setting-up-profiles-retail-essentials.md)

  


