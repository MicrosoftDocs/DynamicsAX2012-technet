---
title: (RUS) Set up the item relation to working clothes and special rigging
TOCTitle: (RUS) Set up the item relation to working clothes and special rigging
ms:assetid: cd3a8ace-27ca-4c56-8946-d0629eeb74ed
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ853225(v=AX.60)
ms:contentKeyID: 50396505
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up the item relation to working clothes and special rigging 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to relate an item or an item group to a fixed asset (FA) group. You can use the following forms to set up an item relation with a fixed asset group:

  - **Conditions for FA group definition** – Set up a period when the item relation is valid, and set up the maximum and minimum cost limits and the service life period for the item.

  - **Item relation with FA group** – Map the item to a fixed asset group.

  - **Copy item relations with FA group** – Copy the conditions for the item relation from an existing item relation.

<!-- end list -->

1.  Click **Fixed assets (Russia)** \> **Setup** \> **Working clothes/Special riggings/NVFA** \> **Identification of FA group**.

2.  Click **New** to create a new condition.

3.  In the **Start date** field, select the starting date from which the item relation is effective.

4.  In the **End date** field, select the date until which the item relation is effective.

5.  In the **Cost from** field, enter the minimum limit for the cost price of the item.

6.  In the **Cost to** field, enter the maximum limit for the cost price of the item.

7.  In the **Service life from** field, enter the minimum service life for the item.

8.  In the **Service life till** field, enter the maximum service life for the item.

9.  Click **Compliance**.

10. In the **Item relation** field, select the item relation that has a fixed asset group, from the following options:
    
      - **Table** – Map a selected item to the fixed asset group.
    
      - **Group** – Map a selected item group to the fixed asset group.
    
      - **All** – Map all items to the fixed asset group.

11. In the **Item** field, select the item or the item group.

12. In the **FA group** field, select the fixed asset group.

13. Close the form.

14. Click **Copy** to open the **Copy item relations with FA group** form. You can also copy the conditions for the item relation from an existing item relation.

15. In the **Start date** field, select the starting date of the period for which item relations are copied.

16. Click **OK** to copy the item relations with fixed asset groups.

## See also

[(RUS) About NVFAs, working clothes, and special rigging accounting](rus-about-nvfas-working-clothes-and-special-rigging-accounting.md)

  


