---
title: TokenizedPaymentCard.PaymentAddress Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models)
TOCTitle: PaymentAddress Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.TokenizedPaymentCard.PaymentAddress
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.models.tokenizedpaymentcard.paymentaddress(v=AX.60)
ms:contentKeyID: 65318053
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.TokenizedPaymentCard.PaymentAddress
dev_langs:
- CSharp
- C++
- VB
---

# PaymentAddress Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PaymentAddress As Address
    Get
    Set
'Usage
Dim instance As TokenizedPaymentCard
Dim value As Address

value = instance.PaymentAddress

instance.PaymentAddress = value
```

``` csharp
[DataMemberAttribute]
public Address PaymentAddress { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Address^ PaymentAddress {
    Address^ get ();
    void set (Address^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Address](address-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

## See Also

#### Reference

[TokenizedPaymentCard Class](tokenizedpaymentcard-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)

