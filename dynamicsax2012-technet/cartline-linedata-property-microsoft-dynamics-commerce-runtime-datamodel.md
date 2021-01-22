---
title: CartLine.LineData Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineData Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.LineData
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartline.linedata(v=AX.60)
ms:contentKeyID: 49849409
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.LineData
dev_langs:
- CSharp
- C++
- VB
---

# LineData Property

Gets or sets the cart line data.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property LineData As CartLineData
    Get
    Set
'Usage
Dim instance As CartLine
Dim value As CartLineData

value = instance.LineData

instance.LineData = value
```

``` csharp
[IgnoreDataMemberAttribute]
public CartLineData LineData { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property CartLineData^ LineData {
    CartLineData^ get ();
    void set (CartLineData^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData](cartlinedata-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [CartLineData](cartlinedata-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[CartLine Class](cartline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

