---
title: CheckoutControl.IsDemoMode Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls)
TOCTitle: IsDemoMode Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.CheckoutControl.IsDemoMode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.controls.checkoutcontrol.isdemomode(v=AX.60)
ms:contentKeyID: 65318303
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.CheckoutControl.IsDemoMode
dev_langs:
- CSharp
- C++
- VB
---

# IsDemoMode Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls](microsoft-dynamics-retail-ecommerce-sdk-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.dll)

## Syntax

``` vb
'Declaration
<ConfigurationPropertyAttribute("isDemoMode")> _
Public ReadOnly Property IsDemoMode As Boolean
    Get
'Usage
Dim instance As CheckoutControl
Dim value As Boolean

value = instance.IsDemoMode
```

``` csharp
[ConfigurationPropertyAttribute("isDemoMode")]
public bool IsDemoMode { get; }
```

``` c++
[ConfigurationPropertyAttribute(L"isDemoMode")]
public:
property bool IsDemoMode {
    bool get ();
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[CheckoutControl Class](checkoutcontrol-class-microsoft-dynamics-retail-ecommerce-sdk-controls.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls Namespace](microsoft-dynamics-retail-ecommerce-sdk-controls-namespace.md)

