---
title: Change an item in formulas
TOCTitle: Change an item in formulas
ms:assetid: 2de8ed70-6aad-4441-91c7-a115e2a3328d
ms:mtpsurl: https://technet.microsoft.com/library/Hh352193(v=AX.60)
ms:contentKeyID: 36687826
author: tonyafehr
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- change formula item
- change formula line
- change item in a formula
- edit formula line
- replace a formula item
- replace item in a formula
audience: Application User
ms.search.region: Global
---

# Change an item in formulas 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use these procedures to add an item as a replacement in one or more formulas.

The item that you add as a replacement can replace:

  - One item in one formula.

  - One item in all formulas or a series of formulas.

  - One item in one or more formulas for a specified period.


> [!NOTE]
> <P>To make sure that the replacement you are about to perform applies to the correct formula lines, click <STRONG>Edit formula lines</STRONG> in the <STRONG>Change formula item</STRONG> form. To change the formula line selection, click <STRONG>Select</STRONG> and change the criteria.</P>



## Replace one item in one formula

1.  Click **Inventory management** \> **Periodic** \> **Formulas** \> **Change formula item**.

2.  In the **To item number** field, select the item that you want to add as a replacement.

3.  Click **Select** to select the item that you want to replace.

4.  In the **Update lines** field, select **Overwrite**.

## Replace one item in all formulas or a series of formulas

1.  Click **Inventory management** \> **Periodic** \> **Formulas** \> **Change formula item**.

2.  In the **To item number** field, select the item that you want to add as a replacement.

3.  In the **Update lines** field, select **Overwrite**.
    

    > [!NOTE]
    > <P>When you perform the two first steps in this procedure, you perform a replacement in all existing formulas. To limit the replacement to a series of formulas, proceed to the next step.</P>



4.  Click **Select** and limit the criteria to the formulas where you want to perform the replacement.

## Replace one item for a specified period

1.  Click **Inventory management** \> **Periodic** \> **Formulas** \> **Change formula item**.

2.  In the **To item number** field, select the item that you want to add as a replacement.

3.  Click **Select** to select the item that you want to replace.

4.  In the **Update lines** field, select **Append**.

5.  In the **Formula line applies to this date** field, select the date through when the new formula item is valid.

6.  In the **Formula line applies as of this date** field, select the date when the replacement item becomes valid.

## See also

[Change formula item (form)](https://technet.microsoft.com/library/hh209311\(v=ax.60\))

  


