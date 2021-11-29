---
title: TrackingInfo.TrackingNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TrackingNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TrackingInfo.TrackingNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.trackinginfo.trackingnumber(v=AX.60)
ms:contentKeyID: 49854020
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TrackingInfo.TrackingNumber
dev_langs:
- CSharp
- C++
- VB
---

# TrackingNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the carrier specific tracking number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TrackingNumber As String
    Get
    Set
'Usage
Dim instance As TrackingInfo
Dim value As String

value = instance.TrackingNumber

instance.TrackingNumber = value
```

``` csharp
[DataMemberAttribute]
public string TrackingNumber { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ TrackingNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The tracking number.  

## See Also

#### Reference

[TrackingInfo Class](trackinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

