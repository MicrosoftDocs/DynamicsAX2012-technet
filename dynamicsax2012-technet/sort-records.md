---
title: Sort records
TOCTitle: Sort records
ms:assetid: c9609a3d-25cc-4a5e-8b37-003bee139d6d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa550879(v=AX.60)
ms:contentKeyID: 43894518
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Sort records 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In forms where the records are listed in a grid, you can sort data in ascending order (A through Z) or descending order (Z through A).

## Sort by one field

You can sort data by using a single criterion. For example, you can sort the items in the Product table according to the product type instead of the product name, which is the default sorting setting.

1.  Select any field in the column to sort by.

2.  Right-click on the column to sort, and then select either **Sort ascending** or **Sort descending**.


> [!TIP]
> <P>You can also sort data by clicking the column header in the table. Click the header again to reverse the sort order.</P>



## Sort by more than one field

You can use Advanced sorting to sort by more than one field. For example, you can sort the customers in the **Customers** table first by **Customer group** and then by **Name**.

1.  Click **File** \> **Edit** \> **Filter** \> **Advanced Filter/Sort**.

2.  Click the **Sorting** tab.

3.  Press CTRL+N to add a new line.

4.  In the **Table** column, select the table that contains the field to sort.

5.  In the **Field** column, select a sorting field.

6.  In the **Search direction** field, select **Ascending** or **Descending**.

7.  Repeat steps 3 through 7 to add more sorting criteria.

8.  Select a sorting criteria row and then click the **Up** or **Down** buttons to change the sort order.

## See also

[Find records](find-records.md)

[Filter records](filter-records.md)

  


