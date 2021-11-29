---
title: TenderTypesResponse.HasGiftCardPayment Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: HasGiftCardPayment Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.TenderTypesResponse.HasGiftCardPayment
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.tendertypesresponse.hasgiftcardpayment(v=AX.60)
ms:contentKeyID: 65318292
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.TenderTypesResponse.HasGiftCardPayment
dev_langs:
- CSharp
- C++
- VB
---

# HasGiftCardPayment Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property HasGiftCardPayment As Boolean
    Get
    Set
'Usage
Dim instance As TenderTypesResponse
Dim value As Boolean

value = instance.HasGiftCardPayment

instance.HasGiftCardPayment = value
```

``` csharp
[DataMemberAttribute]
public bool HasGiftCardPayment { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool HasGiftCardPayment {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[TenderTypesResponse Class](tendertypesresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

