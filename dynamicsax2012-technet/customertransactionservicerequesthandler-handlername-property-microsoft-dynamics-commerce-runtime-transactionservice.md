---
title: CustomerTransactionServiceRequestHandler.HandlerName Property  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: HandlerName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.TransactionService.CustomerTransactionServiceRequestHandler.HandlerName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.customertransactionservicerequesthandler.handlername(v=AX.60)
ms:contentKeyID: 65317419
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.CustomerTransactionServiceRequestHandler.HandlerName
dev_langs:
- CSharp
- C++
- VB
---

# HandlerName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property HandlerName As String
    Get
'Usage
Dim instance As CustomerTransactionServiceRequestHandler
Dim value As String

value = instance.HandlerName
```

``` csharp
public string HandlerName { get; }
```

``` c++
public:
virtual property String^ HandlerName {
    String^ get () sealed;
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Implements

[INamedRequestHandler.HandlerName](inamedrequesthandler-handlername-property-microsoft-dynamics-commerce-runtime-handlers.md)  

## See Also

#### Reference

[CustomerTransactionServiceRequestHandler Class](customertransactionservicerequesthandler-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

