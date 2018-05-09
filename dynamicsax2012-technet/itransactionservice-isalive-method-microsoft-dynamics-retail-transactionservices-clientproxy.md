---
title: ITransactionService.IsAlive Method  (Microsoft.Dynamics.Retail.TransactionServices.ClientProxy)
TOCTitle: IsAlive Method
ms:assetid: M:Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.ITransactionService.IsAlive
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.transactionservices.clientproxy.itransactionservice.isalive(v=AX.60)
ms:contentKeyID: 49832045
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
<FaultContractAttribute(GetType(TrackedFault), Action := "http://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/TrackedFault",  _
    Name := "TrackedFault")> _
<OperationContractAttribute(Action := "http://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/IsAlive",  _
    ReplyAction := "http://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/IsAliveResponse")> _
Function IsAlive As ServiceResponse
'Usage
Dim instance As ITransactionService
Dim returnValue As ServiceResponse

returnValue = instance.IsAlive()
```

``` csharp
[FaultContractAttribute(typeof(TrackedFault), Action = "http://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/TrackedFault", 
    Name = "TrackedFault")]
[OperationContractAttribute(Action = "http://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/IsAlive", 
    ReplyAction = "http://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/IsAliveResponse")]
ServiceResponse IsAlive()
```

``` c++
[FaultContractAttribute(typeof(TrackedFault), Action = L"http://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/TrackedFault", 
    Name = L"TrackedFault")]
[OperationContractAttribute(Action = L"http://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/IsAlive", 
    ReplyAction = L"http://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/IsAliveResponse")]
ServiceResponse^ IsAlive()
```

#### Return Value

Type: [Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.ServiceResponse](serviceresponse-class-microsoft-dynamics-retail-transactionservices-clientproxy.md)  
Returns [ServiceResponse](serviceresponse-class-microsoft-dynamics-retail-transactionservices-clientproxy.md).  

## See Also

#### Reference

[ITransactionService Interface](itransactionservice-interface-microsoft-dynamics-retail-transactionservices-clientproxy.md)

[Microsoft.Dynamics.Retail.TransactionServices.ClientProxy Namespace](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)

