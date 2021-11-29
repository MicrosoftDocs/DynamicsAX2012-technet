---
title: GetManagerActivityHistoryServiceRequest.BreakActivities Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: BreakActivities Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetManagerActivityHistoryServiceRequest.BreakActivities
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getmanageractivityhistoryservicerequest.breakactivities(v=AX.60)
ms:contentKeyID: 65320182
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetManagerActivityHistoryServiceRequest.BreakActivities
dev_langs:
- CSharp
- C++
- VB
---

# BreakActivities Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property BreakActivities As String()
    Get
    Private Set
'Usage
Dim instance As GetManagerActivityHistoryServiceRequest
Dim value As String()

value = instance.BreakActivities
```

``` csharp
[DataMemberAttribute]
public string[] BreakActivities { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property array<String^>^ BreakActivities {
    array<String^>^ get ();
    private: void set (array<String^>^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\[\]  

## See Also

#### Reference

[GetManagerActivityHistoryServiceRequest Class](getmanageractivityhistoryservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

