---
title: CommerceEntity.SetImplicitDataLevel Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SetImplicitDataLevel Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity.SetImplicitDataLevel(Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntityDataLevel)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.commerceentity.setimplicitdatalevel(v=AX.60)
ms:contentKeyID: 62202572
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity.SetImplicitDataLevel
dev_langs:
- CSharp
- C++
- VB
---

# SetImplicitDataLevel Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Allows the derived Commerce entities to set their respective data levels, while not exposing it to other assemblies.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Protected Sub SetImplicitDataLevel ( _
    implicitDataLevel As CommerceEntityDataLevel _
)
'Usage
Dim implicitDataLevel As CommerceEntityDataLevel

Me.SetImplicitDataLevel(implicitDataLevel)
```

``` csharp
protected void SetImplicitDataLevel(
    CommerceEntityDataLevel implicitDataLevel
)
```

``` c++
protected:
void SetImplicitDataLevel(
    CommerceEntityDataLevel implicitDataLevel
)
```

#### Parameters

  - implicitDataLevel  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntityDataLevel](commerceentitydatalevel-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[CommerceEntity Class](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

