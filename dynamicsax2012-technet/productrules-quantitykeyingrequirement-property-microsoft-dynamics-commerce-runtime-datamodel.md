---
title: ProductRules.QuantityKeyingRequirement Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: QuantityKeyingRequirement Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRules.QuantityKeyingRequirement
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productrules.quantitykeyingrequirement(v=AX.60)
ms:contentKeyID: 62205877
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRules.QuantityKeyingRequirement
dev_langs:
- CSharp
- C++
- VB
---

# QuantityKeyingRequirement Property

Gets the items' comment keying requirement.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("KEYINGINQTY")> _
Public Property QuantityKeyingRequirement As KeyInQuantities
    Get
    Friend Set
'Usage
Dim instance As ProductRules
Dim value As KeyInQuantities

value = instance.QuantityKeyingRequirement
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("KEYINGINQTY")]
public KeyInQuantities QuantityKeyingRequirement { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"KEYINGINQTY")]
public:
property KeyInQuantities QuantityKeyingRequirement {
    KeyInQuantities get ();
    internal: void set (KeyInQuantities value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.KeyInQuantities](keyinquantities-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [KeyInQuantities](keyinquantities-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ProductRules Class](productrules-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

