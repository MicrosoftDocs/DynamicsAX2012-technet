---
title: ShoppingCart.GetStartupMarkup Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls)
TOCTitle: GetStartupMarkup Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.ShoppingCart.GetStartupMarkup(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.controls.shoppingcart.getstartupmarkup(v=AX.60)
ms:contentKeyID: 65316649
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.ShoppingCart.GetStartupMarkup
dev_langs:
- CSharp
- C++
- VB
---

# GetStartupMarkup Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

This member overrides [RetailWebControl.GetStartupMarkup(String)](retailwebcontrol-getstartupmarkup-method-microsoft-dynamics-retail-ecommerce-sdk-controls.md).

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls](microsoft-dynamics-retail-ecommerce-sdk-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function GetStartupMarkup ( _
    existingHeaderMarkup As String _
) As String
'Usage
Dim existingHeaderMarkup As String
Dim returnValue As String

returnValue = Me.GetStartupMarkup(existingHeaderMarkup)
```

``` csharp
protected override string GetStartupMarkup(
    string existingHeaderMarkup
)
```

``` c++
protected:
virtual String^ GetStartupMarkup(
    String^ existingHeaderMarkup
) override
```

#### Parameters

  - existingHeaderMarkup  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ShoppingCart Class](shoppingcart-class-microsoft-dynamics-retail-ecommerce-sdk-controls.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls Namespace](microsoft-dynamics-retail-ecommerce-sdk-controls-namespace.md)

