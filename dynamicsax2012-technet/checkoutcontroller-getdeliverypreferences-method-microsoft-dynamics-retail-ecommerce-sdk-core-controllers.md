---
title: CheckoutController.GetDeliveryPreferences Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: GetDeliveryPreferences Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CheckoutController.GetDeliveryPreferences(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.checkoutcontroller.getdeliverypreferences(v=AX.60)
ms:contentKeyID: 65318757
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CheckoutController.GetDeliveryPreferences
dev_langs:
- CSharp
- C++
- VB
---

# GetDeliveryPreferences Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GetDeliveryPreferences ( _
    shoppingCartId As String _
) As CartDeliveryPreferences
'Usage
Dim instance As CheckoutController
Dim shoppingCartId As String
Dim returnValue As CartDeliveryPreferences

returnValue = instance.GetDeliveryPreferences(shoppingCartId)
```

``` csharp
public virtual CartDeliveryPreferences GetDeliveryPreferences(
    string shoppingCartId
)
```

``` c++
public:
virtual CartDeliveryPreferences^ GetDeliveryPreferences(
    String^ shoppingCartId
)
```

#### Parameters

  - shoppingCartId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.CartDeliveryPreferences](cartdeliverypreferences-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

## See Also

#### Reference

[CheckoutController Class](checkoutcontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

