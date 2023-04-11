---
title: GetShipmentPublishingStatusResponse.ShipmentPublishingStatusCollection Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ShipmentPublishingStatusCollection Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetShipmentPublishingStatusResponse.ShipmentPublishingStatusCollection
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getshipmentpublishingstatusresponse.shipmentpublishingstatuscollection(v=AX.60)
ms:contentKeyID: 62209590
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetShipmentPublishingStatusResponse.ShipmentPublishingStatusCollection
dev_langs:
- CSharp
- C++
- VB
---

# ShipmentPublishingStatusCollection Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the shipments publishing status collection.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ShipmentPublishingStatusCollection As ReadOnlyCollection(Of ShipmentPublishingStatus)
    Get
    Private Set
'Usage
Dim instance As GetShipmentPublishingStatusResponse
Dim value As ReadOnlyCollection(Of ShipmentPublishingStatus)

value = instance.ShipmentPublishingStatusCollection
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<ShipmentPublishingStatus> ShipmentPublishingStatusCollection { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<ShipmentPublishingStatus^>^ ShipmentPublishingStatusCollection {
    ReadOnlyCollection<ShipmentPublishingStatus^>^ get ();
    private: void set (ReadOnlyCollection<ShipmentPublishingStatus^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ShipmentPublishingStatus](shipmentpublishingstatus-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetShipmentPublishingStatusResponse Class](getshipmentpublishingstatusresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

