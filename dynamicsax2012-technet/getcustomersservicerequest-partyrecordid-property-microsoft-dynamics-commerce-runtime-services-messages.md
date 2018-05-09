---
title: GetCustomersServiceRequest.PartyRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: PartyRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCustomersServiceRequest.PartyRecordId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getcustomersservicerequest.partyrecordid(v=AX.60)
ms:contentKeyID: 62213106
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCustomersServiceRequest.PartyRecordId
dev_langs:
- CSharp
- C++
- VB
---

# PartyRecordId Property

Gets the party record identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property PartyRecordId As Long
    Get
    Private Set
'Usage
Dim instance As GetCustomersServiceRequest
Dim value As Long

value = instance.PartyRecordId
```

``` csharp
public long PartyRecordId { get; private set; }
```

``` c++
public:
property long long PartyRecordId {
    long long get ();
    private: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  
The party record identifier.  

## See Also

#### Reference

[GetCustomersServiceRequest Class](getcustomersservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

