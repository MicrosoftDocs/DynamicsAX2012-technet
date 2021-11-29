---
title: ShipmentsContainer.Shipments Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Shipments Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentsContainer.Shipments
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shipmentscontainer.shipments(v=AX.60)
ms:contentKeyID: 49849047
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentsContainer.Shipments
dev_langs:
- CSharp
- C++
- VB
---

# Shipments Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the shipments.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Property Shipments As Collection(Of Shipment)
    Get
    Set
'Usage
Dim instance As ShipmentsContainer
Dim value As Collection(Of Shipment)

value = instance.Shipments

instance.Shipments = value
```

``` csharp
public Collection<Shipment> Shipments { get; set; }
```

``` c++
public:
property Collection<Shipment^>^ Shipments {
    Collection<Shipment^>^ get ();
    void set (Collection<Shipment^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[Shipment](shipment-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The shipments.  

## See Also

#### Reference

[ShipmentsContainer Class](shipmentscontainer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

