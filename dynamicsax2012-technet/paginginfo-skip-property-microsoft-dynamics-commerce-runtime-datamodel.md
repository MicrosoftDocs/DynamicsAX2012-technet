---
title: PagingInfo.Skip Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Skip Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PagingInfo.Skip
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.paginginfo.skip(v=AX.60)
ms:contentKeyID: 65320213
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PagingInfo.Skip
dev_langs:
- CSharp
- C++
- VB
---

# Skip Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the number of rows to be skipped.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Skip As Integer
    Get
    Set
'Usage
Dim instance As PagingInfo
Dim value As Integer

value = instance.Skip

instance.Skip = value
```

``` csharp
[DataMemberAttribute]
public int Skip { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int Skip {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The number of rows to be skipped.  

## See Also

#### Reference

[PagingInfo Class](paginginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

