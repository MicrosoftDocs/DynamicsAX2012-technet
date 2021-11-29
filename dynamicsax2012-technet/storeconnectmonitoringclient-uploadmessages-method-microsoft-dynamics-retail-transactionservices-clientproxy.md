---
title: StoreConnectMonitoringClient.UploadMessages Method  (Microsoft.Dynamics.Retail.TransactionServices.ClientProxy)
TOCTitle: UploadMessages Method
ms:assetid: M:Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.StoreConnectMonitoringClient.UploadMessages(Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.RequestInfo,System.Data.DataSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.transactionservices.clientproxy.storeconnectmonitoringclient.uploadmessages(v=AX.60)
ms:contentKeyID: 49844935
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.StoreConnectMonitoringClient.UploadMessages
dev_langs:
- CSharp
- C++
- VB
---

# UploadMessages Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.TransactionServices.ClientProxy](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Sub UploadMessages ( _
    requestInfo As RequestInfo, _
    messages As DataSet _
)
'Usage
Dim instance As StoreConnectMonitoringClient
Dim requestInfo As RequestInfo
Dim messages As DataSet

instance.UploadMessages(requestInfo, _
    messages)
```

``` csharp
public void UploadMessages(
    RequestInfo requestInfo,
    DataSet messages
)
```

``` c++
public:
virtual void UploadMessages(
    RequestInfo^ requestInfo, 
    DataSet^ messages
) sealed
```

#### Parameters

  - requestInfo  
    Type: [Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.RequestInfo](requestinfo-class-microsoft-dynamics-retail-transactionservices-clientproxy.md)  

<!-- end list -->

  - messages  
    Type: [System.Data.DataSet](https://technet.microsoft.com/library/bwy42y0e\(v=ax.60\))  

#### Implements

[IStoreConnectMonitoring.UploadMessages(RequestInfo, DataSet)](istoreconnectmonitoring-uploadmessages-method-microsoft-dynamics-retail-transactionservices-clientproxy.md)  

## See Also

#### Reference

[StoreConnectMonitoringClient Class](storeconnectmonitoringclient-class-microsoft-dynamics-retail-transactionservices-clientproxy.md)

[Microsoft.Dynamics.Retail.TransactionServices.ClientProxy Namespace](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)

