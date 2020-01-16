---
title: StoreConnectMonitoringClient Constructor (String, EndpointAddress) (Microsoft.Dynamics.Retail.TransactionServices.ClientProxy)
TOCTitle: StoreConnectMonitoringClient Constructor (String, EndpointAddress)
ms:assetid: M:Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.StoreConnectMonitoringClient.#ctor(System.String,System.ServiceModel.EndpointAddress)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.transactionservices.clientproxy.storeconnectmonitoringclient.storeconnectmonitoringclient(v=AX.60)
ms:contentKeyID: 49844451
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# StoreConnectMonitoringClient Constructor (String, EndpointAddress)

**Namespace:**  [Microsoft.Dynamics.Retail.TransactionServices.ClientProxy](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    endpointConfigurationName As String, _
    remoteAddress As EndpointAddress _
)
'Usage
Dim endpointConfigurationName As String
Dim remoteAddress As EndpointAddress

Dim instance As New StoreConnectMonitoringClient(endpointConfigurationName, _
    remoteAddress)
```

``` csharp
public StoreConnectMonitoringClient(
    string endpointConfigurationName,
    EndpointAddress remoteAddress
)
```

``` c++
public:
StoreConnectMonitoringClient(
    String^ endpointConfigurationName, 
    EndpointAddress^ remoteAddress
)
```

#### Parameters

  - endpointConfigurationName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - remoteAddress  
    Type: [System.ServiceModel.EndpointAddress](https://technet.microsoft.com/library/ms405980\(v=ax.60\))  

## See Also

#### Reference

[StoreConnectMonitoringClient Class](storeconnectmonitoringclient-class-microsoft-dynamics-retail-transactionservices-clientproxy.md)

[StoreConnectMonitoringClient Overload](storeconnectmonitoringclient-constructor-microsoft-dynamics-retail-transactionservices-clientproxy.md)

[Microsoft.Dynamics.Retail.TransactionServices.ClientProxy Namespace](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)

