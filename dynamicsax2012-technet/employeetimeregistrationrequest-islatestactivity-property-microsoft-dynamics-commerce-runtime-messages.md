---
title: EmployeeTimeRegistrationRequest.IsLatestActivity Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: IsLatestActivity Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.EmployeeTimeRegistrationRequest.IsLatestActivity
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.employeetimeregistrationrequest.islatestactivity(v=AX.60)
ms:contentKeyID: 62208257
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.EmployeeTimeRegistrationRequest.IsLatestActivity
dev_langs:
- CSharp
- C++
- VB
---

# IsLatestActivity Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether to retrieve the latest activity details.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsLatestActivity As Boolean
    Get
    Set
'Usage
Dim instance As EmployeeTimeRegistrationRequest
Dim value As Boolean

value = instance.IsLatestActivity

instance.IsLatestActivity = value
```

``` csharp
[DataMemberAttribute]
public bool IsLatestActivity { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsLatestActivity {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[EmployeeTimeRegistrationRequest Class](employeetimeregistrationrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

