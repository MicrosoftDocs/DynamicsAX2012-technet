---
title: KitDefinition.AddKitVariantToComponentMappingValue Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AddKitVariantToComponentMappingValue Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.KitDefinition.AddKitVariantToComponentMappingValue(System.Int64,Microsoft.Dynamics.Commerce.Runtime.DataModel.KitComponentKey)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.kitdefinition.addkitvarianttocomponentmappingvalue(v=AX.60)
ms:contentKeyID: 65320971
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KitDefinition.AddKitVariantToComponentMappingValue
dev_langs:
- CSharp
- C++
- VB
---

# AddKitVariantToComponentMappingValue Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub AddKitVariantToComponentMappingValue ( _
    kitVariantId As Long, _
    kitComponentKey As KitComponentKey _
)
'Usage
Dim instance As KitDefinition
Dim kitVariantId As Long
Dim kitComponentKey As KitComponentKey

instance.AddKitVariantToComponentMappingValue(kitVariantId, _
    kitComponentKey)
```

``` csharp
public void AddKitVariantToComponentMappingValue(
    long kitVariantId,
    KitComponentKey kitComponentKey
)
```

``` c++
public:
void AddKitVariantToComponentMappingValue(
    long long kitVariantId, 
    KitComponentKey^ kitComponentKey
)
```

#### Parameters

  - kitVariantId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - kitComponentKey  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.KitComponentKey](kitcomponentkey-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[KitDefinition Class](kitdefinition-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

