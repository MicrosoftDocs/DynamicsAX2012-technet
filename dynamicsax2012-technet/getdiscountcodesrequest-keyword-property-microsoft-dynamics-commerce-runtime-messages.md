---
title: GetDiscountCodesRequest.Keyword Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Keyword Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetDiscountCodesRequest.Keyword
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getdiscountcodesrequest.keyword(v=AX.60)
ms:contentKeyID: 62204222
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetDiscountCodesRequest.Keyword
dev_langs:
- CSharp
- C++
- VB
---

# Keyword Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the search keyword.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Keyword As String
    Get
    Set
'Usage
Dim instance As GetDiscountCodesRequest
Dim value As String

value = instance.Keyword

instance.Keyword = value
```

``` csharp
[DataMemberAttribute]
public string Keyword { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Keyword {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetDiscountCodesRequest Class](getdiscountcodesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

