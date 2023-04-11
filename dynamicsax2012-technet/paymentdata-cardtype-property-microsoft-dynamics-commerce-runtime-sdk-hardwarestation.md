---
title: PaymentData.CardType Property  (Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation)
TOCTitle: CardType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.PaymentData.CardType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.sdk.hardwarestation.paymentdata.cardtype(v=AX.60)
ms:contentKeyID: 65318219
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.PaymentData.CardType
dev_langs:
- CSharp
- C++
- VB
---

# CardType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a card type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation](microsoft-dynamics-commerce-runtime-sdk-hardwarestation-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation (in Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CardType As CardType
    Get
    Private Set
'Usage
Dim instance As PaymentData
Dim value As CardType

value = instance.CardType
```

``` csharp
[DataMemberAttribute]
public CardType CardType { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property CardType CardType {
    CardType get ();
    private: void set (CardType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CardType](cardtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [CardType](cardtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[PaymentData Class](paymentdata-class-microsoft-dynamics-commerce-runtime-sdk-hardwarestation.md)

[Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation Namespace](microsoft-dynamics-commerce-runtime-sdk-hardwarestation-namespace.md)

