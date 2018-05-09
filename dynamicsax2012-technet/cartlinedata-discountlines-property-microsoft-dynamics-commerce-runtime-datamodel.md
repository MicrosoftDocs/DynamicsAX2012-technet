---
title: CartLineData.DiscountLines Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DiscountLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.DiscountLines
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.cartlinedata.discountlines(v=AX.60)
ms:contentKeyID: 62211898
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.DiscountLines
dev_langs:
- CSharp
- C++
- VB
---

# DiscountLines Property

Gets a collection of all discounts belonging to the cart line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DiscountLines As Collection(Of DiscountLine)
    Get
    Friend Set
'Usage
Dim instance As CartLineData
Dim value As Collection(Of DiscountLine)

value = instance.DiscountLines
```

``` csharp
[DataMemberAttribute]
public Collection<DiscountLine> DiscountLines { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<DiscountLine^>^ DiscountLines {
    Collection<DiscountLine^>^ get ();
    internal: void set (Collection<DiscountLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\))\<[DiscountLine](discountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [Collection\<T\>](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[CartLineData Class](cartlinedata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

