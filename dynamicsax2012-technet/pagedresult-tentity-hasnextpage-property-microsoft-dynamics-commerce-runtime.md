---
title: PagedResult(TEntity).HasNextPage Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: HasNextPage Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.PagedResult`1.HasNextPage
ms:mtpsurl: https://technet.microsoft.com/library/Dn698354(v=AX.60)
ms:contentKeyID: 62210987
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.PagedResult`1.HasNextPage
dev_langs:
- CSharp
- C++
- VB
---

# HasNextPage Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property HasNextPage As Boolean
    Get
    Friend Set
'Usage
Dim instance As PagedResult
Dim value As Boolean

value = instance.HasNextPage
```

``` csharp
[DataMemberAttribute]
public bool HasNextPage { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property bool HasNextPage {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[PagedResult\<TEntity\> Class](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

