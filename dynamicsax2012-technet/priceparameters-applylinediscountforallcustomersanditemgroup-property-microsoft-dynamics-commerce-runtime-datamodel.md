---
title: PriceParameters.ApplyLineDiscountForAllCustomersAndItemGroup Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ApplyLineDiscountForAllCustomersAndItemGroup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters.ApplyLineDiscountForAllCustomersAndItemGroup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.priceparameters.applylinediscountforallcustomersanditemgroup(v=AX.60)
ms:contentKeyID: 49846398
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters.ApplyLineDiscountForAllCustomersAndItemGroup
dev_langs:
- CSharp
- C++
- VB
---

# ApplyLineDiscountForAllCustomersAndItemGroup Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether line discount trade agreement should apply for combination of all customers and item group.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SALESLINEALLGROUP")> _
Public Property ApplyLineDiscountForAllCustomersAndItemGroup As Boolean
    Get
    Friend Set
'Usage
Dim instance As PriceParameters
Dim value As Boolean

value = instance.ApplyLineDiscountForAllCustomersAndItemGroup
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SALESLINEALLGROUP")]
public bool ApplyLineDiscountForAllCustomersAndItemGroup { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SALESLINEALLGROUP")]
public:
property bool ApplyLineDiscountForAllCustomersAndItemGroup {
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

