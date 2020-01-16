---
title: SyncStockCountTransactionsFromAxServiceRequest.JournalId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: JournalId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SyncStockCountTransactionsFromAxServiceRequest.JournalId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.syncstockcounttransactionsfromaxservicerequest.journalid(v=AX.60)
ms:contentKeyID: 62213870
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SyncStockCountTransactionsFromAxServiceRequest.JournalId
dev_langs:
- CSharp
- C++
- VB
---

# JournalId Property

Gets or sets the journal identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<RequiredAttribute> _
<DataMemberAttribute> _
Public Property JournalId As String
    Get
    Set
'Usage
Dim instance As SyncStockCountTransactionsFromAxServiceRequest
Dim value As String

value = instance.JournalId

instance.JournalId = value
```

``` csharp
[RequiredAttribute]
[DataMemberAttribute]
public string JournalId { get; set; }
```

``` c++
[RequiredAttribute]
[DataMemberAttribute]
public:
property String^ JournalId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[SyncStockCountTransactionsFromAxServiceRequest Class](syncstockcounttransactionsfromaxservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

