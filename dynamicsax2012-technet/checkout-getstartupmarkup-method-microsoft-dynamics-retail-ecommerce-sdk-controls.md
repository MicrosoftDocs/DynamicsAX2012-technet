---
title: Checkout.GetStartupMarkup Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls)
TOCTitle: GetStartupMarkup Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.Checkout.GetStartupMarkup(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.controls.checkout.getstartupmarkup(v=AX.60)
ms:contentKeyID: 65317949
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.Checkout.GetStartupMarkup
dev_langs:
- CSharp
- C++
- VB
---

# GetStartupMarkup Method

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
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[Checkout Class](checkout-class-microsoft-dynamics-retail-ecommerce-sdk-controls.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls Namespace](microsoft-dynamics-retail-ecommerce-sdk-controls-namespace.md)

