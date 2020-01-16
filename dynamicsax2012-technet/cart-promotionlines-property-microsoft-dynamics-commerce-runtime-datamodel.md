---
title: Cart.PromotionLines Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PromotionLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.PromotionLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cart.promotionlines(v=AX.60)
ms:contentKeyID: 62211015
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.PromotionLines
dev_langs:
- CSharp
- C++
- VB
---

# PromotionLines Property

Gets or sets a collection of all promotions belonging to the cart line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PromotionLines As IList(Of String)
    Get
    Set
'Usage
Dim instance As Cart
Dim value As IList(Of String)

value = instance.PromotionLines

instance.PromotionLines = value
```

``` csharp
[DataMemberAttribute]
public IList<string> PromotionLines { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IList<String^>^ PromotionLines {
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

