---
title: GetEmployeeActivityHistoryServiceRequest.FromUtcDateTime Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: FromUtcDateTime Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetEmployeeActivityHistoryServiceRequest.FromUtcDateTime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getemployeeactivityhistoryservicerequest.fromutcdatetime(v=AX.60)
ms:contentKeyID: 65321021
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetEmployeeActivityHistoryServiceRequest.FromUtcDateTime
dev_langs:
- CSharp
- C++
- VB
---

# FromUtcDateTime Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property FromUtcDateTime As Nullable(Of DateTime)
    Get
    Private Set
'Usage
Dim instance As GetEmployeeActivityHistoryServiceRequest
Dim value As Nullable(Of DateTime)

value = instance.FromUtcDateTime
```

``` csharp
[DataMemberAttribute]
public Nullable<DateTime> FromUtcDateTime { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Nullable<DateTime> FromUtcDateTime {
    Nullable<DateTime> get ();
    private: void set (Nullable<DateTime> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))\>  

## See Also

#### Reference

[GetEmployeeActivityHistoryServiceRequest Class](getemployeeactivityhistoryservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

