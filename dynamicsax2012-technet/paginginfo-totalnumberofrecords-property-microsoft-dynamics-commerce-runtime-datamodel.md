---
title: PagingInfo.TotalNumberOfRecords Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TotalNumberOfRecords Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PagingInfo.TotalNumberOfRecords
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.paginginfo.totalnumberofrecords(v=AX.60)
ms:contentKeyID: 65319386
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PagingInfo.TotalNumberOfRecords
dev_langs:
- CSharp
- C++
- VB
---

# TotalNumberOfRecords Property

Gets or sets the total number of records.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property TotalNumberOfRecords As Integer
    Get
    Set
'Usage
Dim instance As PagingInfo
Dim value As Integer

value = instance.TotalNumberOfRecords

instance.TotalNumberOfRecords = value
```

``` csharp
public int TotalNumberOfRecords { get; set; }
```

``` c++
public:
property int TotalNumberOfRecords {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The total number of records.  

## See Also

#### Reference

[PagingInfo Class](paginginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

