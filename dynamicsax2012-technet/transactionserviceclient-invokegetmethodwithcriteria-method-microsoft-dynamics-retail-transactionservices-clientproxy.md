---
title: TransactionServiceClient.InvokeGetMethodWithCriteria Method  (Microsoft.Dynamics.Retail.TransactionServices.ClientProxy)
TOCTitle: InvokeGetMethodWithCriteria Method
ms:assetid: M:Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.TransactionServiceClient.InvokeGetMethodWithCriteria(Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.RequestInfo,System.String,System.String,System.Object[])
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.transactionservices.clientproxy.transactionserviceclient.invokegetmethodwithcriteria(v=AX.60)
ms:contentKeyID: 49846677
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.TransactionServiceClient.InvokeGetMethodWithCriteria
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
Public Function InvokeGetMethodWithCriteria ( _
    requestInfo As RequestInfo, _
    methodName As String, _
    filterCriteria As String, _
    parameters As Object() _
) As ServiceResponse
'Usage
Dim instance As TransactionServiceClient
Dim requestInfo As RequestInfo
Dim methodName As String
Dim filterCriteria As String
Dim parameters As Object()
Dim returnValue As ServiceResponse

returnValue = instance.InvokeGetMethodWithCriteria(requestInfo, _
    methodName, filterCriteria, parameters)
```

``` csharp
public ServiceResponse InvokeGetMethodWithCriteria(
    RequestInfo requestInfo,
    string methodName,
    string filterCriteria,
    Object[] parameters
)
```

``` c++
public:
virtual ServiceResponse^ InvokeGetMethodWithCriteria(
    RequestInfo^ requestInfo, 
    String^ methodName, 
    String^ filterCriteria, 
    array<Object^>^ parameters
) sealed
```

#### Parameters

  - requestInfo  
    Type: [Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.RequestInfo](requestinfo-class-microsoft-dynamics-retail-transactionservices-clientproxy.md)  

<!-- end list -->

  - methodName  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - filterCriteria  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - parameters  
    Type: [System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))\[\]  

#### Return Value

Type: [Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.ServiceResponse](serviceresponse-class-microsoft-dynamics-retail-transactionservices-clientproxy.md)  
Returns [ServiceResponse](serviceresponse-class-microsoft-dynamics-retail-transactionservices-clientproxy.md).  

#### Implements

[ITransactionService.InvokeGetMethodWithCriteria(RequestInfo, String, String, Object\[\])](itransactionservice-invokegetmethodwithcriteria-method-microsoft-dynamics-retail-transactionservices-clientproxy.md)  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-retail-transactionservices-clientproxy.md)

[Microsoft.Dynamics.Retail.TransactionServices.ClientProxy Namespace](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)

