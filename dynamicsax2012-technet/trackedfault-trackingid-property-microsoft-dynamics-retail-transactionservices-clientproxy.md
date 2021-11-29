---
title: TrackedFault.TrackingId Property  (Microsoft.Dynamics.Retail.TransactionServices.ClientProxy)
TOCTitle: TrackingId Property
ms:assetid: P:Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.TrackedFault.TrackingId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.transactionservices.clientproxy.trackedfault.trackingid(v=AX.60)
ms:contentKeyID: 49832733
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.TrackedFault.TrackingId
dev_langs:
- CSharp
- C++
- VB
---

# TrackingId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.TransactionServices.ClientProxy](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TrackingId As Guid
    Get
    Set
'Usage
Dim instance As TrackedFault
Dim value As Guid

value = instance.TrackingId

instance.TrackingId = value
```

``` csharp
[DataMemberAttribute]
public Guid TrackingId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Guid TrackingId {
    Guid get ();
    void set (Guid value);
}
```

#### Property Value

Type: [System.Guid](https://technet.microsoft.com/library/cey1zx63\(v=ax.60\))  
Returns [Guid](https://technet.microsoft.com/library/cey1zx63\(v=ax.60\)).  

## See Also

#### Reference

[TrackedFault Class](trackedfault-class-microsoft-dynamics-retail-transactionservices-clientproxy.md)

[Microsoft.Dynamics.Retail.TransactionServices.ClientProxy Namespace](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)

