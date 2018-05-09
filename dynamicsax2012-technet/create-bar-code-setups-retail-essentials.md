---
title: Create bar code setups (Retail essentials)
TOCTitle: Create bar code setups (Retail essentials)
ms:assetid: 6fb3eac7-938f-4adb-9d6d-adc363eef2e6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn736893(v=AX.60)
ms:contentKeyID: 62200370
ms.date: 08/15/2014
mtps_version: v=AX.60
---

# Create bar code setups (Retail essentials) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to create setups for bar codes. A bar code setup is a kind of template composed of a bar code mask and information about the font and the number of characters in the bar code. After you create setups, you use them to create bar codes.

The following illustration shows how creating setups is part of the process of creating bar codes.

![Create bar code setups and bar codes](images/Dn736893.Createbarcodesetups(Retailessentials)(AX.60).png "Create bar code setups and bar codes")

  

To create bar code setups, follow these steps:

1.  Click **Retail essentials** \> **Inventory management** \> **Setup** \> **Bar codes and labels** \> **Bar code setup**.

2.  Press CTRL+N or click **New** to create a new setup for bar codes.

3.  In the **Bar code setup** field, type an ID for the setup, and then enter a description in the **Description** field.

4.  On the **General** FastTab, in the **Bar code type** field, select a standard type for the bar code.

5.  In the **Mask ID** field, select a mask for the bar code.

6.  In the **Font** and **Size** fields, select a font for the bar code, and type a size for the font.

7.  In the **Minimum length** and **Maximum length** fields, type the minimum and maximum number of characters that the bar code can contain.
    
    For example, a bar code of the EAN-8 type always contains eight characters when it is printed. Therefore, for an EAN-8 bar code, both the minimum length and the maximum length are 8. For a bar code that contains a fixed string of five characters plus a number from 1 to 100, the minimum length is 6, and the maximum length is 8.

8.  Complete steps 2 through 7 for every bar code setup that you want to create.


> [!NOTE]
> <P>In Retail essentials, the form that you use to complete this task includes a subset of the controls that are available for other configurations of Retail. If a topic about this form describes controls that you don't see, it may be because you’re using Retail essentials.</P>



## See also

[Setting up bar codes (Retail essentials)](setting-up-bar-codes-retail-essentials.md)

[Set up bar code masks (Retail essentials)](set-up-bar-code-masks-retail-essentials.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

