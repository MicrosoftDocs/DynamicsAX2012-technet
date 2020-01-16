---
title: GetDiscountCodesServiceRequest.DiscountCode Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: DiscountCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetDiscountCodesServiceRequest.DiscountCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getdiscountcodesservicerequest.discountcode(v=AX.60)
ms:contentKeyID: 62206536
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetDiscountCodesServiceRequest.DiscountCode
dev_langs:
- CSharp
- C++
- VB
---

# DiscountCode Property

Gets the discount code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DiscountCode As String
    Get
    Private Set
'Usage
Dim instance As GetDiscountCodesServiceRequest
Dim value As String

value = instance.DiscountCode
```

``` csharp
[DataMemberAttribute]
public string DiscountCode { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ DiscountCode {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetDiscountCodesServiceRequest Class](getdiscountcodesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

