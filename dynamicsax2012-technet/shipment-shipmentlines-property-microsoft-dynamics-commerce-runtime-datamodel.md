---
title: Shipment.ShipmentLines Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ShipmentLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Shipment.ShipmentLines
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.shipment.shipmentlines(v=AX.60)
ms:contentKeyID: 49853320
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Shipment.ShipmentLines
dev_langs:
- CSharp
- C++
- VB
---

# ShipmentLines Property

Gets or sets the packing slip lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ShipmentLines As Collection(Of ShipmentLine)
    Get
    Set
'Usage
Dim instance As Shipment
Dim value As Collection(Of ShipmentLine)

value = instance.ShipmentLines

instance.ShipmentLines = value
```

``` csharp
[DataMemberAttribute]
public Collection<ShipmentLine> ShipmentLines { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<ShipmentLine^>^ ShipmentLines {
    Collection<ShipmentLine^>^ get ();
    void set (Collection<ShipmentLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\))\<[ShipmentLine](shipmentline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The packing slip lines.  

## Remarks

(Note: Never returns a null value. Instead an empty collection is returned.)

## See Also

#### Reference

[Shipment Class](shipment-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

