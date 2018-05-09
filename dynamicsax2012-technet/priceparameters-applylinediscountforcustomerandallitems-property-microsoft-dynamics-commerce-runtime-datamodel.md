---
title: PriceParameters.ApplyLineDiscountForCustomerAndAllItems Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ApplyLineDiscountForCustomerAndAllItems Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters.ApplyLineDiscountForCustomerAndAllItems
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.priceparameters.applylinediscountforcustomerandallitems(v=AX.60)
ms:contentKeyID: 49853748
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters.ApplyLineDiscountForCustomerAndAllItems
dev_langs:
- CSharp
- C++
- VB
---

# ApplyLineDiscountForCustomerAndAllItems Property

Gets a value indicating whether line discount trade agreement should apply for combination of customer and all items.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SALESLINEACCOUNTALL")> _
Public Property ApplyLineDiscountForCustomerAndAllItems As Boolean
    Get
    Friend Set
'Usage
Dim instance As PriceParameters
Dim value As Boolean

value = instance.ApplyLineDiscountForCustomerAndAllItems
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SALESLINEACCOUNTALL")]
public bool ApplyLineDiscountForCustomerAndAllItems { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SALESLINEACCOUNTALL")]
public:
property bool ApplyLineDiscountForCustomerAndAllItems {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[PriceParameters Class](priceparameters-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

