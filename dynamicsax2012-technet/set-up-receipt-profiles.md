---
title: Set up receipt profiles
TOCTitle: Set up receipt profiles
ms:assetid: a34cedab-c208-4081-974d-f001b36dddf5
ms:mtpsurl: https://technet.microsoft.com/library/Hh597197(v=AX.60)
ms:contentKeyID: 39519266
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up receipt profiles 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

A receipt profile is a group of form layouts that can be assigned to point of sale (POS) printers via a hardware profile. A receipt profile provides a set of receipt templates for the printers at your registers. You must set up form layouts and receipt profiles to print receipts and other documents from Microsoft Dynamics AX for Retail POS.

After you set up the receipt profiles, you must assign them to the hardware profile, so that the POS register can print the receipts.

## Set up a receipt profile

1.  Click **Retail** \> **Setup** \> **POS** \> **Profiles** \> **Receipt profiles**.

2.  In the **Receipt profile** form, click **New** to create a new receipt profile, or select an existing receipt profile.

3.  In the **Receipt profile ID** field, type a unique identifier for the profile.

4.  In the **Description** field, type a name for the profile.

5.  On the **General** FastTab, click **Add** to add a receipt format to the profile.

6.  In the **Receipt type** field, select the type of receipt that you are creating a profile for. The type of receipt that you create a profile for is the type that is printed from the POS register.

7.  In the **Receipt format** field, select the receipt format to add. You can select only one receipt format for each receipt type. Only receipt formats that have the selected receipt type are displayed in this field.
    
    For more information about how to set up a receipt format, see [Set up receipt formats](set-up-receipt-formats.md).

8.  Click **Designer** to view the selected receipt format.

## Assign a receipt profile to a hardware profile

The receipt profile that you select in a hardware profile assigns a set of receipt formats to the printers on the registers that use that hardware profile.

1.  Click **Retail** \> **Setup** \> **POS** \> **Profiles** \> **Hardware profiles**.

2.  In the **POS hardware profile** form, select the hardware profile to add a receipt profile to.

3.  Click the **Printer** FastTab, and then, in the **Receipt profile ID** field, select the appropriate receipt profile.
    
    For more information about how to set up a hardware profile, see [Set up hardware profiles](set-up-hardware-profiles.md).

## See also

[About setting up Retail POS](about-setting-up-retail-pos.md)

[Receipt profile (form)](https://technet.microsoft.com/library/hh580640\(v=ax.60\))

[POS hardware profile (form)](https://technet.microsoft.com/library/hh580636\(v=ax.60\))

  


