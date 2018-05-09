---
title: ProjectionDomain Constructor (Nullable(Int64), Nullable(Int64)) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProjectionDomain Constructor (Nullable(Int64), Nullable(Int64))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProjectionDomain.#ctor(System.Nullable{System.Int64},System.Nullable{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.projectiondomain.projectiondomain(v=AX.60)
ms:contentKeyID: 62204381
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ProjectionDomain Constructor (Nullable(Int64), Nullable(Int64))

Initializes a new instance of the [ProjectionDomain](projectiondomain-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    channelId As Nullable(Of Long), _
    catalogId As Nullable(Of Long) _
)
'Usage
Dim channelId As Nullable(Of Long)
Dim catalogId As Nullable(Of Long)

Dim instance As New ProjectionDomain(channelId, _
    catalogId)
```

``` csharp
public ProjectionDomain(
    Nullable<long> channelId,
    Nullable<long> catalogId
)
```

``` c++
public:
ProjectionDomain(
    Nullable<long long> channelId, 
    Nullable<long long> catalogId
)
```

#### Parameters

  - channelId  
    Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - catalogId  
    Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  

## See Also

#### Reference

[ProjectionDomain Class](projectiondomain-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[ProjectionDomain Overload](projectiondomain-constructor-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

