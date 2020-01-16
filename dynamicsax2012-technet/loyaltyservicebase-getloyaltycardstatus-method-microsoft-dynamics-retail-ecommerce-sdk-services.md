---
title: LoyaltyServiceBase.GetLoyaltyCardStatus Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: GetLoyaltyCardStatus Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.LoyaltyServiceBase.GetLoyaltyCardStatus(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.loyaltyservicebase.getloyaltycardstatus(v=AX.60)
ms:contentKeyID: 65317695
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.LoyaltyServiceBase.GetLoyaltyCardStatus
dev_langs:
- CSharp
- C++
- VB
---

# GetLoyaltyCardStatus Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GetLoyaltyCardStatus ( _
    loyaltyCardNumber As String _
) As LoyaltyCardResponse
'Usage
Dim instance As LoyaltyServiceBase
Dim loyaltyCardNumber As String
Dim returnValue As LoyaltyCardResponse

returnValue = instance.GetLoyaltyCardStatus(loyaltyCardNumber)
```

``` csharp
public virtual LoyaltyCardResponse GetLoyaltyCardStatus(
    string loyaltyCardNumber
)
```

``` c++
public:
virtual LoyaltyCardResponse^ GetLoyaltyCardStatus(
    String^ loyaltyCardNumber
)
```

#### Parameters

  - loyaltyCardNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.LoyaltyCardResponse](loyaltycardresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

#### Implements

[ILoyaltyService.GetLoyaltyCardStatus(String)](iloyaltyservice-getloyaltycardstatus-method-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[LoyaltyServiceBase Class](loyaltyservicebase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

