---
title: GetRoundedStringServiceRequest.UseSalesRounding Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: UseSalesRounding Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetRoundedStringServiceRequest.UseSalesRounding
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getroundedstringservicerequest.usesalesrounding(v=AX.60)
ms:contentKeyID: 62207114
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetRoundedStringServiceRequest.UseSalesRounding
dev_langs:
- CSharp
- C++
- VB
---

# UseSalesRounding Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether to use sales rounding instead of amount rounding.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property UseSalesRounding As Boolean
    Get
    Private Set
'Usage
Dim instance As GetRoundedStringServiceRequest
Dim value As Boolean

value = instance.UseSalesRounding
```

``` csharp
[DataMemberAttribute]
public bool UseSalesRounding { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property bool UseSalesRounding {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[GetRoundedStringServiceRequest Class](getroundedstringservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

