---
title: Shipment.TrackingUrl Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TrackingUrl Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Shipment.TrackingUrl
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shipment.trackingurl(v=AX.60)
ms:contentKeyID: 49836146
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Shipment.TrackingUrl
dev_langs:
- CSharp
- C++
- VB
---

# TrackingUrl Property

Gets or sets the tracking URL.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TrackingUrl As String
    Get
    Set
'Usage
Dim instance As Shipment
Dim value As String

value = instance.TrackingUrl

instance.TrackingUrl = value
```

``` csharp
[DataMemberAttribute]
public string TrackingUrl { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ TrackingUrl {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The tracking URL.  

## See Also

#### Reference

[Shipment Class](shipment-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

