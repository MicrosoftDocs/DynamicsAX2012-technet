---
title: GetAddressDataRequest.CustomerRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: CustomerRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAddressDataRequest.CustomerRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getaddressdatarequest.customerrecordid(v=AX.60)
ms:contentKeyID: 65322324
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAddressDataRequest.CustomerRecordId
dev_langs:
- CSharp
- C++
- VB
---

# CustomerRecordId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the customer record identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CustomerRecordId As Nullable(Of Long)
    Get
    Private Set
'Usage
Dim instance As GetAddressDataRequest
Dim value As Nullable(Of Long)

value = instance.CustomerRecordId
```

``` csharp
[DataMemberAttribute]
public Nullable<long> CustomerRecordId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Nullable<long long> CustomerRecordId {
    Nullable<long long> get ();
    private: void set (Nullable<long long> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  
The customer record identifier.  

## See Also

#### Reference

[GetAddressDataRequest Class](getaddressdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

