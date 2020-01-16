---
title: TransactionServiceClient Constructor (Binding, EndpointAddress) (Microsoft.Dynamics.Retail.TransactionServices.ClientProxy)
TOCTitle: TransactionServiceClient Constructor (Binding, EndpointAddress)
ms:assetid: M:Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.TransactionServiceClient.#ctor(System.ServiceModel.Channels.Binding,System.ServiceModel.EndpointAddress)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.transactionservices.clientproxy.transactionserviceclient.transactionserviceclient(v=AX.60)
ms:contentKeyID: 49847820
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# TransactionServiceClient Constructor (Binding, EndpointAddress)

**Namespace:**  [Microsoft.Dynamics.Retail.TransactionServices.ClientProxy](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    binding As Binding, _
    remoteAddress As EndpointAddress _
)
'Usage
Dim binding As Binding
Dim remoteAddress As EndpointAddress

Dim instance As New TransactionServiceClient(binding, _
    remoteAddress)
```

``` csharp
public TransactionServiceClient(
    Binding binding,
    EndpointAddress remoteAddress
)
```

``` c++
public:
TransactionServiceClient(
    Binding^ binding, 
    EndpointAddress^ remoteAddress
)
```

#### Parameters

  - binding  
    Type: [System.ServiceModel.Channels.Binding](https://technet.microsoft.com/library/ms405791\(v=ax.60\))  

<!-- end list -->

  - remoteAddress  
    Type: [System.ServiceModel.EndpointAddress](https://technet.microsoft.com/library/ms405980\(v=ax.60\))  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-retail-transactionservices-clientproxy.md)

[TransactionServiceClient Overload](transactionserviceclient-constructor-microsoft-dynamics-retail-transactionservices-clientproxy.md)

[Microsoft.Dynamics.Retail.TransactionServices.ClientProxy Namespace](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)

