---
title: PriceParameters.ApplyLineDiscountForCustomerGroupAndItemGroup Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ApplyLineDiscountForCustomerGroupAndItemGroup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters.ApplyLineDiscountForCustomerGroupAndItemGroup
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.priceparameters.applylinediscountforcustomergroupanditemgroup(v=AX.60)
ms:contentKeyID: 49834295
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters.ApplyLineDiscountForCustomerGroupAndItemGroup
dev_langs:
- CSharp
- C++
- VB
---

# ApplyLineDiscountForCustomerGroupAndItemGroup Property

Gets a value indicating whether line discount trade agreement should apply for combination of customer group and item group.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SALESLINEGROUPGROUP")> _
Public Property ApplyLineDiscountForCustomerGroupAndItemGroup As Boolean
    Get
    Friend Set
'Usage
Dim instance As PriceParameters
Dim value As Boolean

value = instance.ApplyLineDiscountForCustomerGroupAndItemGroup
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SALESLINEGROUPGROUP")]
public bool ApplyLineDiscountForCustomerGroupAndItemGroup { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SALESLINEGROUPGROUP")]
public:
property bool ApplyLineDiscountForCustomerGroupAndItemGroup {
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

