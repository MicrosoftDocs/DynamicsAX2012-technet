---
title: (EEUR) About rounding off depreciation amounts
TOCTitle: (EEUR) About rounding off depreciation amounts
ms:assetid: 5c00947d-c86b-460c-940d-9167f2471342
ms:mtpsurl: https://technet.microsoft.com/library/JJ710715(v=AX.60)
ms:contentKeyID: 49385112
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- depreciation
- round off
- round off depreciation
audience: Application User
ms.search.region: Czech Republic, Estonia, Hungary, Latvia, Lithuania, Poland, Russia
---

# (EEUR) About rounding off depreciation amounts 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can round fixed asset depreciation amounts up or down to the nearest whole number. Depreciation amounts are rounded up or down based on the value that is entered in the **Round off depreciation** field and the rounding method specified in the **Rounding method** field in the **Depreciation books** form.

For a depreciation amount (x) with a round off depreciation value (y), the depreciation amount (z) is calculated as x/y. The rounded up or rounded down depreciation amount is calculated as z \* y. For example, for depreciation amount CZK 1111.11 and round off depreciation value 1, the depreciation amount is CZK 1111.11/1, which is CZK 1111.11. The rounded up depreciation amount is calculated as CZK 1112 \* 1, which is CZK 1112. The rounded down depreciation amount is calculated as CZK 1111 \* 1, which is CZK 1111.

The following table shows rounded up and rounded down depreciation amounts for various depreciation amounts and round off depreciation values.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th> <p>
   
	 Depreciation amount (x)
  </p> </th>
    <th> <p>
   
	 Round off depreciation (y)
  </p> </th>
    <th> <p>
   
	 Depreciation amount (z = x/y))
  </p> </th>
    <th colspan="3"> <p>
   
	 Rounding method
  </p> </th>
  </tr>
  <tr>
    <td> <p></p> </td>
    <td> <p></p> </td>
    <td> <p></p> </td>
    <td> <p>
   
	 Normal
  </p> </td>
    <td> <p>
   
	 Downward
  </p> </td>
    <td> <p>
   
	 Rounding-up
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 CZK 1111.11
  </p> </td>
    <td> <p>
   
	 1
  </p> </td>
    <td> <p>
   
	 CZK 1111.11/1 = CZK 1111.11
  </p> </td>
    <td> <p>
   
	 CZK 1111.1
  </p> </td>
    <td> <p>
   
	 CZK 1111.11 is rounded up to CZK 1112.
  </p> <p>
   
	 Final depreciation amount: CZK 1112 * 1 = CZK 1112
  </p> </td>
    <td> <p>
   
	 CZK 1111.11 is rounded down to CZK 1111.
  </p> <p>
   
	 Final depreciation amount: CZK 1111 * 1 = CZK 1111.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 CZK 1234.5
  </p> </td>
    <td> <p>
   
	 10
  </p> </td>
    <td> <p>
   
	 CZK 1234.5/10 = 123.45
  </p> </td>
    <td> <p>
   
	 CZK 1235
  </p> </td>
    <td> <p>
   
	 CZK 123.45 is rounded up to CZK 124. 
  </p> <p>
   
	 Final depreciation amount: CZK 124 * 10 = CZK 1240
  </p> </td>
    <td> <p>
   
	 CZK 123.45 is rounded down to CZK 123. 
  </p> <p>
   
	 Final depreciation amount: CZK 123 * 10 = CZK 1230
  </p> </td>
  </tr>
</table>


## See also

[(EEUR) Depreciation books setup (modified form)](https://technet.microsoft.com/library/jj710730\(v=ax.60\))

  


