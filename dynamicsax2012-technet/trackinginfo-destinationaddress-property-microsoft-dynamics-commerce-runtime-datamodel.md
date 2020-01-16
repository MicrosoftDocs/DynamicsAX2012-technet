---
title: TrackingInfo.DestinationAddress Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DestinationAddress Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TrackingInfo.DestinationAddress
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.trackinginfo.destinationaddress(v=AX.60)
ms:contentKeyID: 49846033
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TrackingInfo.DestinationAddress
dev_langs:
- CSharp
- C++
- VB
---

# DestinationAddress Property

Gets or sets the destination address.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DestinationAddress As Address
    Get
    Set
'Usage
Dim instance As TrackingInfo
Dim value As Address

value = instance.DestinationAddress

instance.DestinationAddress = value
```

``` csharp
[DataMemberAttribute]
public Address DestinationAddress { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Address^ DestinationAddress {
    Address^ get ();
    void set (Address^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The destination address.  

## See Also

#### Reference

[TrackingInfo Class](trackinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

