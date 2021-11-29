---
title: GetDiscountCodesRequest.DiscountCode Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: DiscountCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetDiscountCodesRequest.DiscountCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getdiscountcodesrequest.discountcode(v=AX.60)
ms:contentKeyID: 62204187
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetDiscountCodesRequest.DiscountCode
dev_langs:
- CSharp
- C++
- VB
---

# DiscountCode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the discount code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DiscountCode As String
    Get
    Set
'Usage
Dim instance As GetDiscountCodesRequest
Dim value As String

value = instance.DiscountCode

instance.DiscountCode = value
```

``` csharp
[DataMemberAttribute]
public string DiscountCode { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ DiscountCode {
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

