---
title: SortingInfo.Columns Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Columns Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SortingInfo.Columns
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.sortinginfo.columns(v=AX.60)
ms:contentKeyID: 65321581
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SortingInfo.Columns
dev_langs:
- CSharp
- C++
- VB
---

# Columns Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the column collection to be sorted.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Columns As IEnumerable(Of SortColumn)
    Get
    Set
'Usage
Dim instance As SortingInfo
Dim value As IEnumerable(Of SortColumn)

value = instance.Columns

instance.Columns = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<SortColumn> Columns { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<SortColumn^>^ Columns {
    IEnumerable<SortColumn^>^ get ();
    void set (IEnumerable<SortColumn^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SortColumn](sortcolumn-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[SortingInfo Class](sortinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

