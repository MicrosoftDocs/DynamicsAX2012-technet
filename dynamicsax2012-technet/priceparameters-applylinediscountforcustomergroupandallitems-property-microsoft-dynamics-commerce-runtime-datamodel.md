---
title: PriceParameters.ApplyLineDiscountForCustomerGroupAndAllItems Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ApplyLineDiscountForCustomerGroupAndAllItems Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters.ApplyLineDiscountForCustomerGroupAndAllItems
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.priceparameters.applylinediscountforcustomergroupandallitems(v=AX.60)
ms:contentKeyID: 49852005
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters.ApplyLineDiscountForCustomerGroupAndAllItems
dev_langs:
- CSharp
- C++
- VB
---

# ApplyLineDiscountForCustomerGroupAndAllItems Property

Gets a value indicating whether line discount trade agreement should apply for combination of customer group and all items.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SALESLINEGROUPALL")> _
Public Property ApplyLineDiscountForCustomerGroupAndAllItems As Boolean
    Get
    Friend Set
'Usage
Dim instance As PriceParameters
Dim value As Boolean

value = instance.ApplyLineDiscountForCustomerGroupAndAllItems
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SALESLINEGROUPALL")]
public bool ApplyLineDiscountForCustomerGroupAndAllItems { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SALESLINEGROUPALL")]
public:
property bool ApplyLineDiscountForCustomerGroupAndAllItems {
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

