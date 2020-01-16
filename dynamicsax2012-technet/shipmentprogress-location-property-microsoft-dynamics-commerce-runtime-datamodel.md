---
title: ShipmentProgress.Location Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Location Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentProgress.Location
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shipmentprogress.location(v=AX.60)
ms:contentKeyID: 49837906
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentProgress.Location
dev_langs:
- CSharp
- C++
- VB
---

# Location Property

Gets or sets the location.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Location As Address
    Get
    Set
'Usage
Dim instance As ShipmentProgress
Dim value As Address

value = instance.Location

instance.Location = value
```

``` csharp
[DataMemberAttribute]
public Address Location { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Address^ Location {
    Address^ get ();
    void set (Address^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The location.  

## See Also

#### Reference

[ShipmentProgress Class](shipmentprogress-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

