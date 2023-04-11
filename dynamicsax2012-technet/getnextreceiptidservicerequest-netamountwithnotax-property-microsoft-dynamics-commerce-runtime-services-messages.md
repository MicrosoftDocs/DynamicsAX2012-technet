---
title: GetNextReceiptIdServiceRequest.NetAmountWithNoTax Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: NetAmountWithNoTax Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetNextReceiptIdServiceRequest.NetAmountWithNoTax
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getnextreceiptidservicerequest.netamountwithnotax(v=AX.60)
ms:contentKeyID: 65319892
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetNextReceiptIdServiceRequest.NetAmountWithNoTax
dev_langs:
- CSharp
- C++
- VB
---

# NetAmountWithNoTax Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<RequiredAttribute> _
<DataMemberAttribute> _
Public Property NetAmountWithNoTax As Decimal
    Get
    Set
'Usage
Dim instance As GetNextReceiptIdServiceRequest
Dim value As Decimal

value = instance.NetAmountWithNoTax

instance.NetAmountWithNoTax = value
```

``` csharp
[RequiredAttribute]
[DataMemberAttribute]
public decimal NetAmountWithNoTax { get; set; }
```

``` c++
[RequiredAttribute]
[DataMemberAttribute]
public:
property Decimal NetAmountWithNoTax {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[GetNextReceiptIdServiceRequest Class](getnextreceiptidservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

