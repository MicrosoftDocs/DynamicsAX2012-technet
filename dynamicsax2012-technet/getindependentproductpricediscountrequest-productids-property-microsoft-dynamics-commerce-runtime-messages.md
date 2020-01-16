---
title: GetIndependentProductPriceDiscountRequest.ProductIds Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ProductIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetIndependentProductPriceDiscountRequest.ProductIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getindependentproductpricediscountrequest.productids(v=AX.60)
ms:contentKeyID: 65318854
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetIndependentProductPriceDiscountRequest.ProductIds
dev_langs:
- CSharp
- C++
- VB
---

# ProductIds Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ProductIds As IEnumerable(Of Long)
    Get
    Set
'Usage
Dim instance As GetIndependentProductPriceDiscountRequest
Dim value As IEnumerable(Of Long)

value = instance.ProductIds

instance.ProductIds = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<long> ProductIds { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<long long>^ ProductIds {
    IEnumerable<long long>^ get ();
    void set (IEnumerable<long long>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

## See Also

#### Reference

[GetIndependentProductPriceDiscountRequest Class](getindependentproductpricediscountrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

