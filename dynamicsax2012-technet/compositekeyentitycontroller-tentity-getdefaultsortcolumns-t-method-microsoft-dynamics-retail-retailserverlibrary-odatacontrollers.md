---
title: CompositeKeyEntityController(TEntity).GetDefaultSortColumns(T) Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetDefaultSortColumns(T) Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CompositeKeyEntityController`1.GetDefaultSortColumns``1
ms:mtpsurl: https://technet.microsoft.com/library/Dn737523(v=AX.60)
ms:contentKeyID: 62202235
author: Khairunj
ms.author: daxcpft
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CompositeKeyEntityController`1.GetDefaultSortColumns``1
dev_langs:
- CSharp
- C++
- VB
---

# GetDefaultSortColumns(T) Method

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
The array of sort columns.  

## See Also

#### Reference

[CompositeKeyEntityController\<TEntity\> Class](compositekeyentitycontroller-tentity-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

