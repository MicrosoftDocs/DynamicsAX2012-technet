---
title: GetReturnLocationTransactionServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetReturnLocationTransactionServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReturnLocationTransactionServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction,Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine,System.String,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getreturnlocationtransactionservicerequest.getreturnlocationtransactionservicerequest(v=AX.60)
ms:contentKeyID: 65322155
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReturnLocationTransactionServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetReturnLocationTransactionServiceRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    salesTransaction As SalesTransaction, _
    line As SalesLine, _
    reasonCodeId As String, _
    isInfoCode As Boolean _
)
'Usage
Dim salesTransaction As SalesTransaction
Dim line As SalesLine
Dim reasonCodeId As String
Dim isInfoCode As Boolean

Dim instance As New GetReturnLocationTransactionServiceRequest(salesTransaction, _
    line, reasonCodeId, isInfoCode)
```

``` csharp
public GetReturnLocationTransactionServiceRequest(
    SalesTransaction salesTransaction,
    SalesLine line,
    string reasonCodeId,
    bool isInfoCode
)
```

``` c++
public:
GetReturnLocationTransactionServiceRequest(
    SalesTransaction^ salesTransaction, 
    SalesLine^ line, 
    String^ reasonCodeId, 
    bool isInfoCode
)
```

#### Parameters

  - salesTransaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - line  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - reasonCodeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - isInfoCode  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[GetReturnLocationTransactionServiceRequest Class](getreturnlocationtransactionservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

