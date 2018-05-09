---
title: ServiceResponse.Data Property  (Microsoft.Dynamics.Retail.TransactionServices.ClientProxy)
TOCTitle: Data Property
ms:assetid: P:Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.ServiceResponse.Data
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.transactionservices.clientproxy.serviceresponse.data(v=AX.60)
ms:contentKeyID: 49854416
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.ServiceResponse.Data
dev_langs:
- CSharp
- C++
- VB
---

# Data Property

**Namespace:**  [Microsoft.Dynamics.Retail.TransactionServices.ClientProxy](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Data As ReadOnlyCollection(Of Object)
    Get
    Set
'Usage
Dim instance As ServiceResponse
Dim value As ReadOnlyCollection(Of Object)

value = instance.Data

instance.Data = value
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<Object> Data { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<Object^>^ Data {
    ReadOnlyCollection<Object^>^ get ();
    void set (ReadOnlyCollection<Object^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[ServiceResponse Class](serviceresponse-class-microsoft-dynamics-retail-transactionservices-clientproxy.md)

[Microsoft.Dynamics.Retail.TransactionServices.ClientProxy Namespace](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)

