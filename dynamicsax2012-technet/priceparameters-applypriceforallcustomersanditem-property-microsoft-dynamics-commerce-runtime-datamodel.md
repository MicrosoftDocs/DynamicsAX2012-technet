---
title: PriceParameters.ApplyPriceForAllCustomersAndItem Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ApplyPriceForAllCustomersAndItem Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters.ApplyPriceForAllCustomersAndItem
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.priceparameters.applypriceforallcustomersanditem(v=AX.60)
ms:contentKeyID: 49854859
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters.ApplyPriceForAllCustomersAndItem
dev_langs:
- CSharp
- C++
- VB
---

# ApplyPriceForAllCustomersAndItem Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether price trade agreements should apply for combination of all customers and item.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SALESPRICEALLITEM")> _
Public Property ApplyPriceForAllCustomersAndItem As Boolean
    Get
    Friend Set
'Usage
Dim instance As PriceParameters
Dim value As Boolean

value = instance.ApplyPriceForAllCustomersAndItem
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SALESPRICEALLITEM")]
public bool ApplyPriceForAllCustomersAndItem { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SALESPRICEALLITEM")]
public:
property bool ApplyPriceForAllCustomersAndItem {
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

