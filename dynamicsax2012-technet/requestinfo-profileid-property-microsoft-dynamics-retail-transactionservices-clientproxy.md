---
title: RequestInfo.ProfileId Property  (Microsoft.Dynamics.Retail.TransactionServices.ClientProxy)
TOCTitle: ProfileId Property
ms:assetid: P:Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.RequestInfo.ProfileId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.transactionservices.clientproxy.requestinfo.profileid(v=AX.60)
ms:contentKeyID: 49822681
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.RequestInfo.ProfileId
dev_langs:
- CSharp
- C++
- VB
---

# ProfileId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.TransactionServices.ClientProxy](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ProfileId As String
    Get
    Set
'Usage
Dim instance As RequestInfo
Dim value As String

value = instance.ProfileId

instance.ProfileId = value
```

``` csharp
[DataMemberAttribute]
public string ProfileId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ProfileId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[RequestInfo Class](requestinfo-class-microsoft-dynamics-retail-transactionservices-clientproxy.md)

[Microsoft.Dynamics.Retail.TransactionServices.ClientProxy Namespace](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)

