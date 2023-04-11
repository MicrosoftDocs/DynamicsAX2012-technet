---
title: CheckoutControl.DemoDataPath Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls)
TOCTitle: DemoDataPath Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.CheckoutControl.DemoDataPath
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.controls.checkoutcontrol.demodatapath(v=AX.60)
ms:contentKeyID: 65316836
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.CheckoutControl.DemoDataPath
dev_langs:
- CSharp
- C++
- VB
---

# DemoDataPath Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls](microsoft-dynamics-retail-ecommerce-sdk-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.dll)

## Syntax

``` vb
'Declaration
<ConfigurationPropertyAttribute("demoDataPath")> _
Public ReadOnly Property DemoDataPath As String
    Get
'Usage
Dim instance As CheckoutControl
Dim value As String

value = instance.DemoDataPath
```

``` csharp
[ConfigurationPropertyAttribute("demoDataPath")]
public string DemoDataPath { get; }
```

``` c++
[ConfigurationPropertyAttribute(L"demoDataPath")]
public:
property String^ DemoDataPath {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[CheckoutControl Class](checkoutcontrol-class-microsoft-dynamics-retail-ecommerce-sdk-controls.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls Namespace](microsoft-dynamics-retail-ecommerce-sdk-controls-namespace.md)

