---
title: PriceParameters.ApplyTotalDiscountForCustomerGroupAndAllItems Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ApplyTotalDiscountForCustomerGroupAndAllItems Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters.ApplyTotalDiscountForCustomerGroupAndAllItems
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.priceparameters.applytotaldiscountforcustomergroupandallitems(v=AX.60)
ms:contentKeyID: 49827853
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters.ApplyTotalDiscountForCustomerGroupAndAllItems
dev_langs:
- CSharp
- C++
- VB
---

# ApplyTotalDiscountForCustomerGroupAndAllItems Property

Gets a value indicating whether total discount trade agreement should apply for combination of customer group and all items.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SALESENDGROUPALL")> _
Public Property ApplyTotalDiscountForCustomerGroupAndAllItems As Boolean
    Get
    Friend Set
'Usage
Dim instance As PriceParameters
Dim value As Boolean

value = instance.ApplyTotalDiscountForCustomerGroupAndAllItems
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SALESENDGROUPALL")]
public bool ApplyTotalDiscountForCustomerGroupAndAllItems { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SALESENDGROUPALL")]
public:
property bool ApplyTotalDiscountForCustomerGroupAndAllItems {
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

