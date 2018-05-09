---
title: GetReturnLocationTransactionServiceResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetReturnLocationTransactionServiceResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReturnLocationTransactionServiceResponse.#ctor(System.Boolean,System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getreturnlocationtransactionserviceresponse.getreturnlocationtransactionserviceresponse(v=AX.60)
ms:contentKeyID: 65322185
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReturnLocationTransactionServiceResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetReturnLocationTransactionServiceResponse Constructor

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    printReturnLabel As Boolean, _
    returnWarehouseText As String, _
    returnLocationText As String, _
    returnPalleteText As String _
)
'Usage
Dim printReturnLabel As Boolean
Dim returnWarehouseText As String
Dim returnLocationText As String
Dim returnPalleteText As String

Dim instance As New GetReturnLocationTransactionServiceResponse(printReturnLabel, _
    returnWarehouseText, returnLocationText, _
    returnPalleteText)
```

``` csharp
public GetReturnLocationTransactionServiceResponse(
    bool printReturnLabel,
    string returnWarehouseText,
    string returnLocationText,
    string returnPalleteText
)
```

``` c++
public:
GetReturnLocationTransactionServiceResponse(
    bool printReturnLabel, 
    String^ returnWarehouseText, 
    String^ returnLocationText, 
    String^ returnPalleteText
)
```

#### Parameters

  - printReturnLabel  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - returnWarehouseText  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - returnLocationText  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - returnPalleteText  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetReturnLocationTransactionServiceResponse Class](getreturnlocationtransactionserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

