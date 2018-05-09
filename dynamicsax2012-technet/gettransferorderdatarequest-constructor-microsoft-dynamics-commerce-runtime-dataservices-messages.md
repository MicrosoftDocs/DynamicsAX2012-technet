---
title: GetTransferOrderDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetTransferOrderDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTransferOrderDataRequest.#ctor(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.gettransferorderdatarequest.gettransferorderdatarequest(v=AX.60)
ms:contentKeyID: 65320761
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTransferOrderDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetTransferOrderDataRequest Constructor

Initializes a new instance of the [GetTransferOrderDataRequest](gettransferorderdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    orderId As String, _
    settings As QueryResultSettings _
)
'Usage
Dim orderId As String
Dim settings As QueryResultSettings

Dim instance As New GetTransferOrderDataRequest(orderId, _
    settings)
```

``` csharp
public GetTransferOrderDataRequest(
    string orderId,
    QueryResultSettings settings
)
```

``` c++
public:
GetTransferOrderDataRequest(
    String^ orderId, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - orderId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetTransferOrderDataRequest Class](gettransferorderdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

