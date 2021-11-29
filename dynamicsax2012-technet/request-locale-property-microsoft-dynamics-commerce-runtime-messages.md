---
title: Request.Locale Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Locale Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.Request.Locale
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.request.locale(v=AX.60)
ms:contentKeyID: 49837536
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.Request.Locale
dev_langs:
- CSharp
- C++
- VB
---

# Locale Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the locale for the request.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Locale As String
    Get
    Set
'Usage
Dim instance As Request
Dim value As String

value = instance.Locale

instance.Locale = value
```

``` csharp
[DataMemberAttribute]
public string Locale { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Locale {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[Request Class](request-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

