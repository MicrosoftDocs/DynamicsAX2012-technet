---
title: GetRoundQuantityServiceRequest.Value Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Value Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetRoundQuantityServiceRequest.Value
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getroundquantityservicerequest.value(v=AX.60)
ms:contentKeyID: 62214168
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetRoundQuantityServiceRequest.Value
dev_langs:
- CSharp
- C++
- VB
---

# Value Property

Gets the value for rounding.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Value As Decimal
    Get
    Private Set
'Usage
Dim instance As GetRoundQuantityServiceRequest
Dim value As Decimal

value = instance.Value
```

``` csharp
[DataMemberAttribute]
public decimal Value { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal Value {
    Decimal get ();
    private: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[GetRoundQuantityServiceRequest Class](getroundquantityservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

