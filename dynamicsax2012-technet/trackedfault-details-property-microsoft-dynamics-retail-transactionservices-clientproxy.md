---
title: TrackedFault.Details Property  (Microsoft.Dynamics.Retail.TransactionServices.ClientProxy)
TOCTitle: Details Property
ms:assetid: P:Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.TrackedFault.Details
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.transactionservices.clientproxy.trackedfault.details(v=AX.60)
ms:contentKeyID: 49851954
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.TrackedFault.Details
dev_langs:
- CSharp
- C++
- VB
---

# Details Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.TransactionServices.ClientProxy](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Details As String
    Get
    Set
'Usage
Dim instance As TrackedFault
Dim value As String

value = instance.Details

instance.Details = value
```

``` csharp
[DataMemberAttribute]
public string Details { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Details {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TrackedFault Class](trackedfault-class-microsoft-dynamics-retail-transactionservices-clientproxy.md)

[Microsoft.Dynamics.Retail.TransactionServices.ClientProxy Namespace](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)

