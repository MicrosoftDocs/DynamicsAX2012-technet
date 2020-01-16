---
title: CreateStockCountJournalServiceRequest.Description Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Description Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CreateStockCountJournalServiceRequest.Description
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.createstockcountjournalservicerequest.description(v=AX.60)
ms:contentKeyID: 62205710
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CreateStockCountJournalServiceRequest.Description
dev_langs:
- CSharp
- C++
- VB
---

# Description Property

Gets or sets the description.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Description As String
    Get
    Set
'Usage
Dim instance As CreateStockCountJournalServiceRequest
Dim value As String

value = instance.Description

instance.Description = value
```

``` csharp
[DataMemberAttribute]
public string Description { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Description {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CreateStockCountJournalServiceRequest Class](createstockcountjournalservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

