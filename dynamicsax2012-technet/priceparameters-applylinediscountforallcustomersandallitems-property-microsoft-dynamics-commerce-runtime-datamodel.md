---
title: PriceParameters.ApplyLineDiscountForAllCustomersAndAllItems Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ApplyLineDiscountForAllCustomersAndAllItems Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters.ApplyLineDiscountForAllCustomersAndAllItems
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.priceparameters.applylinediscountforallcustomersandallitems(v=AX.60)
ms:contentKeyID: 49848674
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters.ApplyLineDiscountForAllCustomersAndAllItems
dev_langs:
- CSharp
- C++
- VB
---

# ApplyLineDiscountForAllCustomersAndAllItems Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether line discount trade agreement should apply for combination of all customers and all items.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("SALESLINEALLALL")> _
<DataMemberAttribute> _
Public Property ApplyLineDiscountForAllCustomersAndAllItems As Boolean
    Get
    Friend Set
'Usage
Dim instance As PriceParameters
Dim value As Boolean

value = instance.ApplyLineDiscountForAllCustomersAndAllItems
```

``` csharp
[ColumnAttribute("SALESLINEALLALL")]
[DataMemberAttribute]
public bool ApplyLineDiscountForAllCustomersAndAllItems { get; internal set; }
```

``` c++
[ColumnAttribute(L"SALESLINEALLALL")]
[DataMemberAttribute]
public:
property bool ApplyLineDiscountForAllCustomersAndAllItems {
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

