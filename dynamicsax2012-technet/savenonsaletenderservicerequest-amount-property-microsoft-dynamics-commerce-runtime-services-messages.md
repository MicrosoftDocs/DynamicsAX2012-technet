---
title: SaveNonSaleTenderServiceRequest.Amount Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Amount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveNonSaleTenderServiceRequest.Amount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.savenonsaletenderservicerequest.amount(v=AX.60)
ms:contentKeyID: 62214025
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveNonSaleTenderServiceRequest.Amount
dev_langs:
- CSharp
- C++
- VB
---

# Amount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the amount of the transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Amount As Decimal
    Get
    Set
'Usage
Dim instance As SaveNonSaleTenderServiceRequest
Dim value As Decimal

value = instance.Amount

instance.Amount = value
```

``` csharp
[DataMemberAttribute]
public decimal Amount { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal Amount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[SaveNonSaleTenderServiceRequest Class](savenonsaletenderservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

