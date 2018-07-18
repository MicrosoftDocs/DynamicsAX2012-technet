---
title: (ITA) Set up fiscal LIFO reporting groups
TOCTitle: (ITA) Set up fiscal LIFO reporting groups
ms:assetid: f5845043-bb55-4575-b3a9-518dd0da12df
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa551647(v=AX.60)
ms:contentKeyID: 36060001
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Italy
---

# (ITA) Set up fiscal LIFO reporting groups 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You must attach all items on the **Released products** list page to a fiscal Last in, First out (LIFO) reporting group to calculate fiscal LIFO. If there are items for which the calculation is to be omitted, you must specify that the fiscal LIFO calculation is not to be calculated for these items.

The normal value calculation is set up on the reporting group or on individual items. For more information, see [(ITA) Calculate fiscal LIFO journal lines](ita-calculate-fiscal-lifo-journal-lines.md).

The following criteria must be fulfilled to change the fiscal LIFO reporting group for an item:

  - The fiscal LIFO group of the item must be changed before the first annual municipal report that uses the fiscal LIFO reporting group is approved.

  - No items are available and no fiscal LIFO value remains in the fiscal LIFO reporting group or on the item for an individual item calculation.

Use the following procedures to create a fiscal LIFO reporting group, assign an item to a fiscal LIFO reporting group, and apply fiscal LIFO reporting groups for individual items.

## Create a fiscal LIFO reporting group

1.  Click **Inventory management** \> **Setup** \> **Inventory** \> **Fiscal LIFO reporting group**.

2.  Create a reporting group.

3.  In the **Fiscal LIFO reporting group** and **Name** fields, enter an ID and name for the fiscal LIFO reporting group.

4.  In the **Normal value calculation** field, select how fiscal LIFO is calculated for items in the current reporting group:
    
      - **Never** – The normal value is never calculated for this group.
    
      - **Manual** – The normal value that you enter in the **Normal value** field is applied as the value of items in the current group.
    
      - **Automatic** – The normal value is applied if the deviation percentage is exceeded. The normal value is then set to the average purchase price of items for the calculation period (month, quarter, or half year).
        

        > [!NOTE]
        > <P>You can set the deviation percentage in the <STRONG>Deviation percent</STRONG> field in the <STRONG>Inventory and warehouse management parameters</STRONG> form.</P>



5.  In the **Normal value** field, enter the value that should apply to items as their normal value when you select **Manual** in the **Normal value calculation** field.

6.  Close the form.

## Attach an item to a fiscal LIFO reporting group

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  Double-click an item to open the **Released product details** form.

3.  Click the **Manage costs** tab.

4.  In the **Fiscal LIFO reporting group** field, select a fiscal LIFO reporting group.

5.  Close the form.

## Reporting groups for items to be calculated individually

The fiscal LIFO calculation can be run for each item or for each group of items. You can set up LIFO reporting groups for independent items. Items that are attached to these reporting groups are calculated and displayed individually. If you set up more than one group for independent items, you can move items between these groups.

## Apply fiscal LIFO reporting groups for individual items

1.  Click **Inventory management** \> **Setup** \> **Inventory** \> **Fiscal LIFO reporting group**.

2.  Create a fiscal LIFO reporting group. For more information, see Create a fiscal LIFO reporting group.

3.  Select the **Individual** check box.
    

    > [!NOTE]
    > <P>All items that you add to this group are calculated and displayed individually.</P>



4.  Close the form.

## See also

[(ITA) About fiscal LIFO workflow](ita-about-fiscal-lifo-workflow.md)

  


