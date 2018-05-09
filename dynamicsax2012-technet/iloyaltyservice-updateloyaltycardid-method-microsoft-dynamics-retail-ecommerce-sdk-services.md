---
title: ILoyaltyService.UpdateLoyaltyCardId Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: UpdateLoyaltyCardId Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ILoyaltyService.UpdateLoyaltyCardId(System.Boolean,System.String,Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.ShoppingCartDataLevel)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.services.iloyaltyservice.updateloyaltycardid(v=AX.60)
ms:contentKeyID: 65317340
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ILoyaltyService.UpdateLoyaltyCardId
dev_langs:
- CSharp
- C++
- VB
---

# UpdateLoyaltyCardId Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function UpdateLoyaltyCardId ( _
    isCheckoutSession As Boolean, _
    loyaltyCardId As String, _
    dataLevel As ShoppingCartDataLevel _
) As ShoppingCartResponse
'Usage
Dim instance As ILoyaltyService
Dim isCheckoutSession As Boolean
Dim loyaltyCardId As String
Dim dataLevel As ShoppingCartDataLevel
Dim returnValue As ShoppingCartResponse

returnValue = instance.UpdateLoyaltyCardId(isCheckoutSession, _
    loyaltyCardId, dataLevel)
```

``` csharp
[OperationContractAttribute]
ShoppingCartResponse UpdateLoyaltyCardId(
    bool isCheckoutSession,
    string loyaltyCardId,
    ShoppingCartDataLevel dataLevel
)
```

``` c++
[OperationContractAttribute]
ShoppingCartResponse^ UpdateLoyaltyCardId(
    bool isCheckoutSession, 
    String^ loyaltyCardId, 
    ShoppingCartDataLevel dataLevel
)
```

#### Parameters

  - isCheckoutSession  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - loyaltyCardId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - dataLevel  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.ShoppingCartDataLevel](shoppingcartdatalevel-enumeration-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ShoppingCartResponse](shoppingcartresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[ILoyaltyService Interface](iloyaltyservice-interface-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

