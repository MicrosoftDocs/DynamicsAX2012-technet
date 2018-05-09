---
title: TransactionServiceClient Constructor (String, String) (Microsoft.Dynamics.Retail.TransactionServices.ClientProxy)
TOCTitle: TransactionServiceClient Constructor (String, String)
ms:assetid: M:Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.TransactionServiceClient.#ctor(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.transactionservices.clientproxy.transactionserviceclient.transactionserviceclient(v=AX.60)
ms:contentKeyID: 49845393
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# TransactionServiceClient Constructor (String, String)

**Namespace:**  [Microsoft.Dynamics.Retail.TransactionServices.ClientProxy](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    endpointConfigurationName As String, _
    remoteAddress As String _
)
'Usage
Dim endpointConfigurationName As String
Dim remoteAddress As String

Dim instance As New TransactionServiceClient(endpointConfigurationName, _
    remoteAddress)
```

``` csharp
public TransactionServiceClient(
    string endpointConfigurationName,
    string remoteAddress
)
```

``` c++
public:
TransactionServiceClient(
    String^ endpointConfigurationName, 
    String^ remoteAddress
)
```

#### Parameters

  - endpointConfigurationName  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - remoteAddress  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-retail-transactionservices-clientproxy.md)

[TransactionServiceClient Overload](transactionserviceclient-constructor-microsoft-dynamics-retail-transactionservices-clientproxy.md)

[Microsoft.Dynamics.Retail.TransactionServices.ClientProxy Namespace](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)

