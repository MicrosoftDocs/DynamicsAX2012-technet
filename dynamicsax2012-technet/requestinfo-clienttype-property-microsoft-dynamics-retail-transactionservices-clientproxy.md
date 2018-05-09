---
title: RequestInfo.ClientType Property  (Microsoft.Dynamics.Retail.TransactionServices.ClientProxy)
TOCTitle: ClientType Property
ms:assetid: P:Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.RequestInfo.ClientType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.transactionservices.clientproxy.requestinfo.clienttype(v=AX.60)
ms:contentKeyID: 49831396
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.RequestInfo.ClientType
dev_langs:
- CSharp
- C++
- VB
---

# ClientType Property

**Namespace:**  [Microsoft.Dynamics.Retail.TransactionServices.ClientProxy](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ClientType As String
    Get
    Set
'Usage
Dim instance As RequestInfo
Dim value As String

value = instance.ClientType

instance.ClientType = value
```

``` csharp
[DataMemberAttribute]
public string ClientType { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ClientType {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[RequestInfo Class](requestinfo-class-microsoft-dynamics-retail-transactionservices-clientproxy.md)

[Microsoft.Dynamics.Retail.TransactionServices.ClientProxy Namespace](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)

