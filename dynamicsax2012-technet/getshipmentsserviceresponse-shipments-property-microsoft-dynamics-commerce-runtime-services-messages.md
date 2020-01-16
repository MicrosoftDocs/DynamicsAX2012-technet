---
title: GetShipmentsServiceResponse.Shipments Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Shipments Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetShipmentsServiceResponse.Shipments
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getshipmentsserviceresponse.shipments(v=AX.60)
ms:contentKeyID: 49832005
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetShipmentsServiceResponse.Shipments
dev_langs:
- CSharp
- C++
- VB
---

# Shipments Property

Gets the shipments.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Shipments As ReadOnlyCollection(Of Shipment)
    Get
    Private Set
'Usage
Dim instance As GetShipmentsServiceResponse
Dim value As ReadOnlyCollection(Of Shipment)

value = instance.Shipments
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<Shipment> Shipments { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<Shipment^>^ Shipments {
    ReadOnlyCollection<Shipment^>^ get ();
    private: void set (ReadOnlyCollection<Shipment^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Shipment](shipment-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetShipmentsServiceResponse Class](getshipmentsserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

