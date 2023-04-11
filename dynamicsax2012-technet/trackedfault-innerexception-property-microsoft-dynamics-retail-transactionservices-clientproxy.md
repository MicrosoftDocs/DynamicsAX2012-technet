---
title: TrackedFault.InnerException Property  (Microsoft.Dynamics.Retail.TransactionServices.ClientProxy)
TOCTitle: InnerException Property
ms:assetid: P:Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.TrackedFault.InnerException
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.transactionservices.clientproxy.trackedfault.innerexception(v=AX.60)
ms:contentKeyID: 49832338
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.TrackedFault.InnerException
dev_langs:
- CSharp
- C++
- VB
---

# InnerException Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.TransactionServices.ClientProxy](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property InnerException As Exception
    Get
    Set
'Usage
Dim instance As TrackedFault
Dim value As Exception

value = instance.InnerException

instance.InnerException = value
```

``` csharp
[DataMemberAttribute]
public Exception InnerException { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Exception^ InnerException {
    Exception^ get ();
    void set (Exception^ value);
}
```

#### Property Value

Type: [System.Exception](https://technet.microsoft.com/library/c18k6c59\(v=ax.60\))  
Returns [Exception](https://technet.microsoft.com/library/c18k6c59\(v=ax.60\)).  

## See Also

#### Reference

[TrackedFault Class](trackedfault-class-microsoft-dynamics-retail-transactionservices-clientproxy.md)

[Microsoft.Dynamics.Retail.TransactionServices.ClientProxy Namespace](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)

