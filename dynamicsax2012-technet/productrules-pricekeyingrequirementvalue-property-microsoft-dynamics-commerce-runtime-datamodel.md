---
title: ProductRules.PriceKeyingRequirementValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PriceKeyingRequirementValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRules.PriceKeyingRequirementValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productrules.pricekeyingrequirementvalue(v=AX.60)
ms:contentKeyID: 62209262
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRules.PriceKeyingRequirementValue
dev_langs:
- CSharp
- C++
- VB
---

# PriceKeyingRequirementValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the value of the QuantityKeyingRequirement enum. Used by OData only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PriceKeyingRequirementValue As Integer
    Get
    Friend Set
'Usage
Dim instance As ProductRules
Dim value As Integer

value = instance.PriceKeyingRequirementValue
```

``` csharp
[DataMemberAttribute]
public int PriceKeyingRequirementValue { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property int PriceKeyingRequirementValue {
    int get ();
    internal: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[ProductRules Class](productrules-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

