---
title: CartLineData.PromotionLines Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PromotionLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.PromotionLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartlinedata.promotionlines(v=AX.60)
ms:contentKeyID: 62213588
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.PromotionLines
dev_langs:
- CSharp
- C++
- VB
---

# PromotionLines Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a collection of all promotions belonging to the cart line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PromotionLines As Collection(Of String)
    Get
    Friend Set
'Usage
Dim instance As CartLineData
Dim value As Collection(Of String)

value = instance.PromotionLines
```

``` csharp
[DataMemberAttribute]
public Collection<string> PromotionLines { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<String^>^ PromotionLines {
    Collection<String^>^ get ();
    internal: void set (Collection<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
Returns [Collection\<T\>](https://technet.microsoft.com/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[CartLineData Class](cartlinedata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

