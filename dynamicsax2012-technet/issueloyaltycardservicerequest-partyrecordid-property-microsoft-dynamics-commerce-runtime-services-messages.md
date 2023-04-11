---
title: IssueLoyaltyCardServiceRequest.PartyRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: PartyRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.IssueLoyaltyCardServiceRequest.PartyRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.issueloyaltycardservicerequest.partyrecordid(v=AX.60)
ms:contentKeyID: 65320798
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.IssueLoyaltyCardServiceRequest.PartyRecordId
dev_langs:
- CSharp
- C++
- VB
---

# PartyRecordId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PartyRecordId As Long
    Get
    Private Set
'Usage
Dim instance As IssueLoyaltyCardServiceRequest
Dim value As Long

value = instance.PartyRecordId
```

``` csharp
[DataMemberAttribute]
public long PartyRecordId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property long long PartyRecordId {
    long long get ();
    private: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

## See Also

#### Reference

[IssueLoyaltyCardServiceRequest Class](issueloyaltycardservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

