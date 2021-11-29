---
title: CommerceEntity.CopyFrom(T) Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CopyFrom(T) Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity.CopyFrom``1(``0)
ms:mtpsurl: https://technet.microsoft.com/library/Dn739019(v=AX.60)
ms:contentKeyID: 62211832
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity.CopyFrom``1
dev_langs:
- CSharp
- C++
- VB
---

# CopyFrom(T) Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Copies all properties from the given commerce entity into this entity.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Sub CopyFrom(Of T As CommerceEntity) ( _
    commerceEntity As T _
)
'Usage
Dim instance As CommerceEntity
Dim commerceEntity As T

instance.CopyFrom(commerceEntity)
```

``` csharp
public void CopyFrom<T>(
    T commerceEntity
)
where T : CommerceEntity
```

``` c++
public:
generic<typename T>
where T : CommerceEntity
void CopyFrom(
    T commerceEntity
)
```

#### Type Parameters

  - T

#### Parameters

  - commerceEntity  
    Type: T  

## See Also

#### Reference

[CommerceEntity Class](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

