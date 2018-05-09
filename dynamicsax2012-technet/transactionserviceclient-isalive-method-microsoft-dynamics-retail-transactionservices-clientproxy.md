---
title: TransactionServiceClient.IsAlive Method  (Microsoft.Dynamics.Retail.TransactionServices.ClientProxy)
TOCTitle: IsAlive Method
ms:assetid: M:Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.TransactionServiceClient.IsAlive
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.transactionservices.clientproxy.transactionserviceclient.isalive(v=AX.60)
ms:contentKeyID: 49847806
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.TransactionServiceClient.IsAlive
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
Public Function IsAlive As ServiceResponse
'Usage
Dim instance As TransactionServiceClient
Dim returnValue As ServiceResponse

returnValue = instance.IsAlive()
```

``` csharp
public ServiceResponse IsAlive()
```

``` c++
public:
virtual ServiceResponse^ IsAlive() sealed
```

#### Return Value

Type: [Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.ServiceResponse](serviceresponse-class-microsoft-dynamics-retail-transactionservices-clientproxy.md)  
Returns [ServiceResponse](serviceresponse-class-microsoft-dynamics-retail-transactionservices-clientproxy.md).  

#### Implements

[ITransactionService.IsAlive()](itransactionservice-isalive-method-microsoft-dynamics-retail-transactionservices-clientproxy.md)  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-retail-transactionservices-clientproxy.md)

[Microsoft.Dynamics.Retail.TransactionServices.ClientProxy Namespace](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)

