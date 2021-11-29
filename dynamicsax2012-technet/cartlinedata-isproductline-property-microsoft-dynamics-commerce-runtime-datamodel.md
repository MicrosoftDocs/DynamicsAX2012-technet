---
title: CartLineData.IsProductLine Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsProductLine Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.IsProductLine
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartlinedata.isproductline(v=AX.60)
ms:contentKeyID: 62211237
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.IsProductLine
dev_langs:
- CSharp
- C++
- VB
---

# IsProductLine Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether the cart line is created from a listing.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public ReadOnly Property IsProductLine As Boolean
    Get
'Usage
Dim instance As CartLineData
Dim value As Boolean

value = instance.IsProductLine
```

``` csharp
[IgnoreDataMemberAttribute]
public bool IsProductLine { get; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property bool IsProductLine {
    bool get ();
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[CartLineData Class](cartlinedata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

