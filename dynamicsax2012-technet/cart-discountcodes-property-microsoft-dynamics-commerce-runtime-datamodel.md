---
title: Cart.DiscountCodes Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DiscountCodes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.DiscountCodes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cart.discountcodes(v=AX.60)
ms:contentKeyID: 49855940
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.DiscountCodes
dev_langs:
- CSharp
- C++
- VB
---

# DiscountCodes Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets all the discount/promotion codes currently active on this cart.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DiscountCodes As IList(Of String)
    Get
    Set
'Usage
Dim instance As Cart
Dim value As IList(Of String)

value = instance.DiscountCodes

instance.DiscountCodes = value
```

``` csharp
[DataMemberAttribute]
public IList<string> DiscountCodes { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IList<String^>^ DiscountCodes {
    IList<String^>^ get ();
    void set (IList<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
Returns [IList\<T\>](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\)).  

## See Also

#### Reference

[Cart Class](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

