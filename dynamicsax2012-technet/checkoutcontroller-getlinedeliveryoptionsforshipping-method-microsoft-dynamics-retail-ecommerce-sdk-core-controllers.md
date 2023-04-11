---
title: CheckoutController.GetLineDeliveryOptionsForShipping Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: GetLineDeliveryOptionsForShipping Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CheckoutController.GetLineDeliveryOptionsForShipping(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.SelectedLineShippingInfo})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.checkoutcontroller.getlinedeliveryoptionsforshipping(v=AX.60)
ms:contentKeyID: 65316918
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CheckoutController.GetLineDeliveryOptionsForShipping
dev_langs:
- CSharp
- C++
- VB
---

# GetLineDeliveryOptionsForShipping Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GetLineDeliveryOptionsForShipping ( _
    shoppingCartId As String, _
    customerId As String, _
    selectedLineShippingInfo As IEnumerable(Of SelectedLineShippingInfo) _
) As Collection(Of LineDeliveryOption)
'Usage
Dim instance As CheckoutController
Dim shoppingCartId As String
Dim customerId As String
Dim selectedLineShippingInfo As IEnumerable(Of SelectedLineShippingInfo)
Dim returnValue As Collection(Of LineDeliveryOption)

returnValue = instance.GetLineDeliveryOptionsForShipping(shoppingCartId, _
    customerId, selectedLineShippingInfo)
```

``` csharp
public virtual Collection<LineDeliveryOption> GetLineDeliveryOptionsForShipping(
    string shoppingCartId,
    string customerId,
    IEnumerable<SelectedLineShippingInfo> selectedLineShippingInfo
)
```

``` c++
public:
virtual Collection<LineDeliveryOption^>^ GetLineDeliveryOptionsForShipping(
    String^ shoppingCartId, 
    String^ customerId, 
    IEnumerable<SelectedLineShippingInfo^>^ selectedLineShippingInfo
)
```

#### Parameters

  - shoppingCartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - customerId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - selectedLineShippingInfo  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SelectedLineShippingInfo](selectedlineshippinginfo-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

#### Return Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[LineDeliveryOption](linedeliveryoption-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[CheckoutController Class](checkoutcontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

