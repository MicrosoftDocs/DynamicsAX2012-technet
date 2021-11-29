---
title: SaveShipmentPublishingStatusRequest.ShipmentPublishingStatusCollection Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ShipmentPublishingStatusCollection Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SaveShipmentPublishingStatusRequest.ShipmentPublishingStatusCollection
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.saveshipmentpublishingstatusrequest.shipmentpublishingstatuscollection(v=AX.60)
ms:contentKeyID: 62212612
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SaveShipmentPublishingStatusRequest.ShipmentPublishingStatusCollection
dev_langs:
- CSharp
- C++
- VB
---

# ShipmentPublishingStatusCollection Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the shipments publishing status collection.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<RequiredAttribute> _
Public Property ShipmentPublishingStatusCollection As IEnumerable(Of ShipmentPublishingStatus)
    Get
    Set
'Usage
Dim instance As SaveShipmentPublishingStatusRequest
Dim value As IEnumerable(Of ShipmentPublishingStatus)

value = instance.ShipmentPublishingStatusCollection

instance.ShipmentPublishingStatusCollection = value
```

``` csharp
[DataMemberAttribute]
[RequiredAttribute]
public IEnumerable<ShipmentPublishingStatus> ShipmentPublishingStatusCollection { get; set; }
```

``` c++
[DataMemberAttribute]
[RequiredAttribute]
public:
property IEnumerable<ShipmentPublishingStatus^>^ ShipmentPublishingStatusCollection {
    IEnumerable<ShipmentPublishingStatus^>^ get ();
    void set (IEnumerable<ShipmentPublishingStatus^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ShipmentPublishingStatus](shipmentpublishingstatus-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[SaveShipmentPublishingStatusRequest Class](saveshipmentpublishingstatusrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

