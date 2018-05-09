---
title: Shipment.DeliveryAddress Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DeliveryAddress Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Shipment.DeliveryAddress
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.shipment.deliveryaddress(v=AX.60)
ms:contentKeyID: 49840744
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Shipment.DeliveryAddress
dev_langs:
- CSharp
- C++
- VB
---

# DeliveryAddress Property

Gets or sets the delivery address.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property DeliveryAddress As Address
    Get
    Set
'Usage
Dim instance As Shipment
Dim value As Address

value = instance.DeliveryAddress

instance.DeliveryAddress = value
```

``` csharp
[IgnoreDataMemberAttribute]
public Address DeliveryAddress { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property Address^ DeliveryAddress {
    Address^ get ();
    void set (Address^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The delivery address.  

## See Also

#### Reference

[Shipment Class](shipment-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

