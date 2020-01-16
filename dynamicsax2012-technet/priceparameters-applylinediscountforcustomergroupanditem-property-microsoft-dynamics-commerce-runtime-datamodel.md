---
title: PriceParameters.ApplyLineDiscountForCustomerGroupAndItem Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ApplyLineDiscountForCustomerGroupAndItem Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters.ApplyLineDiscountForCustomerGroupAndItem
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.priceparameters.applylinediscountforcustomergroupanditem(v=AX.60)
ms:contentKeyID: 49848720
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters.ApplyLineDiscountForCustomerGroupAndItem
dev_langs:
- CSharp
- C++
- VB
---

# ApplyLineDiscountForCustomerGroupAndItem Property

Gets a value indicating whether line discount trade agreement should apply for combination of customer group and item.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SALESLINEGROUPITEM")> _
Public Property ApplyLineDiscountForCustomerGroupAndItem As Boolean
    Get
    Friend Set
'Usage
Dim instance As PriceParameters
Dim value As Boolean

value = instance.ApplyLineDiscountForCustomerGroupAndItem
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SALESLINEGROUPITEM")]
public bool ApplyLineDiscountForCustomerGroupAndItem { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SALESLINEGROUPITEM")]
public:
property bool ApplyLineDiscountForCustomerGroupAndItem {
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

