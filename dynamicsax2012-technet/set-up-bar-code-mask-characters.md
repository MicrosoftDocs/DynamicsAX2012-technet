---
title: Set up bar code mask characters
TOCTitle: Set up bar code mask characters
ms:assetid: 05b719a0-1828-40bb-b2df-eed5de6f9323
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh580559(v=AX.60)
ms:contentKeyID: 39519035
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up bar code mask characters 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Bar code mask characters are alphabetical characters that are replaced with numbers when Microsoft Dynamics AX uses a bar code mask to generate a bar code. Use different bar code mask characters to generate different types of bar codes, such as bar codes for products, customers, or employees. A single mask character, such as a mask character that represents the item number, can add several characters to the bar code.


> [!NOTE]
> <P>If you create all your bar codes manually, you do not have to set up mask characters or masks. If you manually create a bar code for a product for which a bar code mask is set up, mask validation is performed only for the check digit. If the check digit does not match the check digit in the bar code mask, you receive an error message that resembles the following message:</P>
> <P>"Expecting check digit 8 but found 3."</P>



1.  Click **Retail** \> **Setup** \> **Bar codes and labels** \> **Mask characters**.

2.  Press CTRL+N to create a new bar code mask character.

3.  In the **Type** field, select the type of mask character. Then, in the **Character** field, type a character between A and Z.

4.  In the **Description** field, type a description of the mask character.

## See also

[About setting up bar codes](about-setting-up-bar-codes.md)

  


