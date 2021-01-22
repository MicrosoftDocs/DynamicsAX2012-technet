---
title: CheckoutServiceBase.SetLineDeliveryOptions Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: SetLineDeliveryOptions Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.CheckoutServiceBase.SetLineDeliveryOptions(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.SelectedLineDeliveryOption},Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.ShoppingCartDataLevel)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.checkoutservicebase.setlinedeliveryoptions(v=AX.60)
ms:contentKeyID: 65316513
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.CheckoutServiceBase.SetLineDeliveryOptions
dev_langs:
- CSharp
- C++
- VB
---

# SetLineDeliveryOptions Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function SetLineDeliveryOptions ( _
    selectedLineDeliveryOptions As IEnumerable(Of SelectedLineDeliveryOption), _
    dataLevel As ShoppingCartDataLevel _
) As ShoppingCartResponse
'Usage
Dim instance As CheckoutServiceBase
Dim selectedLineDeliveryOptions As IEnumerable(Of SelectedLineDeliveryOption)
Dim dataLevel As ShoppingCartDataLevel
Dim returnValue As ShoppingCartResponse

returnValue = instance.SetLineDeliveryOptions(selectedLineDeliveryOptions, _
    dataLevel)
```

``` csharp
public virtual ShoppingCartResponse SetLineDeliveryOptions(
    IEnumerable<SelectedLineDeliveryOption> selectedLineDeliveryOptions,
    ShoppingCartDataLevel dataLevel
)
```

``` c++
public:
virtual ShoppingCartResponse^ SetLineDeliveryOptions(
    IEnumerable<SelectedLineDeliveryOption^>^ selectedLineDeliveryOptions, 
    ShoppingCartDataLevel dataLevel
)
```

#### Parameters

  - selectedLineDeliveryOptions  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SelectedLineDeliveryOption](selectedlinedeliveryoption-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

<!-- end list -->

  - dataLevel  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.ShoppingCartDataLevel](shoppingcartdatalevel-enumeration-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ShoppingCartResponse](shoppingcartresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

#### Implements

[ICheckoutService.SetLineDeliveryOptions(IEnumerable\<SelectedLineDeliveryOption\>, ShoppingCartDataLevel)](icheckoutservice-setlinedeliveryoptions-method-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[CheckoutServiceBase Class](checkoutservicebase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

