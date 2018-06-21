---
title: Set up keyboard mapping groups
TOCTitle: Set up keyboard mapping groups
ms:assetid: 98e5d5b1-b845-457f-b054-3a37add85b1c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh597183(v=AX.60)
ms:contentKeyID: 39519248
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Set up keyboard mapping groups [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Use the **Keyboard mapping groups** form to set up and view the keyboard mapping groups and keyboard mappings that are used by the point of sale (POS) registers in a store. A keyboard mapping can include all the shortcut keys that have been created for operations in Microsoft Dynamics AX for Retail POS. Therefore, Retail POS can use various kinds of POS keyboards by mapping the keys to the codes for regular PC keyboard. Additionally, you can disable specific keys on the PC keyboard, or map the keys to other key combinations. When you configure the hardware profile for your POS system, you reference the keyboard mapping group in the **POS hardware profile** form.

## Create keyboard mapping groups

1.  Click **Retail** \> **Setup** \> **POS** \> **Keyboard mapping groups**.

2.  In the **Keyboard mapping groups** form, click **New** to create a new mapping group, or select an existing keyboard mapping group in the list.

3.  Enter or view the name and description of the keyboard mapping group.

## Create keyboard mappings

1.  Click **Retail** \> **Setup** \> **POS** \> **Keyboard mapping groups**.

2.  In the **Keyboard mapping groups** form, select a keyboard mapping group, and then click **Keyboard mapping**.

3.  In the **Keyboard mapping** form, click **New** to create a new keyboard mapping.

4.  In the **Key character** field, enter the character to use as a shortcut key in Retail POS. The **ASCII value** field is automatically populated with the ASCII value for the character.

5.  In the **Operation ID** field, select the operation that is performed by using the shortcut key. The **Action property** field is automatically populated with the appropriate action for the operation.

## See also

[About setting up Retail POS](about-setting-up-retail-pos.md)

[Keyboard mapping groups (form)](https://technet.microsoft.com/en-us/library/hh597324\(v=ax.60\))

[Keyboard mapping (form)](https://technet.microsoft.com/en-us/library/hh597342\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

