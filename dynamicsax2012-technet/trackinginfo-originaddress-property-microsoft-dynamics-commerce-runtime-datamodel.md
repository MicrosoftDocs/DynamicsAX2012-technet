---
title: TrackingInfo.OriginAddress Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OriginAddress Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TrackingInfo.OriginAddress
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.trackinginfo.originaddress(v=AX.60)
ms:contentKeyID: 49842479
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TrackingInfo.OriginAddress
dev_langs:
- CSharp
- C++
- VB
---

# OriginAddress Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the origin address.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property OriginAddress As Address
    Get
    Set
'Usage
Dim instance As TrackingInfo
Dim value As Address

value = instance.OriginAddress

instance.OriginAddress = value
```

``` csharp
[DataMemberAttribute]
public Address OriginAddress { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Address^ OriginAddress {
    Address^ get ();
    void set (Address^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The origin address.  

## See Also

#### Reference

[TrackingInfo Class](trackinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

