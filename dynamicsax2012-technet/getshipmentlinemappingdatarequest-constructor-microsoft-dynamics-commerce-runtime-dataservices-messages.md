---
title: GetShipmentLineMappingDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetShipmentLineMappingDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetShipmentLineMappingDataRequest.#ctor(System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getshipmentlinemappingdatarequest.getshipmentlinemappingdatarequest(v=AX.60)
ms:contentKeyID: 65315556
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetShipmentLineMappingDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetShipmentLineMappingDataRequest Constructor

Initializes a new instance of the [GetShipmentLineMappingDataRequest](getshipmentlinemappingdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    salesOrderIds As IEnumerable(Of String) _
)
'Usage
Dim salesOrderIds As IEnumerable(Of String)

Dim instance As New GetShipmentLineMappingDataRequest(salesOrderIds)
```

``` csharp
public GetShipmentLineMappingDataRequest(
    IEnumerable<string> salesOrderIds
)
```

``` c++
public:
GetShipmentLineMappingDataRequest(
    IEnumerable<String^>^ salesOrderIds
)
```

#### Parameters

  - salesOrderIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

## See Also

#### Reference

[GetShipmentLineMappingDataRequest Class](getshipmentlinemappingdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

