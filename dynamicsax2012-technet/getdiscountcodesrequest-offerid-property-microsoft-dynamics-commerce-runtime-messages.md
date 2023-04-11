---
title: GetDiscountCodesRequest.OfferId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: OfferId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetDiscountCodesRequest.OfferId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getdiscountcodesrequest.offerid(v=AX.60)
ms:contentKeyID: 62205702
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetDiscountCodesRequest.OfferId
dev_langs:
- CSharp
- C++
- VB
---

# OfferId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the offer id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property OfferId As String
    Get
    Set
'Usage
Dim instance As GetDiscountCodesRequest
Dim value As String

value = instance.OfferId

instance.OfferId = value
```

``` csharp
[DataMemberAttribute]
public string OfferId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ OfferId {
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

