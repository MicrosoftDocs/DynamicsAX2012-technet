---
title: ControlsSection.Checkout Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls)
TOCTitle: Checkout Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.ControlsSection.Checkout
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.controls.controlssection.checkout(v=AX.60)
ms:contentKeyID: 65318238
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.ControlsSection.Checkout
dev_langs:
- CSharp
- C++
- VB
---

# Checkout Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls](microsoft-dynamics-retail-ecommerce-sdk-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.dll)

## Syntax

``` vb
'Declaration
<ConfigurationPropertyAttribute("checkout")> _
Public ReadOnly Property Checkout As CheckoutControl
    Get
'Usage
Dim instance As ControlsSection
Dim value As CheckoutControl

value = instance.Checkout
```

``` csharp
[ConfigurationPropertyAttribute("checkout")]
public CheckoutControl Checkout { get; }
```

``` c++
[ConfigurationPropertyAttribute(L"checkout")]
public:
property CheckoutControl^ Checkout {
    CheckoutControl^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.CheckoutControl](checkoutcontrol-class-microsoft-dynamics-retail-ecommerce-sdk-controls.md)  

## See Also

#### Reference

[ControlsSection Class](controlssection-class-microsoft-dynamics-retail-ecommerce-sdk-controls.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls Namespace](microsoft-dynamics-retail-ecommerce-sdk-controls-namespace.md)

