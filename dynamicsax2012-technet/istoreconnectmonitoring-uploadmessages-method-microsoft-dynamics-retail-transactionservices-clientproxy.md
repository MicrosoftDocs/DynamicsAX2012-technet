---
title: IStoreConnectMonitoring.UploadMessages Method  (Microsoft.Dynamics.Retail.TransactionServices.ClientProxy)
TOCTitle: UploadMessages Method
ms:assetid: M:Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.IStoreConnectMonitoring.UploadMessages(Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.RequestInfo,System.Data.DataSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.transactionservices.clientproxy.istoreconnectmonitoring.uploadmessages(v=AX.60)
ms:contentKeyID: 49851975
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.IStoreConnectMonitoring.UploadMessages
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
<OperationContractAttribute(Action := "https://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/IStoreConnectMonitoring/UploadMessages",  _
    ReplyAction := "https://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/IStoreConnectMonitoring/UploadMessagesResponse")> _
<FaultContractAttribute(GetType(TrackedFault), Action := "https://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/TrackedFault",  _
    Name := "TrackedFault")> _
Sub UploadMessages ( _
    requestInfo As RequestInfo, _
    messages As DataSet _
)
'Usage
Dim instance As IStoreConnectMonitoring
Dim requestInfo As RequestInfo
Dim messages As DataSet

instance.UploadMessages(requestInfo, _
    messages)
```

``` csharp
[OperationContractAttribute(Action = "https://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/IStoreConnectMonitoring/UploadMessages", 
    ReplyAction = "https://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/IStoreConnectMonitoring/UploadMessagesResponse")]
[FaultContractAttribute(typeof(TrackedFault), Action = "https://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/TrackedFault", 
    Name = "TrackedFault")]
void UploadMessages(
    RequestInfo requestInfo,
    DataSet messages
)
```

``` c++
[OperationContractAttribute(Action = L"https://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/IStoreConnectMonitoring/UploadMessages", 
    ReplyAction = L"https://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/IStoreConnectMonitoring/UploadMessagesResponse")]
[FaultContractAttribute(typeof(TrackedFault), Action = L"https://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/TrackedFault", 
    Name = L"TrackedFault")]
void UploadMessages(
    RequestInfo^ requestInfo, 
    DataSet^ messages
)
```

#### Parameters

  - requestInfo  
    Type: [Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.RequestInfo](requestinfo-class-microsoft-dynamics-retail-transactionservices-clientproxy.md)  

<!-- end list -->

  - messages  
    Type: [System.Data.DataSet](https://technet.microsoft.com/library/bwy42y0e\(v=ax.60\))  

## See Also

#### Reference

[IStoreConnectMonitoring Interface](istoreconnectmonitoring-interface-microsoft-dynamics-retail-transactionservices-clientproxy.md)

[Microsoft.Dynamics.Retail.TransactionServices.ClientProxy Namespace](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)

