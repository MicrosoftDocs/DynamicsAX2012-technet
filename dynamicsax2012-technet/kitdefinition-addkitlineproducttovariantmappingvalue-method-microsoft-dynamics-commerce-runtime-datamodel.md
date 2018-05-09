---
title: KitDefinition.AddKitLineProductToVariantMappingValue Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AddKitLineProductToVariantMappingValue Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.KitDefinition.AddKitLineProductToVariantMappingValue(System.Int64,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.kitdefinition.addkitlineproducttovariantmappingvalue(v=AX.60)
ms:contentKeyID: 65322458
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KitDefinition.AddKitLineProductToVariantMappingValue
dev_langs:
- CSharp
- C++
- VB
---

# AddKitLineProductToVariantMappingValue Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub AddKitLineProductToVariantMappingValue ( _
    componentProductId As Long, _
    kitVariantProductId As Long _
)
'Usage
Dim instance As KitDefinition
Dim componentProductId As Long
Dim kitVariantProductId As Long

instance.AddKitLineProductToVariantMappingValue(componentProductId, _
    kitVariantProductId)
```

``` csharp
public void AddKitLineProductToVariantMappingValue(
    long componentProductId,
    long kitVariantProductId
)
```

``` c++
public:
void AddKitLineProductToVariantMappingValue(
    long long componentProductId, 
    long long kitVariantProductId
)
```

#### Parameters

  - componentProductId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - kitVariantProductId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

## See Also

#### Reference

[KitDefinition Class](kitdefinition-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

