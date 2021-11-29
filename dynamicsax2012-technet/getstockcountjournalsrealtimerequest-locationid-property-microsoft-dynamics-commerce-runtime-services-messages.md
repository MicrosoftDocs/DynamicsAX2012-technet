---
title: GetStockCountJournalsRealtimeRequest.LocationId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: LocationId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStockCountJournalsRealtimeRequest.LocationId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getstockcountjournalsrealtimerequest.locationid(v=AX.60)
ms:contentKeyID: 65317261
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStockCountJournalsRealtimeRequest.LocationId
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
Dim instance As GetStockCountJournalsRealtimeRequest
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

[GetStockCountJournalsRealtimeRequest Class](getstockcountjournalsrealtimerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

