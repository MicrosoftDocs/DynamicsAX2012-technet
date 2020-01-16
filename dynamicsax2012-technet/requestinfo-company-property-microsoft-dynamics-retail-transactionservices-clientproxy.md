---
title: RequestInfo.Company Property  (Microsoft.Dynamics.Retail.TransactionServices.ClientProxy)
TOCTitle: Company Property
ms:assetid: P:Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.RequestInfo.Company
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.transactionservices.clientproxy.requestinfo.company(v=AX.60)
ms:contentKeyID: 49833886
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.RequestInfo.Company
dev_langs:
- CSharp
- C++
- VB
---

# Company Property

**Namespace:**  [Microsoft.Dynamics.Retail.TransactionServices.ClientProxy](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Company As String
    Get
    Set
'Usage
Dim instance As RequestInfo
Dim value As String

value = instance.Company

instance.Company = value
```

``` csharp
[DataMemberAttribute]
public string Company { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Company {
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

