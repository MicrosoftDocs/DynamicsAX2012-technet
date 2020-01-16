---
title: KitLineDefinition.AddKitLineProductPropertyValue Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AddKitLineProductPropertyValue Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.KitLineDefinition.AddKitLineProductPropertyValue(System.Int64,Microsoft.Dynamics.Commerce.Runtime.DataModel.KitLineProductProperty)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.kitlinedefinition.addkitlineproductpropertyvalue(v=AX.60)
ms:contentKeyID: 65322887
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KitLineDefinition.AddKitLineProductPropertyValue
dev_langs:
- CSharp
- C++
- VB
---

# AddKitLineProductPropertyValue Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub AddKitLineProductPropertyValue ( _
    kitLineProductId As Long, _
    property As KitLineProductProperty _
)
'Usage
Dim instance As KitLineDefinition
Dim kitLineProductId As Long
Dim property As KitLineProductProperty

instance.AddKitLineProductPropertyValue(kitLineProductId, _
    property)
```

``` csharp
public void AddKitLineProductPropertyValue(
    long kitLineProductId,
    KitLineProductProperty property
)
```

``` c++
public:
void AddKitLineProductPropertyValue(
    long long kitLineProductId, 
    KitLineProductProperty^ property
)
```

#### Parameters

  - kitLineProductId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - property  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.KitLineProductProperty](kitlineproductproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[KitLineDefinition Class](kitlinedefinition-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

