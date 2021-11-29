---
title: CartLine.DiscountLines Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DiscountLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.DiscountLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartline.discountlines(v=AX.60)
ms:contentKeyID: 62212079
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.DiscountLines
dev_langs:
- CSharp
- C++
- VB
---

# DiscountLines Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a collection of all discounts belonging to the salesline.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DiscountLines As IList(Of DiscountLine)
    Get
    Set
'Usage
Dim instance As CartLine
Dim value As IList(Of DiscountLine)

value = instance.DiscountLines

instance.DiscountLines = value
```

``` csharp
[DataMemberAttribute]
public IList<DiscountLine> DiscountLines { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IList<DiscountLine^>^ DiscountLines {
    IList<DiscountLine^>^ get ();
    void set (IList<DiscountLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[DiscountLine](discountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IList\<T\>](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\)).  

## See Also

#### Reference

[CartLine Class](cartline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

