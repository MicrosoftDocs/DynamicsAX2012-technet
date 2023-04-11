---
title: TrackingInfo.ServiceType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ServiceType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TrackingInfo.ServiceType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.trackinginfo.servicetype(v=AX.60)
ms:contentKeyID: 49826269
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TrackingInfo.ServiceType
dev_langs:
- CSharp
- C++
- VB
---

# ServiceType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the type of the service (e.g. Ground, Air).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ServiceType As String
    Get
    Set
'Usage
Dim instance As TrackingInfo
Dim value As String

value = instance.ServiceType

instance.ServiceType = value
```

``` csharp
[DataMemberAttribute]
public string ServiceType { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ServiceType {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The type of the service.  

## See Also

#### Reference

[TrackingInfo Class](trackinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

