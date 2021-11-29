---
title: TrackingInfo.ShipmentProgress Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ShipmentProgress Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TrackingInfo.ShipmentProgress
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.trackinginfo.shipmentprogress(v=AX.60)
ms:contentKeyID: 49836732
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TrackingInfo.ShipmentProgress
dev_langs:
- CSharp
- C++
- VB
---

# ShipmentProgress Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the shipment progress.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ShipmentProgress As ICollection(Of ShipmentProgress)
    Get
    Private Set
'Usage
Dim instance As TrackingInfo
Dim value As ICollection(Of ShipmentProgress)

value = instance.ShipmentProgress
```

``` csharp
[DataMemberAttribute]
public ICollection<ShipmentProgress> ShipmentProgress { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<ShipmentProgress^>^ ShipmentProgress {
    ICollection<ShipmentProgress^>^ get ();
    private: void set (ICollection<ShipmentProgress^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[ShipmentProgress](shipmentprogress-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The shipment progress.  

## See Also

#### Reference

[TrackingInfo Class](trackinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

