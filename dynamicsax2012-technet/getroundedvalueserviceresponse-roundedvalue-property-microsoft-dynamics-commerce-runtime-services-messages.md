---
title: GetRoundedValueServiceResponse.RoundedValue Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: RoundedValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetRoundedValueServiceResponse.RoundedValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getroundedvalueserviceresponse.roundedvalue(v=AX.60)
ms:contentKeyID: 62210033
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetRoundedValueServiceResponse.RoundedValue
dev_langs:
- CSharp
- C++
- VB
---

# RoundedValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the rounded value which was calculated.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property RoundedValue As Decimal
    Get
    Private Set
'Usage
Dim instance As GetRoundedValueServiceResponse
Dim value As Decimal

value = instance.RoundedValue
```

``` csharp
[DataMemberAttribute]
public decimal RoundedValue { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal RoundedValue {
    Decimal get ();
    private: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[GetRoundedValueServiceResponse Class](getroundedvalueserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

