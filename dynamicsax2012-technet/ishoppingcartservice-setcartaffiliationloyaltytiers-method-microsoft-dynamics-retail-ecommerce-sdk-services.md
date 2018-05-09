---
title: IShoppingCartService.SetCartAffiliationLoyaltyTiers Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: SetCartAffiliationLoyaltyTiers Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.IShoppingCartService.SetCartAffiliationLoyaltyTiers(System.Collections.Generic.IEnumerable{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.services.ishoppingcartservice.setcartaffiliationloyaltytiers(v=AX.60)
ms:contentKeyID: 65317164
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.IShoppingCartService.SetCartAffiliationLoyaltyTiers
dev_langs:
- CSharp
- C++
- VB
---

# SetCartAffiliationLoyaltyTiers Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function SetCartAffiliationLoyaltyTiers ( _
    tiers As IEnumerable(Of Long) _
) As NullResponse
'Usage
Dim instance As IShoppingCartService
Dim tiers As IEnumerable(Of Long)
Dim returnValue As NullResponse

returnValue = instance.SetCartAffiliationLoyaltyTiers(tiers)
```

``` csharp
[OperationContractAttribute]
NullResponse SetCartAffiliationLoyaltyTiers(
    IEnumerable<long> tiers
)
```

``` c++
[OperationContractAttribute]
NullResponse^ SetCartAffiliationLoyaltyTiers(
    IEnumerable<long long>^ tiers
)
```

#### Parameters

  - tiers  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.NullResponse](nullresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[IShoppingCartService Interface](ishoppingcartservice-interface-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

