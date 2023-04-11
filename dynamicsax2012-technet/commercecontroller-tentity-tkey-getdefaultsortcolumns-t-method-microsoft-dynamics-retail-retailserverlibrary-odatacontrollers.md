---
title: CommerceController(TEntity, TKey).GetDefaultSortColumns(T) Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetDefaultSortColumns(T) Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CommerceController`2.GetDefaultSortColumns``1
ms:mtpsurl: https://technet.microsoft.com/library/Dn716580(v=AX.60)
ms:contentKeyID: 62203096
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CommerceController`2.GetDefaultSortColumns``1
dev_langs:
- CSharp
- C++
- VB
---

# GetDefaultSortColumns(T) Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the default sort column array.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Protected Overridable Function GetDefaultSortColumns(Of T As Class) As SortColumn()
'Usage
Dim returnValue As SortColumn()

returnValue = Me.GetDefaultSortColumns()
```

``` csharp
protected virtual SortColumn[] GetDefaultSortColumns<T>()
where T : class
```

``` c++
protected:
generic<typename T>
where T : ref class
virtual array<SortColumn^>^ GetDefaultSortColumns()
```

#### Type Parameters

  - T

#### Return Value

Type: SortColumn\[\]  
The SortColumn array of the column's sort order.  

## See Also

#### Reference

[CommerceController\<TEntity, TKey\> Class](commercecontroller-tentity-tkey-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

