---
title: TenderDataLine.PaymentCard Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models)
TOCTitle: PaymentCard Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.TenderDataLine.PaymentCard
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.models.tenderdataline.paymentcard(v=AX.60)
ms:contentKeyID: 65315598
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.TenderDataLine.PaymentCard
dev_langs:
- CSharp
- C++
- VB
---

# PaymentCard Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PaymentCard As Payment
    Get
    Set
'Usage
Dim instance As TenderDataLine
Dim value As Payment

value = instance.PaymentCard

instance.PaymentCard = value
```

``` csharp
[DataMemberAttribute]
public Payment PaymentCard { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Payment^ PaymentCard {
    Payment^ get ();
    void set (Payment^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Payment](payment-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

## See Also

#### Reference

[TenderDataLine Class](tenderdataline-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)

