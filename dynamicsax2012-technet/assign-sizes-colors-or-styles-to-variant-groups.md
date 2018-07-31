---
title: Assign sizes, colors, or styles to variant groups
TOCTitle: Assign sizes, colors, or styles to variant groups
ms:assetid: 34945800-f636-4dd7-ae8b-d19a44f9daa3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh580605(v=AX.60)
ms:contentKeyID: 39519091
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Assign sizes, colors, or styles to variant groups 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Set up variant groups for sizes, colors, and styles, and then assign the groups to retail products. Variant groups let you identify the different options in which a product is available. For example, you can create a size group that is named **Men's Shoes**, and then assign specific sizes to this group.

1.  Click **Retail** \> **Setup** \> **Variant groups** \> **Size groups**.
    
    –or–
    
    Click **Retail** \> **Setup** \> **Variant groups** \> **Color groups**.
    
    –or–
    
    Click **Retail** \> **Setup** \> **Variant groups** \> **Style groups**.

2.  In the form, click **New** to create a new group.

3.  In the **Size group**, **Color group**, or **Style group** field, type an ID number for the group.

4.  In the **Description** field, type a description of the group.

5.  Click **Sizes**, **Colors**, or **Styles**.

6.  Click **New** to create a new record.

7.  In the **Size**, **Color**, or **Style** field, select a size, color, or style.
    
    The **Name** field displays the name of the size, color, or style.
    
    In Microsoft Dynamics AX 2012 R2, you can also enter values to create a new size, color, or style.

8.  In the **Replenishment weight** field, specify how many of this variant are replenished relative to the other variants. For example, you can order three medium-sized shirts for every small-sized and large-sized shirt.

9.  In the **Number in bar code** field, type the number that is automatically assigned to the group when bar codes are created for variants.
    
    In Microsoft Dynamics AX 2012 R2, you can click **Auto number bar code** to automatically enter sequential numbers in the **Number in bar code** field.

10. In Microsoft Dynamics AX 2012 R2, to display the sizes, colors, or styles in an order other than alphabetical or numerical order in lists, enter numbers in the **Display order** field.
    
    For example, to display the sizes *Small*, *Medium*, and *Large* in that order, enter **1** for Small, **2** for Medium, and **3** for Large.

11. Depending on your version of the program, follow one of these steps:
    
      - In Microsoft Dynamics AX 2012 R2: Click **Copy** to copy a selected row. Enter a unique name for the new row. The row description and any sizes, colors, or styles that are assigned to the selected row are also copied.
    
      - In other versions of Microsoft Dynamics AX: Repeat steps 6 through 9 to add other sizes, colors, or styles to the group, and then close the form.

12. When you are prompted to update all items in the group, click **Yes**.

## See also

[About variants](about-variants.md)

[Size groups (form)](https://technet.microsoft.com/en-us/library/hh597326\(v=ax.60\))

[Color groups (form)](https://technet.microsoft.com/en-us/library/hh597230\(v=ax.60\))

[Style groups (form)](https://technet.microsoft.com/en-us/library/hh597260\(v=ax.60\))

  


