---
title: EntityTypeCache.GetInstance Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GetInstance Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.EntityTypeCache.GetInstance(System.Type)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.entitytypecache.getinstance(v=AX.60)
ms:contentKeyID: 65317077
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EntityTypeCache.GetInstance
dev_langs:
- CSharp
- C++
- VB
---

# GetInstance Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get the instance of [EntityTypeCache](entitytypecache-class-microsoft-dynamics-commerce-runtime-datamodel.md).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetInstance ( _
    type As Type _
) As EntityTypeCache
'Usage
Dim type As Type
Dim returnValue As EntityTypeCache

returnValue = EntityTypeCache.GetInstance(type)
```

``` csharp
public static EntityTypeCache GetInstance(
    Type type
)
```

``` c++
public:
static EntityTypeCache^ GetInstance(
    Type^ type
)
```

#### Parameters

  - type  
    Type: [System.Type](https://technet.microsoft.com/library/42892f65\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.EntityTypeCache](entitytypecache-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Cache object.  

## See Also

#### Reference

[EntityTypeCache Class](entitytypecache-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

