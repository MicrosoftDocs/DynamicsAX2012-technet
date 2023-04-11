---
title: Set up hardware profiles
TOCTitle: Set up hardware profiles
ms:assetid: b635525a-0fde-477f-a122-a6a149038f67
ms:mtpsurl: https://technet.microsoft.com/library/Hh597217(v=AX.60)
ms:contentKeyID: 39519289
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up hardware profiles 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Create hardware profiles to set preferences and properties for a register, and for the peripheral devices that are connected to the register. These devices include receipt or document printers, customer displays, magnetic strip readers, cash drawers, bar code scanners, scales, keylocks, keyboards, electronic funds transfer (EFT) hardware, and closed-circuit television (CCTV) cameras.


> [!NOTE]
> <UL>
> <LI>
> <P>Microsoft Dynamics AX for Retail Headquarters supports OPOS-compliant hardware. OPOS is a standard that the retail industry uses for point of sale (POS) devices.</P>
> <LI>
> <P>You must assign a hardware profile for each set of hardware that is used for your registers. If all the registers in a store use the same peripherals, you must assign only one hardware profile for that store. If each register has a unique set of peripherals, you must assign a hardware profile for each register.</P></LI></UL>



A hardware profile contains information about the hardware that is connected to registers. The hardware profile also contains setup information for the peripheral devices. Microsoft Dynamics AX for Retail POS uses the OPOS standard configuration. The POS driver provides a standardized way for software to use register peripherals.

## Set up hardware profiles

1.  Click **Retail** \> **Setup** \> **POS** \> **Profiles** \> **Hardware profiles**.

2.  Click **New** to enter a new profile, or select an existing profile.

3.  On the following FastTabs, enter information about the appropriate hardware devices:
    
      - **Printer** – Specify the settings for the printer that is used to print receipts and other documents for customers.
    
      - **Line display** – You can set up an optional customer display. The customer can use this display to view transaction totals, payment amounts, and optional customized messages. The customer display can also display advertising.
    
      - **Dual display** – If a second monitor is set up in a Windows-based application, you can use the monitor as a line display. This monitor can also display advertising.
    
      - **MSR** – Specify the settings for a magnetic stripe reader (MSR). An MSR reads the information that is encoded in the magnetic stripe on the back of a plastic card. The stripe is read through physical contact and when the stripe is swiped past a reading head. Magnetic stripes are typically used on credit cards, identity cards, and transportation tickets.
    
      - **Drawer** – Specify the settings for the cash drawer. A valid signal from the computer or receipt printer opens the cash drawer.
    
      - **Scanner** – Specify the settings for a product scanner. Because of the constant flow of sales in retail stores, cashiers can scan items into a POS system more accurately than they can enter items manually.
    
      - **RFID** – Specify the settings for radio frequency identification (RFID). RFID is used to track an item in inventory. The item is tagged with an RFID chip. This chip is detected when you pass the item between two RFID bars. The item’s chip sends out a sound that enables the item to be tracked without being invoiced.
    
      - **Scale** – Specify the settings for a scale. A scale is a weighing instrument that is connected to your POS hardware. If you sell items by a weighable unit of measure, the weight of an item is calculated by a POS scale and recorded in the register.
        

        > [!WARNING]
        > <P>You must set the base unit of measure for a product to a unit of weight. For more information about how to set up the base unit of measure for a product, see <A href="https://technet.microsoft.com/library/hh209233(v=ax.60)">Units (form)</A>.</P>

    
      - **Keylock** – Specify the settings for your keylock. The keylock settings specify whether an OPOS keylock or a logon dialog box controls access to the register.
    
      - **Keyboard** – Specify the settings for keyboards. If you use a POS system that does not include a touch screen, the keyboard serves as the primary interface for the POS system. The keyboards that are used for a POS system can vary in complexity and technology. Examples include a standard 101-key keyboard and industry-specific POS keyboards. Grocery stores and restaurants might require special functions that only programmable keyboards can provide. When you select a keyboard, consider the size and your business’s requirements for programmable keys.
    
      - **EFT service** – Specify the settings for your EFT hardware. Use EFT for electronic payments and collections. EFT is based on a deferred net settlement (DNS), in which transactions are settled in batches at a specific time.
    
      - **CCTV** – Specify the settings for a security camera.
    
      - **Cash** – Specify the settings for a cash changer.
    
      - **PIN pad** – Specify the settings for the PIN pad.

## Assign a hardware profile to a register

1.  Click **Retail** \> **Setup** \> **POS** \> **POS registers**.

2.  On the **POS registers** list page, select the terminal to assign a hardware profile to.

3.  On the **Action Pane**, in the **Maintain** group, click **Edit**.

4.  In the **POS registers** form, on the **General** tab, in the **Hardware profile** field, select the appropriate hardware profile.
    
    For more information about how to set up a POS terminal, see [Set up registers](set-up-registers.md).

## See also

[About setting up Retail POS](about-setting-up-retail-pos.md)

[POS hardware profile (form)](https://technet.microsoft.com/library/hh580636\(v=ax.60\))

  


