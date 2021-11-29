---
title: GetShippingRateFromCarrierServiceRequest.ShippingRateInfo Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ShippingRateInfo Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetShippingRateFromCarrierServiceRequest.ShippingRateInfo
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getshippingratefromcarrierservicerequest.shippingrateinfo(v=AX.60)
ms:contentKeyID: 49831992
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetShippingRateFromCarrierServiceRequest.ShippingRateInfo
dev_langs:
- CSharp
- C++
- VB
---

# ShippingRateInfo Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the shipping rate information.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ShippingRateInfo As ShippingRateInfo
    Get
    Private Set
'Usage
Dim instance As GetShippingRateFromCarrierServiceRequest
Dim value As ShippingRateInfo

value = instance.ShippingRateInfo
```

``` csharp
[DataMemberAttribute]
public ShippingRateInfo ShippingRateInfo { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ShippingRateInfo^ ShippingRateInfo {
    ShippingRateInfo^ get ();
    private: void set (ShippingRateInfo^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ShippingRateInfo](shippingrateinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ShippingRateInfo](shippingrateinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetShippingRateFromCarrierServiceRequest Class](getshippingratefromcarrierservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

