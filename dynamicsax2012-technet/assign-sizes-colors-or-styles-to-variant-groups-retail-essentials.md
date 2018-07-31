---
title: Assign sizes, colors, or styles to variant groups (Retail essentials)
TOCTitle: Assign sizes, colors, or styles to variant groups (Retail essentials)
ms:assetid: ed117685-0507-4477-88c3-884d8cad5f2e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn736972(v=AX.60)
ms:contentKeyID: 62200449
ms.date: 11/13/2014
mtps_version: v=AX.60
---

# Assign sizes, colors, or styles to variant groups (Retail essentials) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up variant groups for sizes, colors, and styles, and then assign the groups to retail products. Variant groups let you identify the different options in which a product is available. For example, you can create a size group that is named **Men's Shoes**, and then assign specific sizes to this group.

1.  Click **Retail essentials** \> **Merchandising** \> **Setup** \> **Variant groups** \> **Size groups**.
    
    –or–
    
    Click **Retail essentials** \> **Merchandising** \> **Setup** \> **Variant groups** \> **Color groups**.
    
    –or–
    
    Click **Retail essentials** \> **Merchandising** \> **Setup** \> **Variant groups** \> **Style groups**.

2.  In the form, click **New** to create a new group.

3.  In the **Size group**, **Color group**, or **Style group** field, type an identification number for the group.

4.  In the **Description** field, type a description of the group.

5.  Click **Sizes**, **Colors**, or **Styles**.

6.  Click **New** to create a new record.

7.  In the **Size**, **Color**, or **Style** field, select a size, color, or style.
    
    The **Name** field displays the name of the size, color, or style.
    
    You can also enter values to create a new size, color, or style.

8.  In the **Replenishment weight** field, specify how many of this variant are replenished relative to the other variants. For example, you can order three medium-sized shirts for every small-sized and large-sized shirt.

9.  In the **Number in bar code** field, type the number that is automatically assigned to the group when bar codes are created for variants.
    
    Or, you can click **Auto number bar code** to automatically enter sequential numbers in the **Number in bar code** field.

10. To display the sizes, colors, or styles in an order other than alphabetical or numerical order in lists, enter numbers in the **Display order** field.
    
    For example, to display the sizes *Small*, *Medium*, and *Large* in that order, enter **1** for Small, **2** for Medium, and **3** for Large.

11. In the corresponding **Groups** form, click **Copy** to copy a selected row. Enter a unique name for the new row. The row description and any sizes, colors, or styles that are assigned to the selected row are also copied.

12. When you are prompted to update all items in the group, click **Yes**.


> [!NOTE]
> <P>In Retail essentials, the form that you use to complete this task includes a subset of the controls that are available for other configurations of Retail. If a topic about this form describes controls that you don't see, it may be because you’re using Retail essentials.</P>



## See also

[Product variants (Retail essentials)](product-variants-retail-essentials.md)

[Set up sizes, colors, and styles (Retail essentials)](set-up-sizes-colors-and-styles-retail-essentials.md)

  


