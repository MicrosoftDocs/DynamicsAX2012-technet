---
title: ITransactionService.IsAlive Method  (Microsoft.Dynamics.Retail.TransactionServices.ClientProxy)
TOCTitle: IsAlive Method
ms:assetid: M:Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.ITransactionService.IsAlive
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.transactionservices.clientproxy.itransactionservice.isalive(v=AX.60)
ms:contentKeyID: 49832045
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.ITransactionService.IsAlive
dev_langs:
- CSharp
- C++
- VB
---

# IsAlive Method

**Namespace:**  [Microsoft.Dynamics.Retail.TransactionServices.ClientProxy](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
<FaultContractAttribute(GetType(TrackedFault), Action := "https://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/TrackedFault",  _
    Name := "TrackedFault")> _
<OperationContractAttribute(Action := "https://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/IsAlive",  _
    ReplyAction := "https://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/IsAliveResponse")> _
Function IsAlive As ServiceResponse
'Usage
Dim instance As ITransactionService
Dim returnValue As ServiceResponse

returnValue = instance.IsAlive()
```

``` csharp
[FaultContractAttribute(typeof(TrackedFault), Action = "https://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/TrackedFault", 
    Name = "TrackedFault")]
[OperationContractAttribute(Action = "https://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/IsAlive", 
    ReplyAction = "https://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/IsAliveResponse")]
ServiceResponse IsAlive()
```

``` c++
[FaultContractAttribute(typeof(TrackedFault), Action = L"https://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/TrackedFault", 
    Name = L"TrackedFault")]
[OperationContractAttribute(Action = L"https://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/IsAlive", 
    ReplyAction = L"https://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/IsAliveResponse")]
ServiceResponse^ IsAlive()
```

#### Return Value

Type: [Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.ServiceResponse](serviceresponse-class-microsoft-dynamics-retail-transactionservices-clientproxy.md)  
Returns [ServiceResponse](serviceresponse-class-microsoft-dynamics-retail-transactionservices-clientproxy.md).  

## See Also

#### Reference

[ITransactionService Interface](itransactionservice-interface-microsoft-dynamics-retail-transactionservices-clientproxy.md)

[Microsoft.Dynamics.Retail.TransactionServices.ClientProxy Namespace](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)

