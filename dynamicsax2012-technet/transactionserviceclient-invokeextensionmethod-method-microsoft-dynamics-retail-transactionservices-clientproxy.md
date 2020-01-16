---
title: TransactionServiceClient.InvokeExtensionMethod Method  (Microsoft.Dynamics.Retail.TransactionServices.ClientProxy)
TOCTitle: InvokeExtensionMethod Method
ms:assetid: M:Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.TransactionServiceClient.InvokeExtensionMethod(Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.RequestInfo,System.String,System.Object[])
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.transactionservices.clientproxy.transactionserviceclient.invokeextensionmethod(v=AX.60)
ms:contentKeyID: 49830288
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.TransactionServiceClient.InvokeExtensionMethod
dev_langs:
- CSharp
- C++
- VB
---

# InvokeExtensionMethod Method

**Namespace:**  [Microsoft.Dynamics.Retail.TransactionServices.ClientProxy](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function InvokeExtensionMethod ( _
    requestInfo As RequestInfo, _
    methodName As String, _
    parameters As Object() _
) As ServiceResponse
'Usage
Dim instance As TransactionServiceClient
Dim requestInfo As RequestInfo
Dim methodName As String
Dim parameters As Object()
Dim returnValue As ServiceResponse

returnValue = instance.InvokeExtensionMethod(requestInfo, _
    methodName, parameters)
```

``` csharp
public ServiceResponse InvokeExtensionMethod(
    RequestInfo requestInfo,
    string methodName,
    Object[] parameters
)
```

``` c++
public:
virtual ServiceResponse^ InvokeExtensionMethod(
    RequestInfo^ requestInfo, 
    String^ methodName, 
    array<Object^>^ parameters
) sealed
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

#### Implements

[ITransactionService.InvokeExtensionMethod(RequestInfo, String, Object\[\])](itransactionservice-invokeextensionmethod-method-microsoft-dynamics-retail-transactionservices-clientproxy.md)  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-retail-transactionservices-clientproxy.md)

[Microsoft.Dynamics.Retail.TransactionServices.ClientProxy Namespace](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)

