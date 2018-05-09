---
title: GetCustomersServiceRequest.RecordId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: RecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCustomersServiceRequest.RecordId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getcustomersservicerequest.recordid(v=AX.60)
ms:contentKeyID: 49849827
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCustomersServiceRequest.RecordId
dev_langs:
- CSharp
- C++
- VB
---

# RecordId Property

Gets the record identfier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property RecordId As Long
    Get
    Private Set
'Usage
Dim instance As GetCustomersServiceRequest
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

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[GetCustomersServiceRequest Class](getcustomersservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

