---
title: PriceParameters.ApplyMultilineDiscountForCustomerAndItemGroup Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ApplyMultilineDiscountForCustomerAndItemGroup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters.ApplyMultilineDiscountForCustomerAndItemGroup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.priceparameters.applymultilinediscountforcustomeranditemgroup(v=AX.60)
ms:contentKeyID: 49845766
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters.ApplyMultilineDiscountForCustomerAndItemGroup
dev_langs:
- CSharp
- C++
- VB
---

# ApplyMultilineDiscountForCustomerAndItemGroup Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether multiple line discount trade agreement should apply for combination of customer and item group.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("SALESMULTILNACCOUNTGROUP")> _
<DataMemberAttribute> _
Public Property ApplyMultilineDiscountForCustomerAndItemGroup As Boolean
    Get
    Friend Set
'Usage
Dim instance As PriceParameters
Dim value As Boolean

value = instance.ApplyMultilineDiscountForCustomerAndItemGroup
```

``` csharp
[ColumnAttribute("SALESMULTILNACCOUNTGROUP")]
[DataMemberAttribute]
public bool ApplyMultilineDiscountForCustomerAndItemGroup { get; internal set; }
```

``` c++
[ColumnAttribute(L"SALESMULTILNACCOUNTGROUP")]
[DataMemberAttribute]
public:
property bool ApplyMultilineDiscountForCustomerAndItemGroup {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[PriceParameters Class](priceparameters-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

