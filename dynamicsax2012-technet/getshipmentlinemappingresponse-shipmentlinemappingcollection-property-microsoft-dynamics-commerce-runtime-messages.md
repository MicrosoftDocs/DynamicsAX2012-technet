---
title: GetShipmentLineMappingResponse.ShipmentLineMappingCollection Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ShipmentLineMappingCollection Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetShipmentLineMappingResponse.ShipmentLineMappingCollection
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getshipmentlinemappingresponse.shipmentlinemappingcollection(v=AX.60)
ms:contentKeyID: 62212419
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetShipmentLineMappingResponse.ShipmentLineMappingCollection
dev_langs:
- CSharp
- C++
- VB
---

# ShipmentLineMappingCollection Property

Gets the shipment line mapping collection.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ShipmentLineMappingCollection As ReadOnlyCollection(Of ShipmentLineMapping)
    Get
    Private Set
'Usage
Dim instance As GetShipmentLineMappingResponse
Dim value As ReadOnlyCollection(Of ShipmentLineMapping)

value = instance.ShipmentLineMappingCollection
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<ShipmentLineMapping> ShipmentLineMappingCollection { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<ShipmentLineMapping^>^ ShipmentLineMappingCollection {
    ReadOnlyCollection<ShipmentLineMapping^>^ get ();
    private: void set (ReadOnlyCollection<ShipmentLineMapping^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[ShipmentLineMapping](shipmentlinemapping-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The shipment line mapping collection.  

## See Also

#### Reference

[GetShipmentLineMappingResponse Class](getshipmentlinemappingresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

