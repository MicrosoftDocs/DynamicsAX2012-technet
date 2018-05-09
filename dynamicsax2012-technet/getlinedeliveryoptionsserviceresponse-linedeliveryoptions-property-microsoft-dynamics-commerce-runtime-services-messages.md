---
title: GetLineDeliveryOptionsServiceResponse.LineDeliveryOptions Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: LineDeliveryOptions Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLineDeliveryOptionsServiceResponse.LineDeliveryOptions
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getlinedeliveryoptionsserviceresponse.linedeliveryoptions(v=AX.60)
ms:contentKeyID: 49833423
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLineDeliveryOptionsServiceResponse.LineDeliveryOptions
dev_langs:
- CSharp
- C++
- VB
---

# LineDeliveryOptions Property

Gets the collection of delivery options that have been computed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LineDeliveryOptions As ReadOnlyCollection(Of SalesLineDeliveryOption)
    Get
    Private Set
'Usage
Dim instance As GetLineDeliveryOptionsServiceResponse
Dim value As ReadOnlyCollection(Of SalesLineDeliveryOption)

value = instance.LineDeliveryOptions
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<SalesLineDeliveryOption> LineDeliveryOptions { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<SalesLineDeliveryOption^>^ LineDeliveryOptions {
    ReadOnlyCollection<SalesLineDeliveryOption^>^ get ();
    private: void set (ReadOnlyCollection<SalesLineDeliveryOption^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[SalesLineDeliveryOption](saleslinedeliveryoption-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetLineDeliveryOptionsServiceResponse Class](getlinedeliveryoptionsserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

