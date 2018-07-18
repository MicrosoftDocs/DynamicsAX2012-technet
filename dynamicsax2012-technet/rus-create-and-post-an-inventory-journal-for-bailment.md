---
title: (RUS) Create and post an inventory journal for bailment
TOCTitle: (RUS) Create and post an inventory journal for bailment
ms:assetid: fdbe4172-ba0e-475d-88a9-50c431467c3a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ853246(v=AX.60)
ms:contentKeyID: 50396526
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Create and post an inventory journal for bailment 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Counting** form to create and post an inventory counting journal for an item that is stored in a warehouse.

1.  Click **Inventory management** \> **Journals** \> **Item counting** \> **Counting**.

2.  Press CTRL+N to open the **Dimensions display** form.

3.  Select the **Inventory profile**, **Owner**, and **Batch number** check boxes to activate these dimensions for the journal. Then click **OK** to create a new inventory counting journal.

4.  Close the form.

5.  In the **Counting** form, in the **Name** field, select an inventory journal name.

6.  Click **Lines** to open the **Journal lines, inventory** form and create journal lines. For more information, see [Journal lines, Inventory count (form)](https://technet.microsoft.com/en-us/library/aa599389\(v=ax.60\)).

7.  In the **Item number** field, select the item number of the item that is stored in the warehouse.

8.  On the **Inventory dimensions** tab, in the **Site** field, select the location of the warehouse that the item is stored in. In the **Warehouse** field, select the name of the warehouse.
    

    > [!NOTE]
    > <P>The <STRONG>Batch number</STRONG> field displays the batch number that the item that is stored in the warehouse is assigned to.</P>



9.  In the **Inventory profile** field, select the inventory profile for bailment.

10. In the **Owner** field, select the owner of the item that is stored in the warehouse.

11. Click **Validate** to validate the journal, and then click **Post** to post the journal.

## See also

[(RUS) Generate the Counting list (INV-5) report](rus-generate-the-counting-list-inv-5-report.md)

  


