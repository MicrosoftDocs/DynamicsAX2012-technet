---
title: PriceParameters.ApplyMultilineDiscountForCustomerAndAllItems Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ApplyMultilineDiscountForCustomerAndAllItems Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters.ApplyMultilineDiscountForCustomerAndAllItems
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.priceparameters.applymultilinediscountforcustomerandallitems(v=AX.60)
ms:contentKeyID: 49837463
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters.ApplyMultilineDiscountForCustomerAndAllItems
dev_langs:
- CSharp
- C++
- VB
---

# ApplyMultilineDiscountForCustomerAndAllItems Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether multiple line discount trade agreement should apply for combination of customer and all items.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SALESMULTILNACCOUNTALL")> _
Public Property ApplyMultilineDiscountForCustomerAndAllItems As Boolean
    Get
    Friend Set
'Usage
Dim instance As PriceParameters
Dim value As Boolean

value = instance.ApplyMultilineDiscountForCustomerAndAllItems
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SALESMULTILNACCOUNTALL")]
public bool ApplyMultilineDiscountForCustomerAndAllItems { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SALESMULTILNACCOUNTALL")]
public:
property bool ApplyMultilineDiscountForCustomerAndAllItems {
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

