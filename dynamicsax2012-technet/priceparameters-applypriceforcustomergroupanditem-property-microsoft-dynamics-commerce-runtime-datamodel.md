---
title: PriceParameters.ApplyPriceForCustomerGroupAndItem Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ApplyPriceForCustomerGroupAndItem Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters.ApplyPriceForCustomerGroupAndItem
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.priceparameters.applypriceforcustomergroupanditem(v=AX.60)
ms:contentKeyID: 49820806
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters.ApplyPriceForCustomerGroupAndItem
dev_langs:
- CSharp
- C++
- VB
---

# ApplyPriceForCustomerGroupAndItem Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether price trade agreements should apply for combinations of customer group and item.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("SALESPRICEGROUPITEM")> _
<DataMemberAttribute> _
Public Property ApplyPriceForCustomerGroupAndItem As Boolean
    Get
    Friend Set
'Usage
Dim instance As PriceParameters
Dim value As Boolean

value = instance.ApplyPriceForCustomerGroupAndItem
```

``` csharp
[ColumnAttribute("SALESPRICEGROUPITEM")]
[DataMemberAttribute]
public bool ApplyPriceForCustomerGroupAndItem { get; internal set; }
```

``` c++
[ColumnAttribute(L"SALESPRICEGROUPITEM")]
[DataMemberAttribute]
public:
property bool ApplyPriceForCustomerGroupAndItem {
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

