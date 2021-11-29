---
title: CartLineData.IsPriceOverridden Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsPriceOverridden Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.IsPriceOverridden
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartlinedata.ispriceoverridden(v=AX.60)
ms:contentKeyID: 62211505
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.IsPriceOverridden
dev_langs:
- CSharp
- C++
- VB
---

# IsPriceOverridden Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether the price was overriden.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("ISPRICEOVERRIDDEN")> _
Public Property IsPriceOverridden As Boolean
    Get
    Set
'Usage
Dim instance As CartLineData
Dim value As Boolean

value = instance.IsPriceOverridden

instance.IsPriceOverridden = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("ISPRICEOVERRIDDEN")]
public bool IsPriceOverridden { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"ISPRICEOVERRIDDEN")]
public:
property bool IsPriceOverridden {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[CartLineData Class](cartlinedata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

