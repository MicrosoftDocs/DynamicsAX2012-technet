---
title: ITransactionService.InvokeGetMethodWithCriteria Method  (Microsoft.Dynamics.Retail.TransactionServices.ClientProxy)
TOCTitle: InvokeGetMethodWithCriteria Method
ms:assetid: M:Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.ITransactionService.InvokeGetMethodWithCriteria(Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.RequestInfo,System.String,System.String,System.Object[])
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.transactionservices.clientproxy.itransactionservice.invokegetmethodwithcriteria(v=AX.60)
ms:contentKeyID: 49847050
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.ITransactionService.InvokeGetMethodWithCriteria
dev_langs:
- CSharp
- C++
- VB
---

# InvokeGetMethodWithCriteria Method

**Namespace:**  [Microsoft.Dynamics.Retail.TransactionServices.ClientProxy](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
<ServiceKnownTypeAttribute(GetType(Object()))> _
<ServiceKnownTypeAttribute(GetType(ReadOnlyCollection(Of Object)))> _
<FaultContractAttribute(GetType(TrackedFault), Action := "http://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/TrackedFault",  _
    Name := "TrackedFault")> _
<ServiceKnownTypeAttribute(GetType(ServiceResponse))> _
<ServiceKnownTypeAttribute(GetType(TrackedFault))> _
<ServiceKnownTypeAttribute(GetType(RequestInfo))> _
<OperationContractAttribute(Action := "http://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/InvokeGetMethodWithCriteria",  _
    ReplyAction := "http://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/InvokeGetMethodWithCriteriaResponse")> _
<ServiceKnownTypeAttribute(GetType(Object()()))> _
<ServiceKnownTypeAttribute(GetType(Exception))> _
Function InvokeGetMethodWithCriteria ( _
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

returnValue = instance.InvokeGetMethodWithCriteria(requestInfo, _
    methodName, filterCriteria, parameters)
```

``` csharp
[ServiceKnownTypeAttribute(typeof(Object[]))]
[ServiceKnownTypeAttribute(typeof(ReadOnlyCollection<Object>))]
[FaultContractAttribute(typeof(TrackedFault), Action = "http://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/TrackedFault", 
    Name = "TrackedFault")]
[ServiceKnownTypeAttribute(typeof(ServiceResponse))]
[ServiceKnownTypeAttribute(typeof(TrackedFault))]
[ServiceKnownTypeAttribute(typeof(RequestInfo))]
[OperationContractAttribute(Action = "http://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/InvokeGetMethodWithCriteria", 
    ReplyAction = "http://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/InvokeGetMethodWithCriteriaResponse")]
[ServiceKnownTypeAttribute(typeof(Object[][]))]
[ServiceKnownTypeAttribute(typeof(Exception))]
ServiceResponse InvokeGetMethodWithCriteria(
    RequestInfo requestInfo,
    string methodName,
    string filterCriteria,
    Object[] parameters
)
```

``` c++
[ServiceKnownTypeAttribute(typeof(array<Object^>))]
[ServiceKnownTypeAttribute(typeof(ReadOnlyCollection<Object^>))]
[FaultContractAttribute(typeof(TrackedFault), Action = L"http://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/TrackedFault", 
    Name = L"TrackedFault")]
[ServiceKnownTypeAttribute(typeof(ServiceResponse))]
[ServiceKnownTypeAttribute(typeof(TrackedFault))]
[ServiceKnownTypeAttribute(typeof(RequestInfo))]
[OperationContractAttribute(Action = L"http://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/InvokeGetMethodWithCriteria", 
    ReplyAction = L"http://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService/ITransactionService/InvokeGetMethodWithCriteriaResponse")]
[ServiceKnownTypeAttribute(typeof(array<array<Object^>^>))]
[ServiceKnownTypeAttribute(typeof(Exception))]
ServiceResponse^ InvokeGetMethodWithCriteria(
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

