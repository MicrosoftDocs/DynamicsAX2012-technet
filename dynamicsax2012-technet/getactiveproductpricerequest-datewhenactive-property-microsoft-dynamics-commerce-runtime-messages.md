---
title: GetActiveProductPriceRequest.DateWhenActive Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: DateWhenActive Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetActiveProductPriceRequest.DateWhenActive
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getactiveproductpricerequest.datewhenactive(v=AX.60)
ms:contentKeyID: 62208395
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetActiveProductPriceRequest.DateWhenActive
dev_langs:
- CSharp
- C++
- VB
---

# DateWhenActive Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the date used when finding active prices.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<RequiredAttribute> _
<DataMemberAttribute> _
Public Property DateWhenActive As DateTime
    Get
    Set
'Usage
Dim instance As GetActiveProductPriceRequest
Dim value As DateTime

value = instance.DateWhenActive

instance.DateWhenActive = value
```

``` csharp
[RequiredAttribute]
[DataMemberAttribute]
public DateTime DateWhenActive { get; set; }
```

``` c++
[RequiredAttribute]
[DataMemberAttribute]
public:
property DateTime DateWhenActive {
    DateTime get ();
    void set (DateTime value);
}
```

#### Property Value

Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  
Returns [DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\)).  

## See Also

#### Reference

[GetActiveProductPriceRequest Class](getactiveproductpricerequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

