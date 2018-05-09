---
title: MiniCart.GetCssUrls Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls)
TOCTitle: GetCssUrls Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.MiniCart.GetCssUrls
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.controls.minicart.getcssurls(v=AX.60)
ms:contentKeyID: 65315708
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.MiniCart.GetCssUrls
dev_langs:
- CSharp
- C++
- VB
---

# GetCssUrls Method

This member overrides [RetailWebControl.GetCssUrls()](retailwebcontrol-getcssurls-method-microsoft-dynamics-retail-ecommerce-sdk-controls.md).

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls](microsoft-dynamics-retail-ecommerce-sdk-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function GetCssUrls As Collection(Of String)
'Usage
Dim returnValue As Collection(Of String)

returnValue = Me.GetCssUrls()
```

``` csharp
protected override Collection<string> GetCssUrls()
```

``` c++
protected:
virtual Collection<String^>^ GetCssUrls() override
```

#### Return Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  

## See Also

#### Reference

[MiniCart Class](minicart-class-microsoft-dynamics-retail-ecommerce-sdk-controls.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls Namespace](microsoft-dynamics-retail-ecommerce-sdk-controls-namespace.md)

