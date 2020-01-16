---
title: GetExternalShippingRateServiceResponse.SalesLineShippingRates Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: SalesLineShippingRates Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetExternalShippingRateServiceResponse.SalesLineShippingRates
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getexternalshippingrateserviceresponse.saleslineshippingrates(v=AX.60)
ms:contentKeyID: 49836429
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetExternalShippingRateServiceResponse.SalesLineShippingRates
dev_langs:
- CSharp
- C++
- VB
---

# SalesLineShippingRates Property

Gets the sales line shipping rates.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SalesLineShippingRates As ReadOnlyCollection(Of SalesLineShippingRate)
    Get
    Private Set
'Usage
Dim instance As GetExternalShippingRateServiceResponse
Dim value As ReadOnlyCollection(Of SalesLineShippingRate)

value = instance.SalesLineShippingRates
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<SalesLineShippingRate> SalesLineShippingRates { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<SalesLineShippingRate^>^ SalesLineShippingRates {
    ReadOnlyCollection<SalesLineShippingRate^>^ get ();
    private: void set (ReadOnlyCollection<SalesLineShippingRate^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[SalesLineShippingRate](saleslineshippingrate-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetExternalShippingRateServiceResponse Class](getexternalshippingrateserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

