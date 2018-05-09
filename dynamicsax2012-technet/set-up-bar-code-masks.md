---
title: Set up bar code masks
TOCTitle: Set up bar code masks
ms:assetid: a15c1dc4-cb44-4a87-a2af-9582fe71d9f8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh597190(v=AX.60)
ms:contentKeyID: 39519257
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Set up bar code masks 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Use bar code masks to create and check bar codes, and to reduce bar code errors. You can set up masks for both standard bar codes and custom bar codes, which are also referred to as in-house bar codes. Bar code masks consist of an optional prefix and one or more segments.

## In-house bar code masks

When you set up custom bar code masks, you must know the requirements of the scanners that are used in your stores. Some scanners only validate bar codes that have a specific format and check digit.

When you create a bar code mask for an item that has variants, Microsoft Dynamics AX can generate the bar codes for each size, color, and style combination.

## Standard bar code masks

Bar codes often have a fixed structure. For example, the last digit of standard EAN bar codes is a modulus check digit. When a bar code is entered, Microsoft Dynamics AX checks the validity of the input. Microsoft Dynamics AX also calculates the check digit and converts the input to a standard EAN bar code, if these steps are required.

## Supported standards

Bar code masks can be based on any of the following bar code standards:

  - No bar code

  - EAN128/UCC128

  - Code 39

  - Interleaved 2 of 5

  - Code 128

  - UPC A

  - UPC E

  - EAN13

  - EAN8

  - PDF417

  - Maxicode

## Set up bar code masks

1.  Click **Retail** \> **Setup** \> **Bar codes and labels** \> **Bar code mask setup**.

2.  Press CTRL+N to create a new bar code mask.

3.  In the **Mask ID** field, type an ID number, and then, in the **Description** field, type a description.

4.  In the **Type** field, select the type of bar code mask.

5.  On the **General** FastTab, in the **Bar code standard** field, select the bar code standard for the mask.

6.  In the **Prefix** field, enter an optional prefix. For example, prefixes are often used to identify the manufacturer.

7.  On the **Bar code mask segment** FastTab, click **Add** to create a new segment, and then specify information about the segment.
    
    The **Length** field displays the total number of characters in the bar code mask, which is the sum of the characters in the segments and the prefix.

8.  Repeat step 7 for each additional segment that you must create.
    
    For example, a bar code mask that identifies the size, color, and style of a product might have the following segments.
    
    <table>
    <colgroup>
    <col style="width: 33%" />
    <col style="width: 33%" />
    <col style="width: 33%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p><strong>Segment number</strong></p></th>
    <th><p><strong>Type</strong></p></th>
    <th><p><strong>Length</strong></p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>1</p></td>
    <td><p><strong>Product</strong></p></td>
    <td><p>4</p></td>
    </tr>
    <tr class="even">
    <td><p>2</p></td>
    <td><p><strong>Size digit</strong></p></td>
    <td><p>2</p></td>
    </tr>
    <tr class="odd">
    <td><p>3</p></td>
    <td><p><strong>Color digit</strong></p></td>
    <td><p>2</p></td>
    </tr>
    <tr class="even">
    <td><p>4</p></td>
    <td><p><strong>Style digit</strong></p></td>
    <td><p>2</p></td>
    </tr>
    </tbody>
    </table>


## See also

[About setting up bar codes](about-setting-up-bar-codes.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

