---
title: GetTrackingInformationFromCarrierServiceRequest.TrackingNumbers Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: TrackingNumbers Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetTrackingInformationFromCarrierServiceRequest.TrackingNumbers
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.gettrackinginformationfromcarrierservicerequest.trackingnumbers(v=AX.60)
ms:contentKeyID: 49851952
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetTrackingInformationFromCarrierServiceRequest.TrackingNumbers
dev_langs:
- CSharp
- C++
- VB
---

# TrackingNumbers Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of tracking numbers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TrackingNumbers As ReadOnlyCollection(Of String)
    Get
    Private Set
'Usage
Dim instance As GetTrackingInformationFromCarrierServiceRequest
Dim value As ReadOnlyCollection(Of String)

value = instance.TrackingNumbers
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<string> TrackingNumbers { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<String^>^ TrackingNumbers {
    ReadOnlyCollection<String^>^ get ();
    private: void set (ReadOnlyCollection<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetTrackingInformationFromCarrierServiceRequest Class](gettrackinginformationfromcarrierservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

