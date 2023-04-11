---
title: Set up receipt profiles (Retail essentials)
TOCTitle: Set up receipt profiles (Retail essentials)
ms:assetid: 78cb4bd5-e0fb-4e40-8d34-79b01770421c
ms:mtpsurl: https://technet.microsoft.com/library/Dn736900(v=AX.60)
ms:contentKeyID: 62200377
author: tonyafehr
ms.date: 08/15/2014
mtps_version: v=AX.60
---

# Set up receipt profiles (Retail essentials) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up receipt profiles. A receipt profile is a group of form layouts that can be assigned to point-of-sale (POS) printers via a hardware profile. A receipt profile provides a set of receipt templates for the printers at your registers. You must set up form layouts and receipt profiles to print receipts and other documents from Retail essentials. After you set up the receipt profiles, you must assign them to the hardware profile, so that the POS register can print the receipts.


> [!NOTE]
> <P>In Retail essentials, the forms that you use to complete these tasks include a subset of the controls that are available for other configurations of Retail. If other topics about these forms describe controls that you don't see, it may be because you’re using Retail essentials.</P>



## Set up a receipt profile

1.  Click **Retail essentials** \> **Channels** \> **Setup** \> **POS** \> **Profiles** \> **Receipt profiles**.

2.  In the **Receipt profile** form, click **New** to create a new receipt profile, or select an existing receipt profile.

3.  In the **Receipt profile ID** field, type a unique identifier for the profile.

4.  In the **Description** field, type a name for the profile.

5.  On the **General** FastTab, click **Add** to add a receipt format to the profile.

6.  In the **Receipt type** field, select the type of receipt that you are creating a profile for. This is the type of receipt that is printed from the POS register.

7.  In the **Receipt format** field, select the receipt format to add. You can select only one receipt format for each receipt type. Only receipt formats that can be used with the selected receipt type are displayed in this field.
    
    For more information about how to set up a receipt format, see [Set up receipt formats (Retail essentials)](set-up-receipt-formats-retail-essentials.md).

8.  Click **Designer** to view the selected receipt format.

## Assign a receipt profile to a hardware profile

The receipt profile that you select in a hardware profile assigns a set of receipt formats to the printers on the registers that use that hardware profile.

1.  Click **Retail essentials** \> **Channels** \> **Setup** \> **POS** \> **Profiles** \> **Hardware profiles**.

2.  In the **Hardware profiles** form, select the hardware profile to add a receipt profile to.

3.  On the **Printer** FastTab, in the **Receipt profile ID** field, select the appropriate receipt profile.
    
    For more information about how to set up a hardware profile, see [Set up hardware profiles (Retail Essentials)](set-up-hardware-profiles-retail-essentials.md).

## See also

[Setting up Retail POS (Retail essentials)](setting-up-retail-pos-retail-essentials.md)

  


