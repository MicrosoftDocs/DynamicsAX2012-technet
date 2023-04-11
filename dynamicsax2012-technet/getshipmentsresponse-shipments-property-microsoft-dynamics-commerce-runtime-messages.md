---
title: GetShipmentsResponse.Shipments Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Shipments Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetShipmentsResponse.Shipments
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getshipmentsresponse.shipments(v=AX.60)
ms:contentKeyID: 49824823
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetShipmentsResponse.Shipments
dev_langs:
- CSharp
- C++
- VB
---

# Shipments Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the shipments.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Shipments As ReadOnlyCollection(Of Shipment)
    Get
    Private Set
'Usage
Dim instance As GetShipmentsResponse
Dim value As ReadOnlyCollection(Of Shipment)

value = instance.Shipments
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<Shipment> Shipments { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<Shipment^>^ Shipments {
    ReadOnlyCollection<Shipment^>^ get ();
    private: void set (ReadOnlyCollection<Shipment^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Shipment](shipment-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetShipmentsResponse Class](getshipmentsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

