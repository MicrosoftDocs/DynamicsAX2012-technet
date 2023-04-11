---
title: Shipment.LatestCarrierTrackingInfo Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LatestCarrierTrackingInfo Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Shipment.LatestCarrierTrackingInfo
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shipment.latestcarriertrackinginfo(v=AX.60)
ms:contentKeyID: 49846055
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Shipment.LatestCarrierTrackingInfo
dev_langs:
- CSharp
- C++
- VB
---

# LatestCarrierTrackingInfo Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the latest carrier tracking info.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LatestCarrierTrackingInfo As TrackingInfo
    Get
    Set
'Usage
Dim instance As Shipment
Dim value As TrackingInfo

value = instance.LatestCarrierTrackingInfo

instance.LatestCarrierTrackingInfo = value
```

``` csharp
[DataMemberAttribute]
public TrackingInfo LatestCarrierTrackingInfo { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property TrackingInfo^ LatestCarrierTrackingInfo {
    TrackingInfo^ get ();
    void set (TrackingInfo^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TrackingInfo](trackinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The latest carrier tracking info.  

## See Also

#### Reference

[Shipment Class](shipment-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

