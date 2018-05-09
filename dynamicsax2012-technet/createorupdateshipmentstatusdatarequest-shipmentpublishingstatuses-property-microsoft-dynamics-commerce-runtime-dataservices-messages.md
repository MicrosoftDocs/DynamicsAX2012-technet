---
title: CreateOrUpdateShipmentStatusDataRequest.ShipmentPublishingStatuses Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ShipmentPublishingStatuses Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.CreateOrUpdateShipmentStatusDataRequest.ShipmentPublishingStatuses
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.createorupdateshipmentstatusdatarequest.shipmentpublishingstatuses(v=AX.60)
ms:contentKeyID: 65315607
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.CreateOrUpdateShipmentStatusDataRequest.ShipmentPublishingStatuses
dev_langs:
- CSharp
- C++
- VB
---

# ShipmentPublishingStatuses Property

Gets the shipment statuses to be created or updated.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ShipmentPublishingStatuses As IEnumerable(Of ShipmentPublishingStatus)
    Get
    Private Set
'Usage
Dim instance As CreateOrUpdateShipmentStatusDataRequest
Dim value As IEnumerable(Of ShipmentPublishingStatus)

value = instance.ShipmentPublishingStatuses
```

``` csharp
[DataMemberAttribute]
public IEnumerable<ShipmentPublishingStatus> ShipmentPublishingStatuses { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<ShipmentPublishingStatus^>^ ShipmentPublishingStatuses {
    IEnumerable<ShipmentPublishingStatus^>^ get ();
    private: void set (IEnumerable<ShipmentPublishingStatus^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[ShipmentPublishingStatus](shipmentpublishingstatus-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[CreateOrUpdateShipmentStatusDataRequest Class](createorupdateshipmentstatusdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

