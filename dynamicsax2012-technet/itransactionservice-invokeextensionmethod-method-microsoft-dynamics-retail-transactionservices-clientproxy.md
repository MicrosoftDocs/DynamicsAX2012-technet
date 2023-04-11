---
title: ITransactionService.InvokeExtensionMethod Method  (Microsoft.Dynamics.Retail.TransactionServices.ClientProxy)
TOCTitle: InvokeExtensionMethod Method
ms:assetid: M:Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.ITransactionService.InvokeExtensionMethod(Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.RequestInfo,System.String,System.Object[])
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.transactionservices.clientproxy.itransactionservice.invokeextensionmethod(v=AX.60)
ms:contentKeyID: 49848687
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.ITransactionService.InvokeExtensionMethod
dev_langs:
- CSharp
- C++
- VB
---

# InvokeExtensionMethod Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.TransactionServices.ClientProxy](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute(Action := "https://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/InvokeExtensionMethod",  _
    ReplyAction := "https://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/InvokeExtensionMethodResponse")> _
<ServiceKnownTypeAttribute(GetType(TrackedFault))> _
<ServiceKnownTypeAttribute(GetType(RequestInfo))> _
<ServiceKnownTypeAttribute(GetType(Object()))> _
<ServiceKnownTypeAttribute(GetType(Object()()))> _
<ServiceKnownTypeAttribute(GetType(Exception))> _
<ServiceKnownTypeAttribute(GetType(ReadOnlyCollection(Of Object)))> _
<FaultContractAttribute(GetType(TrackedFault), Action := "https://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/TrackedFault",  _
    Name := "TrackedFault")> _
<ServiceKnownTypeAttribute(GetType(ServiceResponse))> _
Function InvokeExtensionMethod ( _
    requestInfo As RequestInfo, _
    methodName As String, _
    parameters As Object() _
) As ServiceResponse
'Usage
Dim instance As ITransactionService
Dim requestInfo As RequestInfo
Dim methodName As String
Dim parameters As Object()
Dim returnValue As ServiceResponse

returnValue = instance.InvokeExtensionMethod(requestInfo, _
    methodName, parameters)
```

``` csharp
[OperationContractAttribute(Action = "https://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/InvokeExtensionMethod", 
    ReplyAction = "https://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/InvokeExtensionMethodResponse")]
[ServiceKnownTypeAttribute(typeof(TrackedFault))]
[ServiceKnownTypeAttribute(typeof(RequestInfo))]
[ServiceKnownTypeAttribute(typeof(Object[]))]
[ServiceKnownTypeAttribute(typeof(Object[][]))]
[ServiceKnownTypeAttribute(typeof(Exception))]
[ServiceKnownTypeAttribute(typeof(ReadOnlyCollection<Object>))]
[FaultContractAttribute(typeof(TrackedFault), Action = "https://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/TrackedFault", 
    Name = "TrackedFault")]
[ServiceKnownTypeAttribute(typeof(ServiceResponse))]
ServiceResponse InvokeExtensionMethod(
    RequestInfo requestInfo,
    string methodName,
    Object[] parameters
)
```

``` c++
[OperationContractAttribute(Action = L"https://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/InvokeExtensionMethod", 
    ReplyAction = L"https://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/InvokeExtensionMethodResponse")]
[ServiceKnownTypeAttribute(typeof(TrackedFault))]
[ServiceKnownTypeAttribute(typeof(RequestInfo))]
[ServiceKnownTypeAttribute(typeof(array<Object^>))]
[ServiceKnownTypeAttribute(typeof(array<array<Object^>^>))]
[ServiceKnownTypeAttribute(typeof(Exception))]
[ServiceKnownTypeAttribute(typeof(ReadOnlyCollection<Object^>))]
[FaultContractAttribute(typeof(TrackedFault), Action = L"https://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/TrackedFault", 
    Name = L"TrackedFault")]
[ServiceKnownTypeAttribute(typeof(ServiceResponse))]
ServiceResponse^ InvokeExtensionMethod(
    RequestInfo^ requestInfo, 
    String^ methodName, 
    array<Object^>^ parameters
)
```

#### Parameters

  - requestInfo  
    Type: [Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.RequestInfo](requestinfo-class-microsoft-dynamics-retail-transactionservices-clientproxy.md)  

<!-- end list -->

  - methodName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - parameters  
    Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))\[\]  

#### Return Value

Type: [Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.ServiceResponse](serviceresponse-class-microsoft-dynamics-retail-transactionservices-clientproxy.md)  
Returns [ServiceResponse](serviceresponse-class-microsoft-dynamics-retail-transactionservices-clientproxy.md).  

## See Also

#### Reference

[ITransactionService Interface](itransactionservice-interface-microsoft-dynamics-retail-transactionservices-clientproxy.md)

[Microsoft.Dynamics.Retail.TransactionServices.ClientProxy Namespace](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)

