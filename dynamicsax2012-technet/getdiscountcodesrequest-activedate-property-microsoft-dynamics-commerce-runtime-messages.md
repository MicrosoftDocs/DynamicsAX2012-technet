---
title: GetDiscountCodesRequest.ActiveDate Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ActiveDate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetDiscountCodesRequest.ActiveDate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getdiscountcodesrequest.activedate(v=AX.60)
ms:contentKeyID: 62210356
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetDiscountCodesRequest.ActiveDate
dev_langs:
- CSharp
- C++
- VB
---

# ActiveDate Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the active date.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ActiveDate As DateTime
    Get
    Set
'Usage
Dim instance As GetDiscountCodesRequest
Dim value As DateTime

value = instance.ActiveDate

instance.ActiveDate = value
```

``` csharp
[DataMemberAttribute]
public DateTime ActiveDate { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property DateTime ActiveDate {
    DateTime get ();
    void set (DateTime value);
}
```

#### Property Value

Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  
Returns [DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\)).  

## See Also

#### Reference

[GetDiscountCodesRequest Class](getdiscountcodesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

