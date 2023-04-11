---
title: CheckoutController.UpdateCartLineShippingAddresses Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: UpdateCartLineShippingAddresses Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CheckoutController.UpdateCartLineShippingAddresses(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.SelectedLineDeliveryOption},System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.checkoutcontroller.updatecartlineshippingaddresses(v=AX.60)
ms:contentKeyID: 65317189
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CheckoutController.UpdateCartLineShippingAddresses
dev_langs:
- CSharp
- C++
- VB
---

# UpdateCartLineShippingAddresses Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Protected Overridable Sub UpdateCartLineShippingAddresses ( _
    selectedLineDeliveryOptions As IEnumerable(Of SelectedLineDeliveryOption), _
    lines As IEnumerable(Of CartLine) _
)
'Usage
Dim selectedLineDeliveryOptions As IEnumerable(Of SelectedLineDeliveryOption)
Dim lines As IEnumerable(Of CartLine)

Me.UpdateCartLineShippingAddresses(selectedLineDeliveryOptions, _
    lines)
```

``` csharp
protected virtual void UpdateCartLineShippingAddresses(
    IEnumerable<SelectedLineDeliveryOption> selectedLineDeliveryOptions,
    IEnumerable<CartLine> lines
)
```

``` c++
protected:
virtual void UpdateCartLineShippingAddresses(
    IEnumerable<SelectedLineDeliveryOption^>^ selectedLineDeliveryOptions, 
    IEnumerable<CartLine^>^ lines
)
```

#### Parameters

  - selectedLineDeliveryOptions  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SelectedLineDeliveryOption](selectedlinedeliveryoption-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

<!-- end list -->

  - lines  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<CartLine\>  

## See Also

#### Reference

[CheckoutController Class](checkoutcontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

