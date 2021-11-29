---
title: GetAddressRequest.LanguageId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: LanguageId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetAddressRequest.LanguageId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getaddressrequest.languageid(v=AX.60)
ms:contentKeyID: 62213953
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetAddressRequest.LanguageId
dev_langs:
- CSharp
- C++
- VB
---

# LanguageId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the languauge identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LanguageId As String
    Get
    Set
'Usage
Dim instance As GetAddressRequest
Dim value As String

value = instance.LanguageId

instance.LanguageId = value
```

``` csharp
[DataMemberAttribute]
public string LanguageId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ LanguageId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetAddressRequest Class](getaddressrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

