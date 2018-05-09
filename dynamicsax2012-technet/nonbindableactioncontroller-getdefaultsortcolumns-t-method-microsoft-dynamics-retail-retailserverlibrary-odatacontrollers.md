---
title: NonBindableActionController.GetDefaultSortColumns(T) Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetDefaultSortColumns(T) Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetDefaultSortColumns``1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn738005(v=AX.60)
ms:contentKeyID: 62203210
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetDefaultSortColumns``1
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
The array of SortColumn column sorting options.  

## See Also

#### Reference

[NonBindableActionController Class](nonbindableactioncontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

