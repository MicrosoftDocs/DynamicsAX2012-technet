---
title: PriceCheckRequest.Quantity Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Quantity Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.PriceCheckRequest.Quantity
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.pricecheckrequest.quantity(v=AX.60)
ms:contentKeyID: 62205548
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.PriceCheckRequest.Quantity
dev_langs:
- CSharp
- C++
- VB
---

# Quantity Property

Gets the quantity.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Quantity As Decimal
    Get
    Private Set
'Usage
Dim instance As PriceCheckRequest
Dim value As Decimal

value = instance.Quantity
```

``` csharp
[DataMemberAttribute]
public decimal Quantity { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal Quantity {
    Decimal get ();
    private: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[PriceCheckRequest Class](pricecheckrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

