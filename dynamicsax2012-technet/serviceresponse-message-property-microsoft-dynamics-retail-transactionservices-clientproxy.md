---
title: ServiceResponse.Message Property  (Microsoft.Dynamics.Retail.TransactionServices.ClientProxy)
TOCTitle: Message Property
ms:assetid: P:Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.ServiceResponse.Message
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.transactionservices.clientproxy.serviceresponse.message(v=AX.60)
ms:contentKeyID: 49845331
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.ServiceResponse.Message
dev_langs:
- CSharp
- C++
- VB
---

# Message Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.TransactionServices.ClientProxy](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Message As String
    Get
    Set
'Usage
Dim instance As ServiceResponse
Dim value As String

value = instance.Message

instance.Message = value
```

``` csharp
[DataMemberAttribute]
public string Message { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Message {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ServiceResponse Class](serviceresponse-class-microsoft-dynamics-retail-transactionservices-clientproxy.md)

[Microsoft.Dynamics.Retail.TransactionServices.ClientProxy Namespace](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)

