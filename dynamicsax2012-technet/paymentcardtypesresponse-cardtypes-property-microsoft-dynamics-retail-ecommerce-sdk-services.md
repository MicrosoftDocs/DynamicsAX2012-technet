---
title: PaymentCardTypesResponse.CardTypes Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: CardTypes Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.PaymentCardTypesResponse.CardTypes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.paymentcardtypesresponse.cardtypes(v=AX.60)
ms:contentKeyID: 65316477
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.PaymentCardTypesResponse.CardTypes
dev_langs:
- CSharp
- C++
- VB
---

# CardTypes Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CardTypes As Collection(Of PaymentCardType)
    Get
    Private Set
'Usage
Dim instance As PaymentCardTypesResponse
Dim value As Collection(Of PaymentCardType)

value = instance.CardTypes
```

``` csharp
[DataMemberAttribute]
public Collection<PaymentCardType> CardTypes { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<PaymentCardType^>^ CardTypes {
    Collection<PaymentCardType^>^ get ();
    private: void set (Collection<PaymentCardType^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[PaymentCardType](paymentcardtype-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[PaymentCardTypesResponse Class](paymentcardtypesresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

