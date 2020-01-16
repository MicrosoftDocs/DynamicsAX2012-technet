---
title: GetShippingRateFromCarrierServiceResponse.ShippingRate Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ShippingRate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetShippingRateFromCarrierServiceResponse.ShippingRate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getshippingratefromcarrierserviceresponse.shippingrate(v=AX.60)
ms:contentKeyID: 49852664
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetShippingRateFromCarrierServiceResponse.ShippingRate
dev_langs:
- CSharp
- C++
- VB
---

# ShippingRate Property

Gets the shipping rate.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ShippingRate As Decimal
    Get
    Private Set
'Usage
Dim instance As GetShippingRateFromCarrierServiceResponse
Dim value As Decimal

value = instance.ShippingRate
```

``` csharp
[DataMemberAttribute]
public decimal ShippingRate { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal ShippingRate {
    Decimal get ();
    private: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[GetShippingRateFromCarrierServiceResponse Class](getshippingratefromcarrierserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

