---
title: 'Example: Use reduction keys'
TOCTitle: 'Example: Use reduction keys'
ms:assetid: 8bb788fb-cf70-4d5c-b3c0-da747d0c4bba
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa498254(v=AX.60)
ms:contentKeyID: 36058474
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- consume forecast
- forecast consumption
- reduce forecast
- forecast reduction
audience: Application User
ms.search.region: Global
---

# Example: Use reduction keys 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use a reduction key to define how to reduce forecast requirements. Here are some examples that show how to set up a reduction key, the different reduction key settings, and the results.

**Example 1**

Using the forecast reduction principle **Percent - reduction key**

This example shows how a reduction key reduces demand forecast requirements according to the percentages and periods that are defined by the reduction key. Set up the following lines in the **Reduction keys** form:

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Change</p></th>
<th><p>Unit</p></th>
<th><p>Percent</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>1</p></td>
<td><p>Month</p></td>
<td><p>100</p></td>
</tr>
<tr class="even">
<td><p>2</p></td>
<td><p>Month</p></td>
<td><p>75</p></td>
</tr>
<tr class="odd">
<td><p>3</p></td>
<td><p>Month</p></td>
<td><p>50</p></td>
</tr>
<tr class="even">
<td><p>4</p></td>
<td><p>Month</p></td>
<td><p>25</p></td>
</tr>
</tbody>
</table>


  - Link the reduction key to the item's coverage group.

  - Select **Percent - reduction key** in the **Reduction principle** field in the **Master plans** form.

  - Create a demand forecast of 1000 pieces per month.

If you run forecast scheduling on January 1, the demand forecast requirements are consumed according to the percentages that are specified earlier in this section. The following requirement quantities are transferred to the master plan:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Month</p></th>
<th><p>Number of pieces required</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>January</p></td>
<td><p>0</p></td>
</tr>
<tr class="even">
<td><p>February</p></td>
<td><p>250</p></td>
</tr>
<tr class="odd">
<td><p>March</p></td>
<td><p>500</p></td>
</tr>
<tr class="even">
<td><p>April</p></td>
<td><p>750</p></td>
</tr>
<tr class="odd">
<td><p>May - December</p></td>
<td><p>1000</p></td>
</tr>
</tbody>
</table>


**Example 2**

Using the forecast reduction principle **Transactions - reduction key**

This example shows how actual orders, which occur during the periods that are defined by the reduction key, reduce demand forecast requirements.

  - Select **Transactions - reduction key** in the **Reduction principle** field in the **Master plans** form.

  - The following sales orders exist on January 1:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Month</p></th>
<th><p>Number of pieces ordered</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>January</p></td>
<td><p>956</p></td>
</tr>
<tr class="even">
<td><p>February</p></td>
<td><p>1176</p></td>
</tr>
<tr class="odd">
<td><p>March</p></td>
<td><p>451</p></td>
</tr>
<tr class="even">
<td><p>April</p></td>
<td><p>119</p></td>
</tr>
</tbody>
</table>


Using the same demand forecast of 1000 pieces per month, the following requirement quantities are transferred to the master plan:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Month</p></th>
<th><p>Number of pieces required</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>January</p></td>
<td><p>44</p></td>
</tr>
<tr class="even">
<td><p>February</p></td>
<td><p>0</p></td>
</tr>
<tr class="odd">
<td><p>March</p></td>
<td><p>549</p></td>
</tr>
<tr class="even">
<td><p>April</p></td>
<td><p>881</p></td>
</tr>
<tr class="odd">
<td><p>May - December</p></td>
<td><p>1000</p></td>
</tr>
</tbody>
</table>


## See also

[Reduction keys (form)](https://technet.microsoft.com/en-us/library/aa553816\(v=ax.60\))

[Create and use a reduction key](create-and-use-a-reduction-key.md)

  


