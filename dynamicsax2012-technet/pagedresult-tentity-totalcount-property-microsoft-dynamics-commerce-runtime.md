---
title: PagedResult(TEntity).TotalCount Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: TotalCount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.PagedResult`1.TotalCount
ms:mtpsurl: https://technet.microsoft.com/library/Dn719083(v=AX.60)
ms:contentKeyID: 62214698
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.PagedResult`1.TotalCount
dev_langs:
- CSharp
- C++
- VB
---

# TotalCount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TotalCount As Nullable(Of Long)
    Get
    Friend Set
'Usage
Dim instance As PagedResult
Dim value As Nullable(Of Long)

value = instance.TotalCount
```

``` csharp
[DataMemberAttribute]
public Nullable<long> TotalCount { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property Nullable<long long> TotalCount {
    Nullable<long long> get ();
    internal: void set (Nullable<long long> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  
Returns [Nullable\<T\>](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\)).  

## See Also

#### Reference

[PagedResult\<TEntity\> Class](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

