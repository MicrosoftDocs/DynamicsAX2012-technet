---
title: TrackedFault.Timestamp Property  (Microsoft.Dynamics.Retail.TransactionServices.ClientProxy)
TOCTitle: Timestamp Property
ms:assetid: P:Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.TrackedFault.Timestamp
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.transactionservices.clientproxy.trackedfault.timestamp(v=AX.60)
ms:contentKeyID: 49852670
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.TrackedFault.Timestamp
dev_langs:
- CSharp
- C++
- VB
---

# Timestamp Property

**Namespace:**  [Microsoft.Dynamics.Retail.TransactionServices.ClientProxy](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Timestamp As DateTime
    Get
    Set
'Usage
Dim instance As TrackedFault
Dim value As DateTime

value = instance.Timestamp

instance.Timestamp = value
```

``` csharp
[DataMemberAttribute]
public DateTime Timestamp { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property DateTime Timestamp {
    DateTime get ();
    void set (DateTime value);
}
```

#### Property Value

Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  
Returns [DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\)).  

## See Also

#### Reference

[TrackedFault Class](trackedfault-class-microsoft-dynamics-retail-transactionservices-clientproxy.md)

[Microsoft.Dynamics.Retail.TransactionServices.ClientProxy Namespace](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)

