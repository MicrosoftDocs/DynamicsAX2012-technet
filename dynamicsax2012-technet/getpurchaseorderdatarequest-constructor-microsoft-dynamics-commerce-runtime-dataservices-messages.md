---
title: GetPurchaseOrderDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetPurchaseOrderDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPurchaseOrderDataRequest.#ctor(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getpurchaseorderdatarequest.getpurchaseorderdatarequest(v=AX.60)
ms:contentKeyID: 65316914
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPurchaseOrderDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetPurchaseOrderDataRequest Constructor

Initializes a new instance of the [GetPurchaseOrderDataRequest](getpurchaseorderdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

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

Dim instance As New GetPurchaseOrderDataRequest(orderId, _
    settings)
```

``` csharp
public GetPurchaseOrderDataRequest(
    string orderId,
    QueryResultSettings settings
)
```

``` c++
public:
GetPurchaseOrderDataRequest(
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

[GetPurchaseOrderDataRequest Class](getpurchaseorderdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

