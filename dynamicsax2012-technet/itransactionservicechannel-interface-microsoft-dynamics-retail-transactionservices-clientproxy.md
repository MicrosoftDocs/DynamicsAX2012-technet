---
title: ITransactionServiceChannel Interface (Microsoft.Dynamics.Retail.TransactionServices.ClientProxy)
TOCTitle: ITransactionServiceChannel Interface
ms:assetid: T:Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.ITransactionServiceChannel
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.transactionservices.clientproxy.itransactionservicechannel(v=AX.60)
ms:contentKeyID: 49840735
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.ITransactionServiceChannel
dev_langs:
- CSharp
- C++
- VB
---

# ITransactionServiceChannel Interface

**Namespace:**  [Microsoft.Dynamics.Retail.TransactionServices.ClientProxy](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Interface ITransactionServiceChannel _
    Inherits ITransactionService, IClientChannel, IContextChannel, IChannel,  _
    ICommunicationObject, IExtensibleObject(Of IContextChannel), IDisposable
'Usage
Dim instance As ITransactionServiceChannel
```

``` csharp
public interface ITransactionServiceChannel : ITransactionService, 
    IClientChannel, IContextChannel, IChannel, ICommunicationObject, IExtensibleObject<IContextChannel>, 
    IDisposable
```

``` c++
public interface class ITransactionServiceChannel : ITransactionService, 
    IClientChannel, IContextChannel, IChannel, ICommunicationObject, IExtensibleObject<IContextChannel^>, 
    IDisposable
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.TransactionServices.ClientProxy Namespace](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)

