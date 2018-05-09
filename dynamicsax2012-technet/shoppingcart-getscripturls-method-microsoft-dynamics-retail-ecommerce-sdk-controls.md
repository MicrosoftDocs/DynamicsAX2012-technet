---
title: ShoppingCart.GetScriptUrls Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls)
TOCTitle: GetScriptUrls Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.ShoppingCart.GetScriptUrls
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.controls.shoppingcart.getscripturls(v=AX.60)
ms:contentKeyID: 65318028
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.ShoppingCart.GetScriptUrls
dev_langs:
- CSharp
- C++
- VB
---

# GetScriptUrls Method

This member overrides [RetailWebControl.GetScriptUrls()](retailwebcontrol-getscripturls-method-microsoft-dynamics-retail-ecommerce-sdk-controls.md).

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls](microsoft-dynamics-retail-ecommerce-sdk-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function GetScriptUrls As Collection(Of String)
'Usage
Dim returnValue As Collection(Of String)

returnValue = Me.GetScriptUrls()
```

``` csharp
protected override Collection<string> GetScriptUrls()
```

``` c++
protected:
virtual Collection<String^>^ GetScriptUrls() override
```

#### Return Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  

## See Also

#### Reference

[ShoppingCart Class](shoppingcart-class-microsoft-dynamics-retail-ecommerce-sdk-controls.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls Namespace](microsoft-dynamics-retail-ecommerce-sdk-controls-namespace.md)

