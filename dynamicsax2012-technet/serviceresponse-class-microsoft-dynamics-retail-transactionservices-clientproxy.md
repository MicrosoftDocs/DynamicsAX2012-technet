---
title: ServiceResponse Class (Microsoft.Dynamics.Retail.TransactionServices.ClientProxy)
TOCTitle: ServiceResponse Class
ms:assetid: T:Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.ServiceResponse
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.transactionservices.clientproxy.serviceresponse(v=AX.60)
ms:contentKeyID: 49847085
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.ServiceResponse
dev_langs:
- CSharp
- C++
- VB
---

# ServiceResponse Class

**Namespace:**  [Microsoft.Dynamics.Retail.TransactionServices.ClientProxy](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
<KnownTypeAttribute(GetType(Object()))> _
<KnownTypeAttribute(GetType(Exception))> _
<KnownTypeAttribute(GetType(RequestInfo))> _
<KnownTypeAttribute(GetType(TrackedFault))> _
<DataContractAttribute(Name := "ServiceResponse", Namespace := "http://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService")> _
<KnownTypeAttribute(GetType(Object()()))> _
Public Class ServiceResponse _
    Implements IExtensibleDataObject
'Usage
Dim instance As ServiceResponse
```

``` csharp
[KnownTypeAttribute(typeof(Object[]))]
[KnownTypeAttribute(typeof(Exception))]
[KnownTypeAttribute(typeof(RequestInfo))]
[KnownTypeAttribute(typeof(TrackedFault))]
[DataContractAttribute(Name = "ServiceResponse", Namespace = "http://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService")]
[KnownTypeAttribute(typeof(Object[][]))]
public class ServiceResponse : IExtensibleDataObject
```

``` c++
[KnownTypeAttribute(typeof(array<Object^>))]
[KnownTypeAttribute(typeof(Exception))]
[KnownTypeAttribute(typeof(RequestInfo))]
[KnownTypeAttribute(typeof(TrackedFault))]
[DataContractAttribute(Name = L"ServiceResponse", Namespace = L"http://schemas.microsoft.com/dynamics/2012/05/CommerceRuntime/TransactionService")]
[KnownTypeAttribute(typeof(array<array<Object^>^>))]
public ref class ServiceResponse : IExtensibleDataObject
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.ServiceResponse  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.TransactionServices.ClientProxy Namespace](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)

