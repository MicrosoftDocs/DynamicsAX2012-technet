---
title: PeriodicDiscount.IsDiscountCodeRequired Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsDiscountCodeRequired Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.IsDiscountCodeRequired
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.periodicdiscount.isdiscountcoderequired(v=AX.60)
ms:contentKeyID: 49831451
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.IsDiscountCodeRequired
dev_langs:
- CSharp
- C++
- VB
---

# IsDiscountCodeRequired Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether a discount code is required to activate this discount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ISDISCOUNTCODEREQUIRED")> _
Public Property IsDiscountCodeRequired As Boolean
    Get
    Friend Set
'Usage
Dim instance As PeriodicDiscount
Dim value As Boolean

value = instance.IsDiscountCodeRequired
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ISDISCOUNTCODEREQUIRED")]
public bool IsDiscountCodeRequired { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ISDISCOUNTCODEREQUIRED")]
public:
property bool IsDiscountCodeRequired {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[PeriodicDiscount Class](periodicdiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

