---
title: GetCustomersRequest.PartyRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: PartyRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetCustomersRequest.PartyRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getcustomersrequest.partyrecordid(v=AX.60)
ms:contentKeyID: 62208252
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetCustomersRequest.PartyRecordId
dev_langs:
- CSharp
- C++
- VB
---

# PartyRecordId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the party record identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PartyRecordId As Long
    Get
    Set
'Usage
Dim instance As GetCustomersRequest
Dim value As Long

value = instance.PartyRecordId

instance.PartyRecordId = value
```

``` csharp
[DataMemberAttribute]
public long PartyRecordId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property long long PartyRecordId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The party record identifier.  

## See Also

#### Reference

[GetCustomersRequest Class](getcustomersrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

