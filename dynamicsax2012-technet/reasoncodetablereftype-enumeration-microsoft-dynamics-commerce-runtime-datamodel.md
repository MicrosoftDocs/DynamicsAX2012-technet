---
title: ReasonCodeTableRefType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReasonCodeTableRefType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeTableRefType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncodetablereftype(v=AX.60)
ms:contentKeyID: 62213781
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeTableRefType.CreditCard
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeTableRefType
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeTableRefType.Affiliation
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeTableRefType.HierarchyTable
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeTableRefType.Customer
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeTableRefType.ItemDepartment
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeTableRefType.Tender
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeTableRefType.ItemGroup
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeTableRefType.Item
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeTableRefType.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeTableRefType.IncomeExpense
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeTableRefType.InventTable
dev_langs:
- CSharp
- C++
- VB
---

# ReasonCodeTableRefType Enumeration

Table reference type. Maps to RBOInfocodeRefTAbleIdBase enum in AX.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration ReasonCodeTableRefType
'Usage
Dim instance As ReasonCodeTableRefType
```

``` csharp
[DataContractAttribute]
public enum ReasonCodeTableRefType
```

``` c++
[DataContractAttribute]
public enum class ReasonCodeTableRefType
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
<td>No type = 0.</td>
</tr>
<tr class="even">
<td></td>
<td>Item</td>
<td>INVENTTABLE = 1.</td>
</tr>
<tr class="odd">
<td></td>
<td>Customer</td>
<td>RETAILCUSTTABLE = 2.</td>
</tr>
<tr class="even">
<td></td>
<td>Tender</td>
<td>RETAILSTORETENDERTYPETABLE = 3.</td>
</tr>
<tr class="odd">
<td></td>
<td>CreditCard</td>
<td>RETAILSTORETENDERTYPECARDTABLE = 4.</td>
</tr>
<tr class="even">
<td></td>
<td>IncomeExpense</td>
<td>RETAILINCOMEEXPENSEACCOUNTTABLE = 5.</td>
</tr>
<tr class="odd">
<td></td>
<td>ItemDepartment</td>
<td>RETAILINVENTITEMDEPARTMENT = 6.</td>
</tr>
<tr class="even">
<td></td>
<td>ItemGroup</td>
<td>RboInventItemGroup = 7.</td>
</tr>
<tr class="odd">
<td></td>
<td>HierarchyTable</td>
<td>RBOHierarchyTable = 8.</td>
</tr>
<tr class="even">
<td></td>
<td>InventTable</td>
<td>InventTable = 9.</td>
</tr>
<tr class="odd">
<td></td>
<td>Affiliation</td>
<td>RetailAffiliation = 10.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

