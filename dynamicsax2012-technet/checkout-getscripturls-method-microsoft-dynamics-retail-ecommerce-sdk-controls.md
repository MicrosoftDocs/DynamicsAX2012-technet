---
title: Checkout.GetScriptUrls Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls)
TOCTitle: GetScriptUrls Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.Checkout.GetScriptUrls
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.controls.checkout.getscripturls(v=AX.60)
ms:contentKeyID: 65315647
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.Checkout.GetScriptUrls
dev_langs:
- CSharp
- C++
- VB
---

# GetScriptUrls Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

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

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

## See Also

#### Reference

[Checkout Class](checkout-class-microsoft-dynamics-retail-ecommerce-sdk-controls.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls Namespace](microsoft-dynamics-retail-ecommerce-sdk-controls-namespace.md)

