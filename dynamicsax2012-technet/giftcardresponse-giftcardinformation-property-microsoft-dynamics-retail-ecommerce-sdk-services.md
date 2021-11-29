---
title: GiftCardResponse.GiftCardInformation Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: GiftCardInformation Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.GiftCardResponse.GiftCardInformation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.giftcardresponse.giftcardinformation(v=AX.60)
ms:contentKeyID: 65316666
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.GiftCardResponse.GiftCardInformation
dev_langs:
- CSharp
- C++
- VB
---

# GiftCardInformation Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property GiftCardInformation As GiftCardInformation
    Get
    Set
'Usage
Dim instance As GiftCardResponse
Dim value As GiftCardInformation

value = instance.GiftCardInformation

instance.GiftCardInformation = value
```

``` csharp
[DataMemberAttribute]
public GiftCardInformation GiftCardInformation { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property GiftCardInformation^ GiftCardInformation {
    GiftCardInformation^ get ();
    void set (GiftCardInformation^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.GiftCardInformation](giftcardinformation-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

## See Also

#### Reference

[GiftCardResponse Class](giftcardresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

