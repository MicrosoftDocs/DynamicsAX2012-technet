---
title: ServiceResponse.Success Property  (Microsoft.Dynamics.Retail.TransactionServices.ClientProxy)
TOCTitle: Success Property
ms:assetid: P:Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.ServiceResponse.Success
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.transactionservices.clientproxy.serviceresponse.success(v=AX.60)
ms:contentKeyID: 49831436
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.ServiceResponse.Success
dev_langs:
- CSharp
- C++
- VB
---

# Success Property

**Namespace:**  [Microsoft.Dynamics.Retail.TransactionServices.ClientProxy](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Success As Boolean
    Get
    Set
'Usage
Dim instance As ServiceResponse
Dim value As Boolean

value = instance.Success

instance.Success = value
```

``` csharp
[DataMemberAttribute]
public bool Success { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool Success {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ServiceResponse Class](serviceresponse-class-microsoft-dynamics-retail-transactionservices-clientproxy.md)

[Microsoft.Dynamics.Retail.TransactionServices.ClientProxy Namespace](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)

