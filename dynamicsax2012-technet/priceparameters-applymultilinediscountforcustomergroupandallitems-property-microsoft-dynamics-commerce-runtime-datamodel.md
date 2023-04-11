---
title: PriceParameters.ApplyMultilineDiscountForCustomerGroupAndAllItems Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ApplyMultilineDiscountForCustomerGroupAndAllItems Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters.ApplyMultilineDiscountForCustomerGroupAndAllItems
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.priceparameters.applymultilinediscountforcustomergroupandallitems(v=AX.60)
ms:contentKeyID: 49849774
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters.ApplyMultilineDiscountForCustomerGroupAndAllItems
dev_langs:
- CSharp
- C++
- VB
---

# ApplyMultilineDiscountForCustomerGroupAndAllItems Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether multiple line discount trade agreement should apply for combination of customer group and all items.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("SALESMULTILNGROUPALL")> _
<DataMemberAttribute> _
Public Property ApplyMultilineDiscountForCustomerGroupAndAllItems As Boolean
    Get
    Friend Set
'Usage
Dim instance As PriceParameters
Dim value As Boolean

value = instance.ApplyMultilineDiscountForCustomerGroupAndAllItems
```

``` csharp
[ColumnAttribute("SALESMULTILNGROUPALL")]
[DataMemberAttribute]
public bool ApplyMultilineDiscountForCustomerGroupAndAllItems { get; internal set; }
```

``` c++
[ColumnAttribute(L"SALESMULTILNGROUPALL")]
[DataMemberAttribute]
public:
property bool ApplyMultilineDiscountForCustomerGroupAndAllItems {
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

