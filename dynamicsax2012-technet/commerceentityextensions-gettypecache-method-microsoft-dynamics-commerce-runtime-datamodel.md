---
title: CommerceEntityExtensions.GetTypeCache Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GetTypeCache Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntityExtensions.GetTypeCache(Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.commerceentityextensions.gettypecache(v=AX.60)
ms:contentKeyID: 65321865
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntityExtensions.GetTypeCache
dev_langs:
- CSharp
- C++
- VB
---

# GetTypeCache Method

Gets the cache for reflection data.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function GetTypeCache ( _
    entity As CommerceEntity _
) As EntityTypeCache
'Usage
Dim entity As CommerceEntity
Dim returnValue As EntityTypeCache

returnValue = entity.GetTypeCache()
```

``` csharp
public static EntityTypeCache GetTypeCache(
    this CommerceEntity entity
)
```

``` c++
[ExtensionAttribute]
public:
static EntityTypeCache^ GetTypeCache(
    CommerceEntity^ entity
)
```

#### Parameters

  - entity  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.EntityTypeCache](entitytypecache-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Instance of [EntityTypeCache](entitytypecache-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[CommerceEntityExtensions Class](commerceentityextensions-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

