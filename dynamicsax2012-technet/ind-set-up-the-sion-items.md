---
title: (IND) Set up the SION items
TOCTitle: (IND) Set up the SION items
ms:assetid: 7aaaaad3-d2cc-473d-9d3c-893db81850e7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677954(v=AX.60)
ms:contentKeyID: 49385917
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (IND)
- india
- set up SION
- SION items form
audience: Application User
ms.search.region: India
---

# (IND) Set up the SION items 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

As part of setting up Standard Input Output Norms (SION), you can assign input items to the SION. The input items are used in finished products that qualify for the SION.

Input items are added to a bill of materials (BOM) for a finished product. By default, when you assign a BOM to the SION, all the items that you include in the BOM are displayed in the SION items list. You can add or delete BOM items in the SION items list after you assign the BOM to the SION.

When the quantity of input items under an Advance Authorization (AA) incentive scheme is determined from the quantity of a SION input item, the importable items are related items. For example, an exporter manufactures item A as a finished product from imported raw materials B and C. For every unit of item B, the exporter imports two units of item C. In the SION, item B is the input item and item C is the related item. For more information, see [(IND) Related items (form)](https://technet.microsoft.com/en-us/library/jj664922\(v=ax.60\)).

Use this procedure to select the input goods that are used for a finished product.

1.  Click **Inventory management** \> **Setup** \> **EXIM** \> **SION**. Create a product group, and then enter the applicable BOM number

2.  To add a BOM to an existing product group, select the product group, and then on the **Lines** FastTab, click any BOM. Press Ctrl+N. For more information about how to set up the SION, see [(IND) Set up the SION](ind-set-up-the-sion.md).

3.  In the **SION** form, on the **Lines** FastTab, click **SION Items**.

4.  In the **SION Items** form, the items in the selected BOM are displayed. The **Item number**, **Product name**, **Unit**, and **Quantity** fields are filled in automatically from the values in the BOM.

5.  In the left pane, select an item.

6.  In the **Quantity** field, enter or modify the turnover quantity. The turnover quantity is the total number of units of raw material that will be used in the finished product.
    

    > [!IMPORTANT]
    > <P>You cannot modify this field after you create the SION items.</P>



7.  In the **Basis** field, select the basis that you want to use when calculating the allowed quantity. Select from the following options:
    
      - **Net/Net+pct.** – The quantity is calculated as a percentage of the quantity of the input item.
    
      - **Pct. of FOB** – The quantity is calculated as a percentage of the quantity of the finished goods.
    
      - **Pct. of input** – The quantity is calculated as a percentage of the value of the input item.
    
      - **Standard quantity** – The quantity is a specific quantity.
    
      - **Value** – The quantity of the related item is calculated as a percentage of the value of the finished goods.

8.  In the **Value** field, enter a value for the selected basis. If you selected **Net/Net+pct.** or **Pct. of FOB** in the **Basis** field, the **Value** field is a percentage.
    
    For a **Net/Net+pct.** basis, the percentage in the **Value** field cannot exceed 100. For a **Pct. of FOB** basis, the calculated percentage must be a positive value.
    
    If you selected **Pct. of input** or **Standard quantity** in the **Basis** field, the **Value** field for the record cannot be modified.

9.  The quantity of the item that you can import duty-free is displayed in the **Allowed quantity** field. The quantity is calculated from the information that you entered in the **Basis** and **Value** fields:
    
      - If you select **Net/Net+pct.** in the **Basis** field, the quantity is calculated as Quantity + (Quantity \* Value/100)
    
      - If the **Value** field contains a negative value, the **Allowed quantity** is calculated as Quantity – (Quantity \* Value/100).
    
      - If you selected **Pct. of FOB** or **Value** in the **Basis** field, the value that you entered in the **Quantity** field is displayed in the **Allowed quantity** field for the item.

10. In the **Item number** field, select the identification number of the item that is used in the finished product.

11. Select the **Apply restriction** check box to indicate that the value in the **Allowed quantity** field for the SION item is restricted to a percentage of the input item.

12. In the **Restricted pct.** field, enter the restricted percentage to apply to the allowed quantity. Enter the percentage as a whole number between 0 and 100. The **Restricted pct.** field is available only if you selected the **Apply restriction** check box for an item.
    
    The quantity of the item, after you apply the restricted percentage, is displayed in the **Restricted allowed quantity** field.

13. In the **SION Items** form, click **Standard quantity** to open the **Standard quantity** form, where you can enter information to use to calculate the quantity of a SION item. The **Standard quantity** button is available only if you selected **Standard quantity** in the **Basis** field.
    
    The calculated quantity of the SION item is displayed in the **Allowed quantity** field and in the **Restricted allowed quantity** field, if applicable, in the **SION Items** form.

14. When you modify the values for an item, click **Update** to recalculate the values for the item in the **Allowed quantity** field and in the **Restricted allowed quantity** field.

## See also

[(IND) Setting up SION in Inventory management](ind-setting-up-sion-in-inventory-management.md)

[(IND) SION (form)](https://technet.microsoft.com/en-us/library/jj710966\(v=ax.60\))

[(IND) SION items (form)](https://technet.microsoft.com/en-us/library/jj664548\(v=ax.60\))

[(IND) Related items (form)](https://technet.microsoft.com/en-us/library/jj664922\(v=ax.60\))

  


