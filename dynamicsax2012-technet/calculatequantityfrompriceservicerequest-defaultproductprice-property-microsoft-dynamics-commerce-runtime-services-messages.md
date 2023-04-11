---
title: CalculateQuantityFromPriceServiceRequest.DefaultProductPrice Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: DefaultProductPrice Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateQuantityFromPriceServiceRequest.DefaultProductPrice
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.calculatequantityfrompriceservicerequest.defaultproductprice(v=AX.60)
ms:contentKeyID: 62205199
author: tfehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateQuantityFromPriceServiceRequest.DefaultProductPrice
dev_langs:
- CSharp
- C++
- VB
---

# DefaultProductPrice Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the default product price.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DefaultProductPrice As Decimal
    Get
    Private Set
'Usage
Dim instance As CalculateQuantityFromPriceServiceRequest
Dim value As Decimal

value = instance.DefaultProductPrice
```

``` csharp
[DataMemberAttribute]
public decimal DefaultProductPrice { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal DefaultProductPrice {
    Decimal get ();
    private: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[CalculateQuantityFromPriceServiceRequest Class](calculatequantityfrompriceservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

