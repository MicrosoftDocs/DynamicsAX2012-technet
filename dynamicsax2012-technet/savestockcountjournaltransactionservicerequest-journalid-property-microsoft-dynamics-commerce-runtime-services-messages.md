---
title: SaveStockCountJournalTransactionServiceRequest.JournalId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: JournalId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveStockCountJournalTransactionServiceRequest.JournalId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.savestockcountjournaltransactionservicerequest.journalid(v=AX.60)
ms:contentKeyID: 62214310
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveStockCountJournalTransactionServiceRequest.JournalId
dev_langs:
- CSharp
- C++
- VB
---

# JournalId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the journal identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<RequiredAttribute> _
Public Property JournalId As String
    Get
    Private Set
'Usage
Dim instance As SaveStockCountJournalTransactionServiceRequest
Dim value As String

value = instance.JournalId
```

``` csharp
[DataMemberAttribute]
[RequiredAttribute]
public string JournalId { get; private set; }
```

``` c++
[DataMemberAttribute]
[RequiredAttribute]
public:
property String^ JournalId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[SaveStockCountJournalTransactionServiceRequest Class](savestockcountjournaltransactionservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

