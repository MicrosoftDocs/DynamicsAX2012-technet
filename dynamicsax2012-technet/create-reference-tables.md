---
title: Create reference tables
TOCTitle: Create reference tables
ms:assetid: 0f44d083-b957-45b2-a444-9e22d7acfd82
ms:mtpsurl: https://technet.microsoft.com/library/Aa496419(v=AX.60)
ms:contentKeyID: 36056019
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create reference tables 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Reference tables are used as the basis for calculations for the distribution or allocation of costs or quantities. Reference tables are typically used when references are fixed for several periods. Examples of reference tables are square meters, headcount, equipment calculation, and so on.

1.  Click **Cost accounting** \> **Setup** \> **Calculation** \> **Reference tables**.

2.  Press CTRL+N to create a new line.

3.  In the **Reference table** field, enter a name for the reference table.

4.  On the **General** tab, select the dimensions that you want to use in this reference table.

5.  Click **Cost accounting** \> **Setup** \> **Calculation** \> **Calculation versions**.

6.  Click **Reference table** to open the **Reference table values** form.

7.  On the **Overview** tab, in the list of created reference tables, click the reference table that you created in the **Reference tables** form.

8.  On the **General** tab, select the dimensions that you want to enter the references for, and then enter the total reference quantity in the **Reference quantity** field.

9.  Enter the reference quantity for each dimension that you want to allocate.

10. Confirm that the value in the **Difference** field is 0 (zero).

## Example

The most common example of a reference table is the cost center building. Here, the costs are allocated by square meters, as shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Description</p></th>
<th><p>Square meters</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Total quantity of square meters</p></td>
<td><p>2000 m2</p></td>
</tr>
<tr class="even">
<td><p>Square meters used by the cost center's stock</p></td>
<td><p>500 m2</p></td>
</tr>
<tr class="odd">
<td><p>Square meters used by the cost center's production 1</p></td>
<td><p>500 m2</p></td>
</tr>
<tr class="even">
<td><p>Square meters used by the cost center's production 2</p></td>
<td><p>750 m2</p></td>
</tr>
<tr class="odd">
<td><p>Square meters used by the cost center's administration</p></td>
<td><p>250 m2</p></td>
</tr>
</tbody>
</table>


If the total costs on the cost center building are USD 1,000, the period calculation will allocate USD 250 to the cost center's stock, USD 250 to the production 1, and so on.

## See also

[Reference tables (form)](https://technet.microsoft.com/library/aa591454\(v=ax.60\))

  


