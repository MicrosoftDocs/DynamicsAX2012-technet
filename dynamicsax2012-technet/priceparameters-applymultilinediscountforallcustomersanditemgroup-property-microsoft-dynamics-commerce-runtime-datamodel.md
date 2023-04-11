---
title: PriceParameters.ApplyMultilineDiscountForAllCustomersAndItemGroup Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ApplyMultilineDiscountForAllCustomersAndItemGroup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters.ApplyMultilineDiscountForAllCustomersAndItemGroup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.priceparameters.applymultilinediscountforallcustomersanditemgroup(v=AX.60)
ms:contentKeyID: 49856254
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters.ApplyMultilineDiscountForAllCustomersAndItemGroup
dev_langs:
- CSharp
- C++
- VB
---

# ApplyMultilineDiscountForAllCustomersAndItemGroup Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether multiple line discount trade agreement should apply for combination of all customers and item group.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SALESMULTILNALLGROUP")> _
Public Property ApplyMultilineDiscountForAllCustomersAndItemGroup As Boolean
    Get
    Friend Set
'Usage
Dim instance As PriceParameters
Dim value As Boolean

value = instance.ApplyMultilineDiscountForAllCustomersAndItemGroup
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SALESMULTILNALLGROUP")]
public bool ApplyMultilineDiscountForAllCustomersAndItemGroup { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SALESMULTILNALLGROUP")]
public:
property bool ApplyMultilineDiscountForAllCustomersAndItemGroup {
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

