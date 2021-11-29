---
title: PagingInfo.CalculateRecordCount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CalculateRecordCount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PagingInfo.CalculateRecordCount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.paginginfo.calculaterecordcount(v=AX.60)
ms:contentKeyID: 65315511
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PagingInfo.CalculateRecordCount
dev_langs:
- CSharp
- C++
- VB
---

# CalculateRecordCount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether to calculate the total number of records in the query.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property CalculateRecordCount As Boolean
    Get
    Set
'Usage
Dim instance As PagingInfo
Dim value As Boolean

value = instance.CalculateRecordCount

instance.CalculateRecordCount = value
```

``` csharp
public bool CalculateRecordCount { get; set; }
```

``` c++
public:
property bool CalculateRecordCount {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
If true the record count should be calculated; otherwise, false.  

## See Also

#### Reference

[PagingInfo Class](paginginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

