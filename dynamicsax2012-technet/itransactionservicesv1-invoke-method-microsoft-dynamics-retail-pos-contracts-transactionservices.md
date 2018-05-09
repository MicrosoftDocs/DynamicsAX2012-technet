---
title: ITransactionServicesV1.Invoke Method  (Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices)
TOCTitle: Invoke Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.Invoke(System.String,System.Object[])
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.transactionservices.itransactionservicesv1.invoke(v=AX.60)
ms:contentKeyID: 47129051
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.Invoke
dev_langs:
- CSharp
- C++
- VB
---

# Invoke Method

Invokes an extension method in Microsoft Dynamics AX through the transaction service.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function Invoke ( _
    methodName As String, _
    ParamArray parameters As Object() _
) As ReadOnlyCollection(Of Object)
'Usage
Dim instance As ITransactionServicesV1
Dim methodName As String
Dim parameters As Object()
Dim returnValue As ReadOnlyCollection(Of Object)

returnValue = instance.Invoke(methodName, _
    parameters)
```

``` csharp
ReadOnlyCollection<Object> Invoke(
    string methodName,
    params Object[] parameters
)
```

``` c++
ReadOnlyCollection<Object^>^ Invoke(
    String^ methodName, 
    ... array<Object^>^ parameters
)
```

#### Parameters

  - methodName  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - parameters  
    Type: [System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))\[\]  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))\>  
Results in a read-only collection of objects.  

## Remarks

External callers should use InvokeExtension instead.

## See Also

#### Reference

[ITransactionServicesV1 Interface](itransactionservicesv1-interface-microsoft-dynamics-retail-pos-contracts-transactionservices.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices Namespace](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)

