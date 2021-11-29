---
title: PriceParameters.ApplyMultilineDiscountForAllCustomersAndAllItems Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ApplyMultilineDiscountForAllCustomersAndAllItems Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters.ApplyMultilineDiscountForAllCustomersAndAllItems
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.priceparameters.applymultilinediscountforallcustomersandallitems(v=AX.60)
ms:contentKeyID: 49854419
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters.ApplyMultilineDiscountForAllCustomersAndAllItems
dev_langs:
- CSharp
- C++
- VB
---

# ApplyMultilineDiscountForAllCustomersAndAllItems Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether multiple line discount trade agreement should apply for combination of all customer and all items.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SALESMULTILNALLALL")> _
Public Property ApplyMultilineDiscountForAllCustomersAndAllItems As Boolean
    Get
    Friend Set
'Usage
Dim instance As PriceParameters
Dim value As Boolean

value = instance.ApplyMultilineDiscountForAllCustomersAndAllItems
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SALESMULTILNALLALL")]
public bool ApplyMultilineDiscountForAllCustomersAndAllItems { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SALESMULTILNALLALL")]
public:
property bool ApplyMultilineDiscountForAllCustomersAndAllItems {
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

