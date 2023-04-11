---
title: IDimensionV1.GetDimensionForVariant Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GetDimensionForVariant Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDimensionV1.GetDimensionForVariant(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IDimension)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.idimensionv1.getdimensionforvariant(v=AX.60)
ms:contentKeyID: 47344430
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDimensionV1.GetDimensionForVariant
dev_langs:
- CSharp
- C++
- VB
---

# GetDimensionForVariant Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Populates dimension information about dimension object passed in.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub GetDimensionForVariant ( _
    dimension As IDimension _
)
'Usage
Dim instance As IDimensionV1
Dim dimension As IDimension

instance.GetDimensionForVariant(dimension)
```

``` csharp
void GetDimensionForVariant(
    IDimension dimension
)
```

``` c++
void GetDimensionForVariant(
    IDimension^ dimension
)
```

#### Parameters

  - dimension  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IDimension](idimension-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IDimensionV1 Interface](idimensionv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

