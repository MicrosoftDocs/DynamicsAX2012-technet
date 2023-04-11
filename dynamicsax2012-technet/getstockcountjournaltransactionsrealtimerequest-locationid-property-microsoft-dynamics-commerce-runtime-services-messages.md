---
title: GetStockCountJournalTransactionsRealtimeRequest.LocationId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: LocationId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStockCountJournalTransactionsRealtimeRequest.LocationId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getstockcountjournaltransactionsrealtimerequest.locationid(v=AX.60)
ms:contentKeyID: 65321050
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStockCountJournalTransactionsRealtimeRequest.LocationId
dev_langs:
- CSharp
- C++
- VB
---

# LocationId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LocationId As String
    Get
    Private Set
'Usage
Dim instance As GetStockCountJournalTransactionsRealtimeRequest
Dim value As String

value = instance.LocationId
```

``` csharp
[DataMemberAttribute]
public string LocationId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ LocationId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetStockCountJournalTransactionsRealtimeRequest Class](getstockcountjournaltransactionsrealtimerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

