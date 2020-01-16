---
title: ITransactionService.InvokeExtensionGetMethodWithCriteria Method  (Microsoft.Dynamics.Retail.TransactionServices.ClientProxy)
TOCTitle: InvokeExtensionGetMethodWithCriteria Method
ms:assetid: M:Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.ITransactionService.InvokeExtensionGetMethodWithCriteria(Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.RequestInfo,System.String,System.String,System.Object[])
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.transactionservices.clientproxy.itransactionservice.invokeextensiongetmethodwithcriteria(v=AX.60)
ms:contentKeyID: 49820228
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.ITransactionService.InvokeExtensionGetMethodWithCriteria
dev_langs:
- CSharp
- C++
- VB
---

# InvokeExtensionGetMethodWithCriteria Method

**Namespace:**  [Microsoft.Dynamics.Retail.TransactionServices.ClientProxy](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
<FaultContractAttribute(GetType(TrackedFault), Action := "http://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/TrackedFault",  _
    Name := "TrackedFault")> _
<ServiceKnownTypeAttribute(GetType(ReadOnlyCollection(Of Object)))> _
<OperationContractAttribute(Action := "http://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/InvokeExtensionGetMethodWithCriteria",  _
    ReplyAction := "http://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/InvokeExtensionGetMethodWithCriteriaResponse")> _
<ServiceKnownTypeAttribute(GetType(ServiceResponse))> _
<ServiceKnownTypeAttribute(GetType(TrackedFault))> _
<ServiceKnownTypeAttribute(GetType(RequestInfo))> _
<ServiceKnownTypeAttribute(GetType(Object()))> _
<ServiceKnownTypeAttribute(GetType(Object()()))> _
<ServiceKnownTypeAttribute(GetType(Exception))> _
Function InvokeExtensionGetMethodWithCriteria ( _
    requestInfo As RequestInfo, _
    methodName As String, _
    filterCriteria As String, _
    parameters As Object() _
) As ServiceResponse
'Usage
Dim instance As ITransactionService
Dim requestInfo As RequestInfo
Dim methodName As String
Dim filterCriteria As String
Dim parameters As Object()
Dim returnValue As ServiceResponse

returnValue = instance.InvokeExtensionGetMethodWithCriteria(requestInfo, _
    methodName, filterCriteria, parameters)
```

``` csharp
[FaultContractAttribute(typeof(TrackedFault), Action = "http://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/TrackedFault", 
    Name = "TrackedFault")]
[ServiceKnownTypeAttribute(typeof(ReadOnlyCollection<Object>))]
[OperationContractAttribute(Action = "http://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/InvokeExtensionGetMethodWithCriteria", 
    ReplyAction = "http://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/InvokeExtensionGetMethodWithCriteriaResponse")]
[ServiceKnownTypeAttribute(typeof(ServiceResponse))]
[ServiceKnownTypeAttribute(typeof(TrackedFault))]
[ServiceKnownTypeAttribute(typeof(RequestInfo))]
[ServiceKnownTypeAttribute(typeof(Object[]))]
[ServiceKnownTypeAttribute(typeof(Object[][]))]
[ServiceKnownTypeAttribute(typeof(Exception))]
ServiceResponse InvokeExtensionGetMethodWithCriteria(
    RequestInfo requestInfo,
    string methodName,
    string filterCriteria,
    Object[] parameters
)
```

``` c++
[FaultContractAttribute(typeof(TrackedFault), Action = L"http://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/TrackedFault", 
    Name = L"TrackedFault")]
[ServiceKnownTypeAttribute(typeof(ReadOnlyCollection<Object^>))]
[OperationContractAttribute(Action = L"http://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/InvokeExtensionGetMethodWithCriteria", 
    ReplyAction = L"http://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/InvokeExtensionGetMethodWithCriteriaResponse")]
[ServiceKnownTypeAttribute(typeof(ServiceResponse))]
[ServiceKnownTypeAttribute(typeof(TrackedFault))]
[ServiceKnownTypeAttribute(typeof(RequestInfo))]
[ServiceKnownTypeAttribute(typeof(array<Object^>))]
[ServiceKnownTypeAttribute(typeof(array<array<Object^>^>))]
[ServiceKnownTypeAttribute(typeof(Exception))]
ServiceResponse^ InvokeExtensionGetMethodWithCriteria(
    RequestInfo^ requestInfo, 
    String^ methodName, 
    String^ filterCriteria, 
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

  - filterCriteria  
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

