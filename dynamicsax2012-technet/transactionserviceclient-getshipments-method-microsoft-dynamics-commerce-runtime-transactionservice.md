---
title: TransactionServiceClient.GetShipments Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: GetShipments Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetShipments(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.getshipments(v=AX.60)
ms:contentKeyID: 62213298
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetShipments
dev_langs:
- CSharp
- C++
- VB
---

# GetShipments Method

Gets the shipments.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function GetShipments ( _
    salesId As String, _
    shipmentId As String _
) As ReadOnlyCollection(Of Shipment)
'Usage
Dim instance As TransactionServiceClient
Dim salesId As String
Dim shipmentId As String
Dim returnValue As ReadOnlyCollection(Of Shipment)

returnValue = instance.GetShipments(salesId, _
    shipmentId)
```

``` csharp
public ReadOnlyCollection<Shipment> GetShipments(
    string salesId,
    string shipmentId
)
```

``` c++
public:
ReadOnlyCollection<Shipment^>^ GetShipments(
    String^ salesId, 
    String^ shipmentId
)
```

#### Parameters

  - salesId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - shipmentId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Shipment](shipment-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
A collection of shiptment.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

