---
title: TenderTypesResponse.HasLoyaltyCardPayment Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: HasLoyaltyCardPayment Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.TenderTypesResponse.HasLoyaltyCardPayment
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.tendertypesresponse.hasloyaltycardpayment(v=AX.60)
ms:contentKeyID: 65316096
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.TenderTypesResponse.HasLoyaltyCardPayment
dev_langs:
- CSharp
- C++
- VB
---

# HasLoyaltyCardPayment Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property HasLoyaltyCardPayment As Boolean
    Get
    Set
'Usage
Dim instance As TenderTypesResponse
Dim value As Boolean

value = instance.HasLoyaltyCardPayment

instance.HasLoyaltyCardPayment = value
```

``` csharp
[DataMemberAttribute]
public bool HasLoyaltyCardPayment { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool HasLoyaltyCardPayment {
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

