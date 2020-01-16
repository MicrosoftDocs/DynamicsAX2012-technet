---
title: GetPriceAndDiscountDataServiceRequest.ProductId Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ProductId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPriceAndDiscountDataServiceRequest.ProductId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getpriceanddiscountdataservicerequest.productid(v=AX.60)
ms:contentKeyID: 65320040
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPriceAndDiscountDataServiceRequest.ProductId
dev_langs:
- CSharp
- C++
- VB
---

# ProductId Property

Gets or sets the product identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ProductId As Long
    Get
    Protected Set
'Usage
Dim instance As GetPriceAndDiscountDataServiceRequest
Dim value As Long

value = instance.ProductId

instance.ProductId = value
```

``` csharp
[DataMemberAttribute]
public long ProductId { get; protected set; }
```

``` c++
[DataMemberAttribute]
public:
property long long ProductId {
    long long get ();
    protected: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[GetPriceAndDiscountDataServiceRequest Class](getpriceanddiscountdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

