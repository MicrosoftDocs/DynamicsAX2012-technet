---
title: Set up keyboard mapping and mapping groups (Retail essentials)
TOCTitle: Set up keyboard mapping and mapping groups (Retail essentials)
ms:assetid: 1282a565-7b4b-4059-b15b-f3925ac3512f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn716046(v=AX.60)
ms:contentKeyID: 62200310
ms.date: 08/15/2014
mtps_version: v=AX.60
---

# Set up keyboard mapping and mapping groups (Retail essentials) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up keyboard mapping groups and keyboard mapping. A keyboard mapping group contains one or more key mappings that associate individual keyboard keys with operations in Retail POS. For example, you could map the number “2” keyboard key to the “Issue gift card” operation. If your store issues gift cards often, this shortcut key could save time at the point of sale.

After you set up a keyboard mapping group, you can assign it to a point-of-sale (POS) register.


> [!NOTE]
> <P>In Retail essentials, the form that you use to complete this task includes a subset of the controls that are available for other configurations of Retail. If a topic about this form describes controls that you don't see, it may be because you’re using Retail essentials.</P>



## Create or modify keyboard mapping groups

1.  Click **Retail essentials** \> **Channels** \> **Setup** \> **POS** \> **Keyboard mapping groups**.

2.  In the **Keyboard mapping groups** form, click **New** to create a new keyboard mapping group, or select an existing group, and then click **Keyboard mapping**.

3.  In the **Keyboard mapping** form, click **New** to create a new keyboard mapping, or select an existing one.

4.  In the **Key character** field, enter the character to use as a shortcut key in Retail POS. The **ASCII value** field is automatically populated with the ASCII value for the character.

5.  In the **Operation ID** field, select the operation that is performed by using the shortcut key. The **Action property** field is automatically populated with the appropriate action for the operation.

6.  Repeat steps 3 through 5 for the additional mappings that you want to set up.

7.  Close the **Keyboard mapping** form, and then close the **Keyboard mapping groups** form.

## Assign a keyboard mapping group to a register

1.  Click **Retail essentials** \> **Channels** \> **POS registers**.

2.  On the **POS registers** list page, select the POS register that you want to add the keyboard mapping group to.

3.  On the **Action Pane**, in the **Maintain** group, click **Edit**.

4.  In the **Key character** form, on the **General** tab, under **Profiles**, take note of the hardware profile number in the **Hardware profile** field.

5.  Click **Retail essentials** \> **Channels** \> **Setup** \> **POS** \> **Profiles** \> **Hardware profiles**.

6.  In the **POS hardware profile** form, select the hardware profile that you noted in step 4, and then on the **Keyboard** FastTab, in the **Keyboard mapping groups** field, select a keyboard mapping group.

## See also

[Setting up Retail POS (Retail essentials)](setting-up-retail-pos-retail-essentials.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

