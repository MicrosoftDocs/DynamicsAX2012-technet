---
title: GetOrderDeliveryOptionsServiceResponse.DeliveryOptions Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: DeliveryOptions Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetOrderDeliveryOptionsServiceResponse.DeliveryOptions
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getorderdeliveryoptionsserviceresponse.deliveryoptions(v=AX.60)
ms:contentKeyID: 49853991
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetOrderDeliveryOptionsServiceResponse.DeliveryOptions
dev_langs:
- CSharp
- C++
- VB
---

# DeliveryOptions Property

Gets the collection of delivery options that have been computed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DeliveryOptions As ReadOnlyCollection(Of DeliveryOption)
    Get
    Private Set
'Usage
Dim instance As GetOrderDeliveryOptionsServiceResponse
Dim value As ReadOnlyCollection(Of DeliveryOption)

value = instance.DeliveryOptions
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<DeliveryOption> DeliveryOptions { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<DeliveryOption^>^ DeliveryOptions {
    ReadOnlyCollection<DeliveryOption^>^ get ();
    private: void set (ReadOnlyCollection<DeliveryOption^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[DeliveryOption](deliveryoption-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetOrderDeliveryOptionsServiceResponse Class](getorderdeliveryoptionsserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

