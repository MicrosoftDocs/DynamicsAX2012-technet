---
title: GetTrackingInformationFromCarrierServiceResponse.TrackingDetails Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: TrackingDetails Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetTrackingInformationFromCarrierServiceResponse.TrackingDetails
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.gettrackinginformationfromcarrierserviceresponse.trackingdetails(v=AX.60)
ms:contentKeyID: 49837091
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetTrackingInformationFromCarrierServiceResponse.TrackingDetails
dev_langs:
- CSharp
- C++
- VB
---

# TrackingDetails Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the details of the shipments that need to be tracked.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TrackingDetails As ReadOnlyCollection(Of TrackingInfo)
    Get
    Private Set
'Usage
Dim instance As GetTrackingInformationFromCarrierServiceResponse
Dim value As ReadOnlyCollection(Of TrackingInfo)

value = instance.TrackingDetails
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<TrackingInfo> TrackingDetails { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<TrackingInfo^>^ TrackingDetails {
    ReadOnlyCollection<TrackingInfo^>^ get ();
    private: void set (ReadOnlyCollection<TrackingInfo^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[TrackingInfo](trackinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetTrackingInformationFromCarrierServiceResponse Class](gettrackinginformationfromcarrierserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

