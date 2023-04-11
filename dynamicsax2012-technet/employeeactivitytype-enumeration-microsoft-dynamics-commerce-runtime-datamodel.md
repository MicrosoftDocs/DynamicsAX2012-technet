---
title: EmployeeActivityType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EmployeeActivityType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivityType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.employeeactivitytype(v=AX.60)
ms:contentKeyID: 62208402
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivityType.FinishQuantity
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivityType.JobStart
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivityType.ClockOut
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivityType.TeamStop
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivityType.Logbook
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivityType.JobStop
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivityType.BreakCancelAll
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivityType.BreakFlowStart
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivityType.TeamStart
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivityType.BreakForLunch
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivityType.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivityType.ClockIn
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivityType
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivityType.BreakFlowStop
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivityType.BreakFromWork
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivityType.BreakCancelOne
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivityType.EventCode
dev_langs:
- CSharp
- C++
- VB
---

# EmployeeActivityType Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Time clock type which is mapped from AX enum "JmgTermRegType".

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Enumeration EmployeeActivityType
'Usage
Dim instance As EmployeeActivityType
```

``` csharp
public enum EmployeeActivityType
```

``` c++
public enum class EmployeeActivityType
```

## Members

<table>
<thead>
<tr class="header">
<th></th>
<th>Member name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td></td>
<td>None</td>
<td>If the employee activity type does not match.</td>
</tr>
<tr class="even">
<td></td>
<td>ClockIn</td>
<td>Employee punch in clock time.</td>
</tr>
<tr class="odd">
<td></td>
<td>JobStop</td>
<td>Employee Stop job.</td>
</tr>
<tr class="even">
<td></td>
<td>JobStart</td>
<td>Employee Start job.</td>
</tr>
<tr class="odd">
<td></td>
<td>TeamStop</td>
<td>Employee team stop assistance.</td>
</tr>
<tr class="even">
<td></td>
<td>TeamStart</td>
<td>Employee team start assistance.</td>
</tr>
<tr class="odd">
<td></td>
<td>BreakFlowStart</td>
<td>Employee takes a break (break starts at this time).</td>
</tr>
<tr class="even">
<td></td>
<td>BreakCancelOne</td>
<td>Cancel one break.</td>
</tr>
<tr class="odd">
<td></td>
<td>BreakCancelAll</td>
<td>Cancel all breaks.</td>
</tr>
<tr class="even">
<td></td>
<td>BreakFlowStop</td>
<td>Employee comes back to work after the break.</td>
</tr>
<tr class="odd">
<td></td>
<td>FinishQuantity</td>
<td>Quantity change.</td>
</tr>
<tr class="even">
<td></td>
<td>ClockOut</td>
<td>Employee clock's out after his shift is over.</td>
</tr>
<tr class="odd">
<td></td>
<td>EventCode</td>
<td>Time clock event code.</td>
</tr>
<tr class="even">
<td></td>
<td>BreakFromWork</td>
<td>Employee takes a break from work.</td>
</tr>
<tr class="odd">
<td></td>
<td>BreakForLunch</td>
<td>Employee takes a break for lunch.</td>
</tr>
<tr class="even">
<td></td>
<td>Logbook</td>
<td>Employee views the log book details.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

