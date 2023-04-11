---
title: PagedResult(TEntity).Results Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: Results Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.PagedResult`1.Results
ms:mtpsurl: https://technet.microsoft.com/library/Dn684342(v=AX.60)
ms:contentKeyID: 62203482
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.PagedResult`1.Results
dev_langs:
- CSharp
- C++
- VB
---

# Results Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Results As ReadOnlyCollection(Of TEntity)
    Get
    Set
'Usage
Dim instance As PagedResult
Dim value As ReadOnlyCollection(Of TEntity)

value = instance.Results

instance.Results = value
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<TEntity> Results { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<TEntity>^ Results {
    ReadOnlyCollection<TEntity>^ get ();
    void set (ReadOnlyCollection<TEntity>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[TEntity](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[PagedResult\<TEntity\> Class](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

