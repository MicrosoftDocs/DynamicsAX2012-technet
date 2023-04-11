---
title: PriceParameters.ApplyPriceForCustomerAndItem Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ApplyPriceForCustomerAndItem Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters.ApplyPriceForCustomerAndItem
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.priceparameters.applypriceforcustomeranditem(v=AX.60)
ms:contentKeyID: 49846663
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters.ApplyPriceForCustomerAndItem
dev_langs:
- CSharp
- C++
- VB
---

# ApplyPriceForCustomerAndItem Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether price trade agreements should apply for combinations of customer and item.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SALESPRICEACCOUNTITEM")> _
Public Property ApplyPriceForCustomerAndItem As Boolean
    Get
    Friend Set
'Usage
Dim instance As PriceParameters
Dim value As Boolean

value = instance.ApplyPriceForCustomerAndItem
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SALESPRICEACCOUNTITEM")]
public bool ApplyPriceForCustomerAndItem { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SALESPRICEACCOUNTITEM")]
public:
property bool ApplyPriceForCustomerAndItem {
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

