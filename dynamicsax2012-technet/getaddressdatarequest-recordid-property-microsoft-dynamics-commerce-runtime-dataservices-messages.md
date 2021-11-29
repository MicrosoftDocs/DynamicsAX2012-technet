---
title: GetAddressDataRequest.RecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: RecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAddressDataRequest.RecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getaddressdatarequest.recordid(v=AX.60)
ms:contentKeyID: 65318990
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAddressDataRequest.RecordId
dev_langs:
- CSharp
- C++
- VB
---

# RecordId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the address record identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property RecordId As Long
    Get
    Private Set
'Usage
Dim instance As GetAddressDataRequest
Dim value As Long

value = instance.RecordId
```

``` csharp
[DataMemberAttribute]
public long RecordId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property long long RecordId {
    long long get ();
    private: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The address record identifier.  

## See Also

#### Reference

[GetAddressDataRequest Class](getaddressdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

