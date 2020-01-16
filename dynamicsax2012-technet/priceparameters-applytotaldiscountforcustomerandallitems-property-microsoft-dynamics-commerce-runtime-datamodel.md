---
title: PriceParameters.ApplyTotalDiscountForCustomerAndAllItems Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ApplyTotalDiscountForCustomerAndAllItems Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters.ApplyTotalDiscountForCustomerAndAllItems
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.priceparameters.applytotaldiscountforcustomerandallitems(v=AX.60)
ms:contentKeyID: 49831762
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters.ApplyTotalDiscountForCustomerAndAllItems
dev_langs:
- CSharp
- C++
- VB
---

# ApplyTotalDiscountForCustomerAndAllItems Property

Gets a value indicating whether total discount trade agreement should apply for combination of customer and all items.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("SALESENDACCOUNTALL")> _
<DataMemberAttribute> _
Public Property ApplyTotalDiscountForCustomerAndAllItems As Boolean
    Get
    Friend Set
'Usage
Dim instance As PriceParameters
Dim value As Boolean

value = instance.ApplyTotalDiscountForCustomerAndAllItems
```

``` csharp
[ColumnAttribute("SALESENDACCOUNTALL")]
[DataMemberAttribute]
public bool ApplyTotalDiscountForCustomerAndAllItems { get; internal set; }
```

``` c++
[ColumnAttribute(L"SALESENDACCOUNTALL")]
[DataMemberAttribute]
public:
property bool ApplyTotalDiscountForCustomerAndAllItems {
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

